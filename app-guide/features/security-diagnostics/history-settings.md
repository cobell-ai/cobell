# Set local execution-history retention

Limit completed local records while retaining active executions.

## Start here

**Desktop:** Security → History settings, or the settings gear on the [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/desktop-agent-device.md).

**Mobile:** Fifth bottom tab More → Security → History settings. In an agent session, use History settings on the [agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-device.md); its return fallback is the dashboard.

## Desktop steps

1. Open Security → History settings, or the agent screen's settings gear. Wait for the current account's history to load.
2. Enter whole numbers: 1–365 days for Retention period and 1–100000 for Maximum completed records. Defaults are 30 days and 2000 records. Correct any field errors.
3. Save. A successful save closes the dialog. A failed save leaves it open with a storage error; inspect the values before retrying Save.
4. To delete completed records, choose Delete completed history and review the separate confirmation. Cancel keeps records; Delete removes the selected completed records while keeping active ones and leaves settings open. This does not save an edited retention draft.
5. Cancel closes settings without saving the draft. It is disabled during a write, as are the fields, Save and deletion control. Outside dismissal can still close the dialog; closing does not undo a submitted operation. There is no dedicated Retry button or extra draft-discard confirmation in this desktop dialog.

## Mobile steps

1. Open Security → History settings, or History settings on the agent dashboard. Wait for local history/settings to load; use Retry for a storage error.
2. Enter digits: 1–365 days and 1–100000 completed records. Defaults are 30 days and 2000 records. Editing a field clears its validation error.
3. Tap Save or use the second field's keyboard Done. Correct any field errors. Fields, Back, Retry and Save are disabled during the local operation; the Save area shows progress.
4. Successful Save returns to the previous screen. Failed Save keeps the draft and offers Retry for local history storage. Retry does not save an edited retention draft or repeat deletion; inspect the draft before Save.
5. Use Delete completed history only when completed records exist. Cancel the confirmation to keep them, or Delete to remove the selected completed records while keeping active ones. Settings stays open and the retention draft is not saved by deletion.
6. To leave changed numeric values without saving, use Back and confirm Discard. Cancel keeps editing; outside taps do not dismiss this confirmation. With no changes, Back leaves directly. The fallback is Security or, for agent history, the agent dashboard.

## Completion, limits and recovery

Reducing either limit can immediately remove older completed records. Pending/running records are kept even when completed history is cleared. Clearing this history does not delete chat messages or stop active tools.

Review the displayed values before saving a history-settings draft. After changing accounts, reopen settings from the current account.

Also find this under: retention, delete tool history, local records, history limits.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/history-settings.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/README.md)

Reviewed: 2026-10-24 (desktop settings dialog; mobile settings screen, confirmations, storage recovery and agent return fallback). UI labels use the English app language.
