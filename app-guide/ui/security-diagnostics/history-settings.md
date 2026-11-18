# Set local execution-history retention: screen reference

Limit completed local records while retaining active executions.

## Open this screen

**Desktop:** Security → History settings, or the settings gear on the [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/desktop-agent-device.md).

**Mobile:** Fifth bottom tab More → Security → History settings. In an agent session, use History settings on the [agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md); its return fallback is the dashboard.

## Controls

| Control or area | Location and behavior |
|---|---|
| Retention period | Whole number 1–365 days; default 30. |
| Maximum completed records | Bounded record count; the screen shows its permitted range/default. |
| Save | Applies the retention policy. |
| Delete completed history | Removes completed records after confirmation. |
| Cancel / Discard | Leaves or discards an unsaved settings draft. |
| Retry, where offered | Rechecks local storage errors. The desktop settings dialog has no dedicated Retry button. |

## Desktop dialog behavior

Retention period accepts a whole number from 1–365 days, default 30. Maximum completed records accepts 1–100000, default 2000. Save trims the inputs, validates both and shows field errors for invalid values.

Review your edited values before saving.

While history is loading, a write is pending or the account/session has changed, the fields, Save and Delete completed history are disabled. Successful Save closes the dialog; failed Save leaves it open with a local-storage error so the values can be checked and saved again.

Delete completed history opens a separate Cancel/Delete confirmation. Cancel keeps records. Delete removes the selected completed records and leaves the settings dialog open; it does not save an edited retention draft. Pending/running records are retained. A failed deletion shows a storage error.

Cancel closes the settings dialog without saving its draft and is disabled during its write. Outside dismissal can still close the dialog; closing does not undo a submitted save or deletion. This dialog does not add a separate unsaved-draft confirmation.

## Mobile screen behavior

The two fields accept digits only: Retention period is 1–365 days, default 30; Maximum completed records is 1–100000, default 2000. Save or the second field's keyboard Done attempts to save both values. Invalid values show field errors; editing a field clears its error.

Wait for history to load. Fields and Save are disabled until settings are ready, during history loading or while a local operation is pending. The Save area shows progress during an operation; Back and Retry are also disabled while it is pending. Successful Save returns to the previous screen; failed Save keeps the draft and shows the storage error with Retry.

Back with changed numeric values asks Discard changes? Cancel keeps editing; Discard leaves without saving. Tapping outside that confirmation does not dismiss it. Without changes, Back returns directly. The fallback is Security for personal history and the agent dashboard for agent history.

Delete completed history is disabled when there are no completed records. Otherwise it opens a separate Cancel/Delete confirmation. Delete removes the selected completed records, keeps active records and leaves settings open. It does not save the retention draft.

Retry recovers local history storage; it does not save an edited retention draft or repeat a confirmed deletion. Review current settings and unsaved edits before saving.

After changing accounts, reopen history settings before editing.

## Conditions and results

Reducing either limit can immediately remove older completed records. Pending/running records are kept even when completed history is cleared. Clearing this history does not delete chat messages or stop active tools.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/history-settings.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/README.md)

Reviewed: 2026-10-24 (desktop settings dialog; mobile settings screen, confirmations, storage recovery and agent return fallback). UI labels use the English app language.
