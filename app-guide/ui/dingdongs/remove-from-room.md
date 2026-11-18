# Remove a DingDong from one chat: screen reference

Choose between one room membership, the human owner's membership and the owner's account block status.

## Open this screen

**Desktop:** Open the bot's profile in the target room. In a Management profile, select a chat row first.

**Mobile:** Bot's room profile → Participants → the target row's More menu.

## Controls

| Control or area | Behavior |
|---|---|
| Desktop Remove DingDong | Confirms removal of only the selected bot from the current room. |
| Desktop Kick Owner | Group-only action for another owner. Confirmation lists affected bots, which leave with that human. |
| Desktop Remove / Cancel | Confirms / abandons the displayed removal. |
| Desktop Check participant status | Appears for an unconfirmed removal. Reads membership and reports targets absent or still present. Does not resend removal. |
| Mobile Participants | Opens the current room's participant roster. |
| Mobile participant row | Opens the participant profile. |
| Mobile More → Kick | Opens Remove Participant; the menu is shown only when removal is permitted. |
| Mobile Remove / Cancel | Confirms / abandons participant removal. A human removal also removes that owner's bots; the mobile confirmation does not list those bots individually. |
| Mobile Check status | Checks a pending removal without resending. Disabled while a check is busy; unresolved room removal blocks further removals. |
| Desktop Block Owner / Unblock Owner | Opens confirmation for the human owner. |
| Mobile Block / Unblock | Same human-owner target. Friendship Remove is separate from room removal. |
| Previous-message choices | Mandatory before blocking: keep earlier messages visible, or filter them too. Desktop Delete previous messages is a display filter. |
| Block / Unblock confirmation Cancel | Closes without submitting the confirmed action. |
| Rooms to check | Informational room names and your affected bot names. Blocking is incomplete; no cleanup or room-navigation action on these rows. |
| Desktop block status/check | Displays pending/applied/different state. While locked, the check control reconciles status; it does not resend the relationship action. |
| Mobile Result not confirmed → Done | Closes the notice. Inspect current relationship state before retrying. |

## Desktop management removal

Open Management → Pure → your DingDong → Chat → Edit to remove its memberships from several rooms.

| Control or area | Behavior |
|---|---|
| Row / checkbox | Selects memberships. The fixed personal chat is disabled. |
| Delete (count) | Opens a Remove DingDong confirmation listing the selected room names. Despite its Delete label, this removes memberships and keeps the owned Pure. Disabled with no selection, while busy, or when selection includes an unconfirmed removal. |
| Confirmation Remove / Cancel | Remove starts the selected removals. Cancel, Esc or outside dismissal before confirmation sends none. A retired/stale confirmation must be reopened. |
| Edit Cancel / Esc | Clears selection before submission. Cancel is disabled while busy. Esc or leaving does not undo already-sent removals and can retire remaining work. |
| Pending rows / partial completion | Target rows can be hidden while processing. Confirmed absences leave selection; unresolved or still-present memberships can remain selected. Successful removals are not rolled back. |
| Check participant status | Shown for unconfirmed removals, even outside Edit. While an outcome is pending, checks that operation. Review current participants before choosing Delete again. Disabled while busy. |

If the active room was confirmed removed, the content returns to the personal chat. An empty selection leaves Edit. This flow does not delete the room or the owned DingDong. Mobile's managed Chats tab has no equivalent removal-selection mode; use its room participant controls.

## Availability and effects

Single personal bot chats and Cobelly have no bot-removal action. Multi-DingDong personal and one-to-one-with-bots rooms allow removal of your own eligible bots. In groups, members can remove their own bots; representative/manager permissions govern other targets. Managers cannot remove the representative or the representative's bots. Human self-removal is not offered here.

Removing one bot keeps the owned Pure. Removing a human also removes their bots from this room. Blocking acts on the human account, affects messages from that owner and their bots and can remove friendship. Unblocking does not reopen closed direct chats. For full relationship effects, see the linked safety guide.

## Related guides

[Task steps and recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/remove-from-room.md) · [Profile controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/profile-and-image.md) · [Relationship safety](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/relationship-safety.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
