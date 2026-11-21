# Read the viewer and chat in a KnowledgeBox app

A static app served from a KnowledgeBox folder on desktop, Android or iOS can ask Cobell who opened it and from which chat. Use this when the page needs to select a player's settings, resume a draft for one participant, or distinguish two chats using the same app.

## Request and response

From the served page, send a same-origin `GET /.well-known/cobell/app-share-context`. The leading slash also works from nested entry pages. The request takes no parameters, body or app-supplied credentials. If the owner restricts the app’s allowed paths, include this exact path alongside the page and its assets.

Opening the app from a chat returns `application/json` with the viewer’s Cobell user ID and the chat where they opened it. This example shows user 42 opening the app from a group chat.

```json
{"user_id":"42","room":{"room_type":"ROOM_TYPE_FRIENDS","room_id":"71"},"local":false}
```

Opening the same folder with **Open on this device** returns the owner's user ID and a null room.

```json
{"user_id":"42","room":null,"local":true}
```

An owner who opens a **chat share** gets that chat and `local: false` just like any other participant. Treat all IDs as strings. Identify a chat by both `room_type` and `room_id`. The same room ID can occur in different room types.

## JavaScript example

The example displays the current scope in an element with `id="scope"`. Load the script after that element or use `type="module"`.

```js
async function showScope() {
  const label = document.getElementById("scope");
  try {
    const response = await fetch("/.well-known/cobell/app-share-context", {
      mode: "same-origin",
      cache: "no-store"
    });
    if (!response.ok) throw new Error("Viewer context unavailable");
    const { user_id, room, local } = await response.json();
    label.textContent = local
      ? `Local preview for user ${user_id}`
      : `User ${user_id} in ${room.room_type} / ${room.room_id}`;
  } catch {
    label.textContent = "Open this app in Cobell to see the current viewer.";
  }
}

showScope();
```

Fetch the context when opening or resuming a viewer-dependent activity. If the request fails, leave that activity unavailable until it succeeds. Use the returned ID for display or local state. An external server that accepts writes must authenticate them independently. This endpoint identifies one viewer and chat. Names, room membership lists and other viewers’ connection data are outside its scope.

## Verify during development

1. Use a direct file preview to check layout and ordinary controls. Viewer context is available when Cobell serves the folder through App Share.
2. Sign in normally and choose **Open on this device**. Check the local branch with `room === null`.
3. Open the app through an enabled chat share. Check the same account from a second shared chat and a second participant from the first chat. Only the chat should change in the first case and only the user in the second.

This built-in endpoint belongs to static folder hosting. A desktop HTTP server that you register as an app implements its own browser-facing routes.

[App Share feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md) · [Registration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/register.md)
