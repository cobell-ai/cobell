# Create a direct or group chat: screen reference

Start a new conversation with friends or an owner-only DingDong group.

## Open this screen

**Desktop:** Fr → Direct or Group → plus (New Chat). DD → Group → plus creates an owner-only DingDong group. DD → List → plus creates a DingDong instead.

**Mobile:** Chat → Friends → Direct or Group → New Chat. For bots, use Chat → DingDong → Group Chat → New Chat.

## Controls

| Control or area | Location and behavior |
|---|---|
| New Chat / New Group Chat | Friend direct/group creation modes. |
| Search friends | Narrows displayed friends by name. In desktop group creation, previously selected friends remain selected outside the search result. |
| Direct-room friend row (desktop/mobile) | Immediately requests a new direct room with that friend; there is no separate Create button. |
| Room Name | Names a new group. |
| Selection circles / count | Selects participants and shows how many are chosen. |
| DingDong group creation | Has its own name, search and selection screen; see the linked guide below. There is no separate type filter. |
| Desktop group Create | Sends the named group and selected participants. Requires a signed-in account and at least one selected friend; name validation runs on submission. Busy progress disables this button. |
| Desktop preselected friend from a profile | A profile's group-creation route can lock that person in the selection. Their row cannot be deselected. |
| Create (other creation screens) | Submits the selected room where offered. |
| Create and request votes | Confirms a plan requiring participant approval. |
| Desktop friend creation Back / panel Esc | Closes the creation view. This path has no Save/Discard prompt or automatic draft saving. |
| Desktop approval-plan Cancel / information Confirm | Cancel declines the proposed fallback plan; Confirm dismisses a result or failure explanation. |
| Mobile New Group Chat switch | Switches direct/group mode and clears participant selection. Turning it off also clears the group name. |
| Mobile name / search / selection | Room Name has a 40-character limit and inline validation. Search matches displayed friend names without case sensitivity; hidden search results retain their selections. |
| Mobile Retry after directory load failure | Reloads the selection directory when loading failed and there are no candidates; disabled during creation. An empty search result has no separate action. |
| Mobile Back / system Back | If the draft changed, opens Discard changes? Cancel or dismissal keeps the draft; Discard leaves. Search text alone can trigger this check. |
| Mobile creation in progress | Disables name/search, mode switches, people rows, Create and leaving this screen. The button shows progress. |
| Mobile compact controls scroll | With the keyboard open or little vertical space, scroll the upper controls to reach mode, name and search; candidates use a separate list. |

## Conditions and results

Friend direct rooms require an explicit friendship. Some group participants require approval votes. If the room is created but votes fail to start, invite the remaining people through room settings. Cobelly cannot be invited into another room.

In desktop group creation, inspect the initial participants and the people who will need votes before choosing Create and request votes. Selected friends and the name remain available after a creation failure. Name and participants are captured when you submit; edits made while waiting do not change that request. Closing the view does not cancel a request already sent. Check the room list and participants before creating again after an uncertain result.

On mobile, a creation failure shows a message and retains the draft. Correct any Room Name error before retrying. Back asks before discarding changes; no draft is saved after leaving. Use a normal account; preview cannot create a room.

If mobile group creation succeeds but starting invitation votes fails, the room can open with an invitation-failure banner. Retry resends its stored invitation selection for that existing room and shows progress; it does not create another room. Failure retains the banner. A completed invitation attempt does not mean the invitees' votes were approved. See the invitation guide.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/create-room.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

[Create a DingDong group](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/dingdong-group.md) · [Invitations and votes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/invite-people.md)

Reviewed: 2026-10-24 (desktop friend creation and mobile direct/group creation controls). UI labels use the English app language.
