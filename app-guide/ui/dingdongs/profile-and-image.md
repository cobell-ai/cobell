# Inspect a DingDong and manage its image: screen reference

Inspect a bot's selected-room configuration, related chats and avatar.

## Open this screen

**Desktop:** A chat's bot avatar, or Management → Pure → the bot's profile control. Management opens the chat-list view first.

**Mobile:** A bot participant's profile, or the owned bot's management Open profile action. Actions require the current normal account and accessible data.

## Desktop controls

| Control or area | Behavior |
|---|---|
| Profile header Back | Returns from the selected room's profile to the Management profile's chat list. |
| Close | Closes the profile dialog. |
| Chat row | Selects this profile's room context. Does not open the conversation. Rows can show last message, time and unread count. |
| Chat-list Retry | Reloads room reads. Retained rows can remain below a refresh-failure notice; initial reads can show a loading indicator. |
| Public configuration / Visible to everyone | Read-only Active, Bell permission, intelligence and Auto Reply/interval/delay. Mode is omitted for Cobelly. |
| Visible only to you | Owned bot's embedded room settings, with the bot selector locked. Personal bot chats show the settings panel directly. |
| Owner | Displays owner name/avatar. No owner-profile navigation. |
| View Image / avatar | Opens the current avatar. |
| Generate profile image / View generation status | Owner-only, state-dependent image controls; see the image guide. |
| Block Owner / Unblock Owner | Acts on the human owner's block status. |
| Remove DingDong / Kick Owner | Conditional room actions; see the removal guide. |

The list shows related chats available to the current account and may not include every room. Select the intended room before reviewing its DingDong configuration. Reopen the list if it looks incomplete.

## Mobile controls

| Control or area | Behavior |
|---|---|
| Back | Returns to the previous route. |
| View larger | Opens the avatar. Pinch to zoom, drag to move and use Back to return. |
| Manage image | Opens a supported owned bot's image management. |
| Public configuration | Read-only Enabled, Mode, Auto Reply, Delay and Bell permission. No intelligence row in this card. |
| DingDong settings | Owner-only when supported in this room; bot selection is locked. |
| Chats with this DingDong | Available related chats containing this DingDong. Select a row to open its profile in that room. The list may not include every room. |
| Hidden chats label | Identifies a hidden room; selecting it does not unhide it. |
| Chat-list Retry / loading indicator | Refreshes directory reads after a failure / shows a pending read. |
| Open chat | Opens the current profile's conversation. |
| Participants | Opens this room's participant list. Removal is available there when permitted. |
| DingDong management | Opens the owned bot's management detail when available. |
| Block / Unblock / Remove | Human-owner safety actions. Friendship Remove appears for a friend who is not blocked; it is not bot removal. |

There is no navigable Owner row in the mobile bot profile. A missing or inaccessible scoped participant can show an unavailable profile; return and reopen from the current chat. The unavailable view has no general Retry button.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/profile-and-image.md) · [Room removal and owner safety](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/remove-from-room.md) · [Image controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/avatar-generation.md) · [Behavior settings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/behavior.md) · [Gear controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
