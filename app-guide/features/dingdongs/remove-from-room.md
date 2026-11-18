# Remove a DingDong from one chat

Remove one bot's room membership, or remove a human owner and their invited bots from a group. This does not delete the owned Pure from Management.

## Desktop steps

1. Open the DingDong's profile in the intended room. From its Management profile, select the room row first.
2. To remove only the bot, choose Remove DingDong and review the bot/room confirmation.
3. To remove another human owner from a group, use Kick Owner when available. Review the affected DingDong list: this action also removes their bots from that room.
4. Confirm Remove, or Cancel to keep membership unchanged.
5. If removal could not be confirmed, use Check participant status. It reads the participant state rather than sending removal again. Review whether the targets are absent or still present before starting another action.

## Mobile steps

1. In the bot's room profile, choose Participants.
2. On the desired bot row, use More → Kick. Tapping the row itself opens its profile.
3. Review Remove Participant, then Remove or Cancel. To remove a human owner and their bots instead, use that human's participant-row menu when permitted.
4. If the removal banner says the result is uncertain, use Check status. This checks membership without sending another removal. Further removals in that room wait until the pending result is resolved. If the target is still listed, review the current list before trying again.

The mobile bot profile's friendship Remove button acts on its human owner; it is not the participant-removal menu. The mobile participant confirmation names the selected target and does not enumerate affected bots when removing a human.

## Remove from several rooms in desktop management

1. Open Management → Pure → your DingDong → Chat → Edit. Select room rows or checkboxes. The fixed personal chat cannot be selected.
2. Choose Delete (count), review the Remove DingDong confirmation and its room names, then Remove. This removes memberships while keeping the owned Pure. Cancel, Esc or outside dismissal before confirmation sends no removal. Reopen a confirmation that closes after account, access or selection changes.
3. Wait for the result. Target rows can temporarily disappear while processing. Confirmed absences leave selection; failed or unresolved targets can remain. Earlier successful removals stay completed if later work fails or stops.
4. For an unconfirmed result, use Check participant status, which can appear outside Edit. Check the pending outcome and current participants before choosing Delete again. Delete is disabled if the current selection includes an unconfirmed removal.

Edit's Cancel clears selection before submission and is disabled while busy. Esc or leaving does not undo a sent removal and can retire remaining work. Confirmed removal of the active room returns content to the personal chat; clearing the final selection exits Edit. Mobile's managed Chats tab does not offer this batch selection; use room participant controls there.

## Permission limits

- A single personal DingDong chat has no room-removal action. Cobelly is excluded from bot removal.
- In a multi-DingDong personal room or a one-to-one room with bots, you can remove your own eligible bots. You cannot remove the other human through this action.
- In groups, members can remove their own eligible bots. Representatives can remove other participants. Managers cannot remove the representative or the representative's bots.
- You cannot remove yourself with the human-removal action. Closed, inaccessible or stale room/participant data can disable or retire a pending action. Reopen the current room before deciding again.

## Blocking the owner instead

Desktop Block Owner / Unblock Owner and mobile Block / Unblock act on the human account. They do not mean “remove just this bot.” If you are friends, blocking also removes the friendship.

Before blocking, explicitly select whether earlier messages remain visible. Desktop calls the options Keep previous messages / Delete previous messages; mobile uses Keep previous messages visible / Hide previous messages. The latter choice is a visibility filter, not physical message deletion. Confirm remains disabled until you select an option. Cancel leaves the block unchanged.

If Rooms to check is shown, blocking has not completed. Close the notice, leave the listed rooms or remove your own DingDongs from them, then request blocking again. The room rows are information, not shortcuts that perform cleanup.

Desktop can show the pending block/unblock status and a status-check control. Use it if the result is unconfirmed or local completion is pending; it does not submit the block again. Mobile's Result not confirmed notice has Done; check current friendship/block status before requesting the action again.

Read [relationship safety](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/relationship-safety.md) for direct-chat closure, group message filtering and unblocking effects. Unblocking does not reopen closed direct chats.

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/remove-from-room.md) · [Bot profile](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/profile-and-image.md) · [Delete an owned Pure](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/maintain-pure.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
