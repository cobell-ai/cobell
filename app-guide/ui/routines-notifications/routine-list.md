# Manage automatic Routines: screen reference

Manage three trigger types: DingDong notification, Mobile notification and Scheduler. Each can request an AI response or run Flows.

## Open this screen

**Desktop:** Main navigation → Routine.

**Mobile:** Shortcuts → Routine. DingDong settings and Flow Hooks and scheduler also open their respective rules.

## Controls

| Control or area | Behavior |
|---|---|
| Search routines | Filters entries by search text. |
| Trigger / Target filters | Chooses a trigger type or AI response/Flow target. |
| All / Active / Paused | Filters activation state; summary counts describe the available list. |
| Refresh / Retry | Reloads rules after a stale or failed read. |
| Create / Add | Chooses trigger type and target type, then opens the relevant editor. |
| Chat room / responder picker | For AI response, selects a supported room and one of the user's DingDongs in that room. Desktop can show only selectable rooms. |
| Flow target picker | Selects one or more Flows for a Flow rule. |
| Routine row / details | Shows trigger, target and execution policy. |
| Enabled switch | Pauses or re-enables future triggering. |
| Edit / Delete | Changes a rule or confirms removal. |
| Review before saving | Desktop creation presents a summary before committing the rule. |

## Conditions and results

Pausing or deleting a rule changes future triggering; it does not delete its target or stop work already running. Failed reads can leave partial or cached lists. A failed toggle must not be treated as a successful state change.

Routine details do not provide a combined execution history. Use the originating notification's trigger history and the target chat or Flow's execution history to check results.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/routine-list.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
