# Import files into KnowledgeBox: screen reference

Copy selected files into a local or eligible remote workspace. This is separate from sending chat attachments.

## Open this screen

**Desktop:** Management → Pure → select your DingDong → KnowledgeBox → choose source/destination → Add → Add file.

**Mobile:** Shortcuts → DingDong → select your Pure → Knowledge → Files → enter the destination → Add → Import files.

## Controls

| Control or area | Behavior |
|---|---|
| Add file / Choose files | Opens the system picker. Cancel keeps the existing mobile selection; a new successful selection replaces it. |
| File selection limit | At most 10 per batch. Desktop opens a checkbox selection dialog if more were picked; initially the first 10 are selected. Clear one before choosing another. Confirm requires at least one; Cancel/close abandons selection. Mobile rejects more than 10 and keeps the previous list. |
| Destination | Desktop captures the selected folder, selected file's parent, or root before opening the picker. Mobile shows the target path/root. A remote destination uploads the selected local files to that source device. |
| Selected items and status | Mobile shows each name as waiting, imported or failed, plus completed/total count. Items are status rows, not per-item retry buttons. |
| Import | Desktop begins after picker/limit confirmation. Mobile starts with Import; pressing it again skips successful items and attempts the remaining ones. |
| Back | Mobile checks an unimported selection before leaving. Discard clears the selection; already imported files remain. Leaving is blocked while the batch is busy. |

## Conditions and recovery

Files already imported remain if later items fail or you discard the selection. Existing destination names are rejected rather than overwritten; use another destination or rename the conflicting entry/source before retrying. Choosing files again replaces the mobile batch instead of appending to it.

Picker access, source-file existence, destination permission, storage and the connection affect success. A recovery-required, replaced workspace, lost access or offline failure can stop the remaining batch. Do not infer success for waiting/failed items from another item's completion. There is no separate per-item Retry control on the mobile import page.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-files.md) · [Browse files](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/browse-files.md) · [Import a folder](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-folder.md) · [Workspace setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Review pending changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md)

Reviewed: 2026-10-23. UI labels use the English app language.
