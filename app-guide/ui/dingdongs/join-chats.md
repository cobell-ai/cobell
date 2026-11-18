# Join several chats with one DingDong: screen reference

Select room targets for an owned bot from management.

## Open this screen

**Desktop:** Management → Pure → the bot → Chat → Join in the Chats list header, outside edit mode.

**Mobile:** Shortcuts → DingDong → your Pure → Chats → Join chats.

## Desktop controls

| Control or area | Behavior |
|---|---|
| Room row / checkbox | Selects an eligible friend direct or group chat. For personal multi-DingDong groups, invite from that room instead. |
| Loading / empty state | Waits for room data / reports no available targets. No search or dedicated Retry control. |
| Policy lock notice | Disables joining until the owned bot's invitation policy is on. |
| Join (count) | Starts joining the selected rooms and shows required Gear setup. No additional final confirmation. |
| Gear setup Save / Cancel | Save keeps the room's setup. Cancel stops the remaining work; changes already saved remain saved. |
| Completed room | No longer pending or selectable within this dialog. Earlier successes remain if a later room fails. |
| Cancel | Closes when idle. Disabled while submitting. |
| Header Close | Also closes when idle and is disabled while submitting. Does not undo earlier setup saves or joins. |
| Esc | Dismisses the active join/setup dialog. It does not undo a request already sent. |
| Failure/unconfirmed notice | Stops at the first failed room. Inspect participants/Gear before retrying; no Check invitation status button. |

## Mobile controls

| Control or area | Behavior |
|---|---|
| Room checkbox | Toggles an available target in the current visible directory. Already joined rows remain checked and disabled. |
| Availability label | Explains already joined, closed, guest restriction or incomplete room information. |
| Policy loading / Retry | Shared targets wait for policy; Retry reloads a failed policy read. Owner-only multi-DingDong rooms bypass the policy. |
| Join selected chats (count) | Starts joining selected rooms and shows Gear setup when needed. Disabled while saving or when selection is unavailable. |
| Setup Save / Back | Save returns the explicit Gear choice; Back without choosing stops the remaining batch. Previously joined rooms remain joined. |
| Joined count | Reports completed memberships in this screen, including memberships needing Gear repair. Successful rooms leave selection. |
| Failed count | Failed rooms remain selected; later rooms are still attempted. Inspect the current roster before submitting again. |
| Back / discard confirmation | With selected rooms, asks before clearing the selection. Busy state blocks leaving; it does not undo prior joins. |

## Conditions and recovery

Normal account, owned supported bot and current room access are required. Group guests cannot invite bots; Cobelly is excluded. A row's availability is not confirmation that a future request will succeed.

A joined room can still need Gear setup. Some rooms may complete while others fail; earlier successful joins and saved settings remain. Check current participants and Gear before retrying unfinished rooms.

## Related guides

[Browse the bot's chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/browse-chats.md)

[Task steps and recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/join-chats.md) · [Room invitation controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/invite-to-room.md) · [Gear setup controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
