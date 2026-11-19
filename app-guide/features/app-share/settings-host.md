# Change an app's settings or host

## Settings

1. Open Apps → owned app → Operate → Settings/App settings. Mobile Apps is under More.
2. Set the name and allowed path prefixes, one per line. Use a prefix such as `/reports` to limit accessible paths, or `/` to allow all paths. Leaving the list empty also allows all paths.
3. Set End-to-end encryption and save. Changing encryption disconnects current viewers.
4. To remove the registration instead, choose Delete and confirm. This ends its shares and connections; it does not remove the web app's files from the host.

In **App avatar**, choose a style and optionally supply a prompt and up to five reference images. Review the generated candidate and apply it when ready. The owner can replace or remove the avatar while the app is serving.

## Hosting

1. Open the registered app's Operate screen on the intended host with normal sign-in.
2. For static HTML on desktop or mobile, use Choose KnowledgeBox folder and confirm its start page. For a desktop web server, set the local server address under This device's binding and use the integration configuration file in the local app.
3. Open Change host on desktop or mobile. Choose a device already bound to the app; mobile requires confirming Change host.
4. Wait for the app to verify, then check chat sharing. Existing viewers must reopen the app after a host change.

Keep Cobell in the foreground to serve files on mobile. Disconnect source removes the local folder binding and preserves its files. Desktop Replace integration secret replaces that binding's integration secret; ensure the local app uses the updated configuration. For an existing binding, Integration configuration file reopens its path and Delete removes this device's binding without deleting the app registration.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/settings-host.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-11-19.
