# Schedule an automatic DingDong response: screen reference

Submit a prompt once or on a repeating schedule.

## Open this screen

**Desktop:** Routine → Create → Scheduler → AI response, or DingDong Settings → Scheduler → Add.

**Mobile:** Shortcuts → Routine → Create → AI response/Scheduler, or the responding DingDong's Hooks and scheduler.

## Controls

| Control or area | Behavior |
|---|---|
| Chat room / Response DingDong | Chooses your responder and destination room. |
| Repeat | Once, Daily, Weekly or Monthly. |
| Time / Date | Time applies to the schedule; Once also needs a future date. |
| Weekdays | Weekly schedules select one or more days. |
| Day of month | Selects the monthly day. |
| Schedule timezone | Displays how a new local timezone or an existing saved timezone is used. |
| Late execution window | 0–60 minutes of allowed lateness; a run missed beyond this window is skipped. |
| Prompt | Instructions for the scheduled response. |
| Response context | Room main conversation or a new top-level thread. |
| Trigger mode / Run location | Always, connected normal desktop or connected normal mobile session. |
| Save / Cancel / discard confirmation | Saves the rule or resolves unfinished edits. |
| Enabled / Delete | Rule-list/details controls pause, resume or remove the saved rule. Mobile also offers activation in the editor. |

## Conditions and results

New schedules use the creating device's local timezone; saved schedules retain their timezone. Recurring wall-clock times follow that saved zone, including daylight-saving changes. Moving the device to another zone does not retarget the saved schedule.

Always can trigger while devices are offline. Device tools still require eligible available devices. Desktop/mobile trigger conditions refer to normal signed-in sessions rather than agent sessions. A creation-verification warning requires refresh/retry of verification before creating another copy.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/scheduler.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
