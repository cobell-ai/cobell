# Restore a hidden chat: screen reference

Bring a room back to the ordinary chat list.

## Open this screen

**Desktop:** Click your avatar/name near the upper-right → Profile → Chat → Hidden chats.

**Mobile:** Chat → header's Hidden chats eye button. More → profile card → Hidden chats opens the same sheet.

## Controls

| Control or area | Location and behavior |
|---|---|
| Hidden chat list | Shows rooms hidden from ordinary navigation. On mobile, scroll the sheet to see more rows; rows show a name, room type and available preview. |
| Unhide | Restores the selected room. On mobile, tap the explicit row button; the row body and avatar do not open a conversation. |
| Check status (mobile) | Replaces Unhide when the visibility result is uncertain. Checks that result without sending another hide/unhide request. |
| Row progress (mobile) | Replaces the action while that room is busy. Other rows can remain available. |
| Row failure (mobile) | Inline error under the room details; the action becomes available again. Check the remaining status before retrying. |
| Retry | Reloads a failed list. On mobile, a failed refresh can show Retry above retained rows; a loaded empty list has no reload action. |
| Close / Back | Closes the mobile sheet and returns to its caller, including Chat or Profile. Dismissing the sheet does not undo an accepted visibility change. |

## Conditions and results

Hidden Chat Rooms is separate from messages hidden from AI. Restoring room visibility does not reopen a room that was permanently closed.

The mobile sheet supports non-group rooms and excludes Cobelly and Flow. Its Unhide action for a room with blocked remote access restores this device's local history; it does not restore remote access or membership. A normally available room uses its visibility change. The sheet does not navigate into the restored room automatically; return to Chat and open it there.

Use Check status for an uncertain visibility change and read the result before repeating it. This is separate from Leave chat. If loading fails, use Retry; No hidden chat rooms is the ordinary empty state.

Mobile actions require a normal signed-in account; preview and agent sessions cannot open the sheet. After account or access changes, reopen it and use its current controls.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/hidden-rooms.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-24 (mobile sheet controls, visibility checks and local restoration; desktop guidance retained). UI labels use the English app language.
