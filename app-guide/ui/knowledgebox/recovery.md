# Review unfinished mobile file changes: screen reference

Inspect unfinished file changes and retained copies in this phone's current KnowledgeBox folder.

## Open this screen

**Desktop:** For desktop workspace problems, open Workspace settings and check the binding; the mobile recovery inspector is not a desktop dialog.

**Mobile:** Third bottom tab Shortcuts → DingDong → select your Pure → Knowledge → Knowledge file recovery, or Review pending changes when shown.

## Controls

| Control or area | Location and behavior |
|---|---|
| Check again / pull-to-refresh | Rechecks this local folder and retries verifiable pending work. Disabled while checking. Failed checks can leave details from a previous check, marked as stale. |
| Issue reason / affected paths | Read why review is needed and inspect the listed paths before choosing a recovery action. |
| Inspect files and copies | Opens an eligible record's inspection screen. Unavailable or unverified records can lack an opening action. |
| Current file / Retained copy | Labels the source of each row. Open a file/directory row to inspect it; missing or unavailable entries cannot be opened. |
| Affected files / Parent folder / Back | Returns to the record overview or parent within the inspection. Back from a nested location goes up before leaving the inspector. |
| File text / kind / size | Shows available read-only text and file information. Empty, non-text and missing files have separate states. A limited preview does not mean retained data was deleted. |
| Descriptions saved before the change | Shows saved descriptions/summaries for reference in the overview; some previews can be partial. Opening does not apply them to current files. |
| Copy to a new folder | Offered for an available retained file/directory, including its root from the overview. Confirmation copies it into a separate folder in this KnowledgeBox; the UI supplies a name based on Recovered files and displays the resulting path. No destination-name input is offered. |
| Copy progress / copied path | Shows progress while copying, then the created folder path. A failed copy retains the saved copy; check connection/storage and reload if the record changed. |
| Use current files | When offered on the record overview, asks for confirmation to keep present files, their current descriptions and available recovery records/copies. |
| Retained recovery records → Open retained record | Reopens retained recovery information for review. Read the current status and use the actions offered there. |
| Inspector Check again / Retry | Reloads the inspected location after a failed read or changed folder/record. |
| Done | Appears after a completed check with no active check, failed check or blocking issue. Returns from the recovery list. |

## Conditions and results

Recovery concerns this device's connected folder under the current owner; it is not a cross-device backup browser. It requires a normal signed-in owner and an available local binding. For a missing folder or connection problem, use the workspace controls described in [Workspace setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md).

Inspection is read-only. A visible current file does not prove the interrupted operation completed. Copy to a new folder preserves both current files and the retained source; it does not finish review of pending changes. Use current files accepts this record's present state and retains copies for later inspection; other records can still need attention.

File updates can remain paused while review is required. If confirmation was interrupted or its result is uncertain, reopen the record and check its current status before confirming again. Do not treat a previous check's stale details as a fresh result.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
