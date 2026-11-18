# Create a DingDong group: screen reference

Create a room for you and your DingDongs, without inviting other people.

## Open this screen

**Desktop:** Chat panel → DD → Group → plus (New Chat).

**Mobile:** Chat → DingDong → Group Chat → New Chat.

## Shared controls

| Control | Behavior |
|---|---|
| Room Name | Names the new room. Validation runs before creation. |
| Search DingDongs / search field | Matches displayed names or localized type labels, ignoring case and surrounding whitespace. There is no separate type filter. |
| Bot row / selection circle | Toggles a participant. Search changes do not remove selections outside the result. |
| Cobelly / system row | Cannot be selected for another room. Choose eligible owned Pure DingDongs. |
| Selected count | Counts all selected bots, including those outside the current search result. |
| Create | Requires at least one selected bot and a current normal account. Shows progress and blocks another submission while running. Success opens the new room. |
| Empty result | Clear search or create a Pure and reopen selection. This screen has no list Refresh or Retry button. |

## Desktop controls and results

Name, search, selection and Back remain usable while Create is waiting. The submitted request uses the name and bots captured at submission. Back or the containing panel's Esc closes without saving the draft or asking Save/Discard; it does not cancel a request already sent.

A failed creation opens an explanation with Confirm and retains the fields. If a selected bot disappears from the current owned list before submission, creation is refused; reopen the screen to select current bots.

## Mobile controls and results

Room Name has a 40-character limit and inline validation. Editing the name clears its previous error. Name, search, rows and Back are disabled during creation. Failure shows a message and retains the fields.

Back or system Back opens Discard changes? when name or search contains nonblank text, or bots are selected. Cancel or dismissal keeps editing; Discard leaves without saving. An unchanged blank screen leaves directly. Leaving is blocked while creating. Changing accounts retires this screen.

Choose from the current account's available owned DingDongs. If a selected bot is no longer available, reopen and select again. Preview cannot submit creation.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/dingdong-group.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

[Create friend chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/create-room.md) · [Create a Pure](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/create-pure.md)

Reviewed: 2026-10-24. UI labels use the English app language.
