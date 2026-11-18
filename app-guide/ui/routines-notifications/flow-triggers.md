# Automatically run Flows: screen reference

Start one or more saved Flows from a schedule or notification event.

## Open this screen

**Desktop:** Flow → Notification hooks & scheduler → Manage, or Routine → Create → Flow target.

**Mobile:** Flow → Hooks and scheduler, or Shortcuts → Routine → Create → Flow.

## Controls

| Control or area | Behavior |
|---|---|
| DingDong notification hooks / Mobile notification hooks / Schedulers | Opens the relevant rule category. |
| Add / Create | Opens a rule editor. |
| Manage | Desktop expands a compact category into full management. |
| Notification sources | DingDong-event rules use Chat, Flow or All activity source selectors. |
| App / title / content filters | Limits eligible notification events. App filter belongs to Android events. |
| Repeat / date / time / weekdays / day / timezone / late window | Scheduler controls match the response-schedule timing controls. |
| Target Flows | Chooses one or more saved Flows. |
| Trigger mode / Run location | Mobile offers Always/Desktop/Mobile for DingDong hooks and Schedulers. Android hooks do not offer this setting. |
| Enabled / Edit / Delete | Toggles future triggering, changes settings or removes the rule. |
| Save / Cancel / discard confirmation | Resolves rule edits. |

## Conditions and results

Desktop Flow-hook/Scheduler editors preserve an existing execution condition and create new rules with connected normal desktop as the condition; they do not offer a trigger-mode picker. Mobile editors can change that condition. Read the saved policy in Routine details.

Saved target graphs must be executable, and device tools still need eligible available devices. A rule can target multiple Flows. Deleting it does not delete them or cancel their active runs. If a creation result needs verification, refresh/retry verification before creating another copy.

[Source selection](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/notification-sources.md) · [Schedule timing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/scheduler.md).

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/flow-triggers.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
