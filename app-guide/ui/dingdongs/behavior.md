# Change DingDong behavior in a room: screen reference

Change an owned DingDong's response settings in the current room. Most controls save when changed; the people picker has its own confirmation.

## Open this screen

**Desktop:** Right-click the room row → DingDong Settings. Select your DingDong at the top when several are present.

**Mobile:** Chat → room settings → DingDong Settings. With several owned DingDongs, use the top dropdown; with one, its name is plain text.

An unconfigured DingDong first requires [compatible Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md). If an owned bot is unavailable, return to the current DingDong list and check its status.

## Response controls

| Control | Behavior |
|---|---|
| Active / Enabled | Desktop shows Active outside individual DingDong rooms. Mobile also shows Enabled in individual rooms. Off disables the response controls below it and prevents new permitted invocations; it does not delete the DingDong or Gear. |
| Desktop Mode | Pure uses Questioner/Decider segments with description tooltips. Cobelly uses a popup with both mode descriptions. Choosing starts saving. |
| Mobile Agent mode | Dropdown offers Questioner and Decider; choosing a different value starts saving. |
| Intelligence Level | Both sliders offer integer levels 1–7. Dragging previews a level; releasing submits it. |
| Show inner thoughts / Show thinking and working messages | Desktop Off/On; mobile Show/Hide. Controls emission of intermediate thinking messages for responses; changing it does not delete existing chat messages. |
| Goal Mode | Off by default. Applies to runs started with the Bell in this chat. Running or paused runs keep their original setting. Resuming a failed run uses the current setting. |
| Allow DingDong to edit its Memories | Owner setting, on by default. Applies to this DingDong across chats. See [Memory self-editing and locks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/memory-self-edit.md). |
| Auto Reply | Desktop Off/On; mobile Allowed/Not Allowed. On reveals reply scope, message interval and delay controls. Off hides those controls without clearing their saved values. |

Questioner discusses open choices during work and proceeds when the direction is clear. Decider selects an approach and asks essential questions. Cobelly's settings and the Start/Home mode control edit the same saved mode. On desktop, its menu is disabled while loading or saving; Mode unavailable offers Retry with the mode choices disabled until loading succeeds. A failed mode save restores the earlier choice and shows an error.

## Bell permissions and people

Bell permissions apply to other human participants. For an enabled bot, the owner keeps permission even when the group option says Not allowed or Do not allow anyone.

| Room or control | Behavior |
|---|---|
| One-to-one chat with another person | Other Party on desktop or Bell permission on mobile offers Not Allowed/Allowed for that person. |
| Group permission dropdown | Desktop: Not allowed, All allowed, Some allowed, Some excluded. Mobile: Do not allow anyone, All allowed, Allow selected people, Allow everyone except selected people. The policy saves on selection. |
| Allowed Users / Allowed people | Under the selected-people policy, opens a picker for the allowed list. An empty list allows no other participants. |
| Excluded Users / Excluded people | Under the exclusion policy, opens the excluded list. An empty list excludes no other participants. |
| Person checkbox | Changes the picker draft. Candidates are humans currently in the room, excluding the bot owner; bots are not candidates. |
| Desktop Confirm / Cancel | Confirm closes and starts saving the chosen list. Cancel discards the draft. There is no search or select-all control. |
| Mobile Save / Back | Save closes and starts saving the list. Back discards the draft; it does not save checked rows automatically. |

Changing the group policy alone does not clear its saved allowed/excluded lists. Review the relevant list when switching policies. Personal DingDong rooms remain owner-only; controls rendered in a mobile personal DingDong group do not grant access to other people.

## Automatic reply controls

| Control | Behavior |
|---|---|
| My messages only | Desktop checkbox in chats with other people. Checked counts the owner's eligible messages; unchecked also counts eligible messages from people allowed to use this bot's Bell. Personal rooms, including owner-only DingDong groups, force owner-only counting and hide this checkbox. |
| Mobile reply scope | Use Reply only to my messages in personal DingDong rooms and groups. In other eligible rooms, choose between your messages and messages from people with Bell permission. |
| Reply Interval | Choose from the available 1–7 message settings. Desktop uses a dropdown; mobile uses a slider and saves on release. This sets a message interval, not seconds. |
| Reply Delay / Wait before replying | Checking enables a 5-second delay; unchecking saves 0. Enabled delay can be set from 5–30 seconds, saving on slider release. Desktop leaves the slider disabled at 0 when off; mobile hides it. Turning delay back on starts at 5 seconds. |

Auto Reply is not a guaranteed schedule. AI-hidden messages do not trigger it. Mentioning the bot can request an immediate response separately from the automatic delay.

## Conditions and results

There is no page-wide Save or discard transaction. Selectors and switches submit immediately; sliders submit on release; the people picker submits on Confirm/Save. Leaving settings does not undo an update already sent. A visible new value may still be awaiting confirmation. Failure can restore confirmed settings; reopen the room to check an uncertain result before editing again.

If a change fails or its result is uncertain, reopen the current settings or use Retry to read saved values before changing them again. Reopen the people picker after account, room or access changes.

Behavior settings apply to the selected bot in this room. The separate new-chat invitation policy affects future invitations and has its own [guide](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md).

Desktop's lower DingDong Notification Hook, Mobile Notification Hook and Scheduler counts open their management dialogs. Mobile offers Routines and trigger-specific entries for non-System DingDongs. These are separate from Auto Reply; use the [routine guides](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md).

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/behavior.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Schedule an automatic DingDong response](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/scheduler.md)

Reviewed: 2026-10-23. UI labels use the English app language.
