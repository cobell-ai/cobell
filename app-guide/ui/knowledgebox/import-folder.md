# Import a directory tree: screen reference

Review a selected folder and import it as a folder under the chosen KnowledgeBox directory.

## Open this screen

**Desktop:** Management → Pure → select your DingDong → KnowledgeBox → choose destination → Add → Add folder.

**Mobile:** Shortcuts → DingDong → select your Pure → Knowledge → Files → enter destination → Add → Import folder.

## Controls

| Control or area | Behavior |
|---|---|
| Select folder / folder picker | Chooses the source directory; canceling the picker does not publish an import. Mobile copies the external selection for import rather than binding it as a workspace. |
| Selection progress / Cancel | Mobile can cancel pending selection/scanning. This is separate from a confirmed import. |
| Name | Mobile sets the new destination folder name after scanning. Desktop preview retains the source folder name and has no name-edit field. |
| Counts / skipped entries | Review planned files, directories and bytes, and any skipped entries. Skipped entries are not imported merely because other items succeed. |
| Import preview | Shows the source, planned counts and size. On mobile, expand the path preview; it may not show every path. |
| Large import warning | Review the planned size and any additional confirmation before importing. |
| Too-large state | Select a smaller source or split the import if the app reports that it is too large. |
| Import / Cancel | Confirms publication or abandons the preview. Mobile Cancel clears the plan; Back checks an unfinished plan. Busy import disables conflicting actions/leaving. |
| Completed / failure | Mobile returns to the prior view after confirmed success, or shows the failure/recovery state. It has no per-entry failure/retry list for folder import. |

## Conditions and recovery

Imports create a destination folder; an existing conflicting name is not silently replaced. Mobile can change the planned root name. On desktop, choose another destination or rename the source before selecting it again if the name conflicts.

Review the planned file and folder counts and any skipped entries. Links or unsupported/unreadable entries may be skipped. A folder cannot be copied into itself or a destination inside the source.

After a failure, inspect the destination and any recovery-required state before starting another import. Folder import reports one operation result, not a list of independently retryable files. Pending recovery needs review; repeatedly selecting the entire folder does not resolve an uncertain result.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-folder.md) · [Import individual files](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-files.md) · [Browse files](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/browse-files.md) · [Review pending changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md)

Reviewed: 2026-10-23. UI labels use the English app language.
