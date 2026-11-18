# Automatically run Flows

## Add an automatic Flow run

1. Open Flow → Hooks and scheduler or create a Flow-target Routine.
2. Choose DingDong notification, Mobile notification or Scheduler.
3. Select notification sources and filters, or configure repeat/date/time/timezone and the late execution window.
4. Select one or more target Flows.
5. Review activation and the execution condition, then save.

## Set execution conditions

Mobile lets you choose Always, connected normal desktop or connected normal mobile for DingDong hooks and Schedulers. Desktop creates these Flow rules with the connected-normal-desktop condition and preserves an existing condition when editing. Inspect the saved policy in Routine details. Android event hooks do not have this selector.

## Completion and recovery

Check that each target's saved graph has complete task assignments. Android events also require observation access on Android. If the app says a created rule still needs verification, refresh/retry verification before adding another copy.

Use Enabled to pause future triggering. Inspect each Flow's execution history for results. Removing a rule leaves its target Flows and active executions intact.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/flow-triggers.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
