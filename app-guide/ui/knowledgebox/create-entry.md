# Create a file, document or folder: screen reference

Create knowledge content directly on the selected workspace device.

## Open this screen

**Desktop:** Management → Pure → select your DingDong → KnowledgeBox → Add → New folder, Write directly or Write directly (web-only).

**Mobile:** Shortcuts → DingDong → select your Pure → Knowledge → Files → Add → New file or folder.

## Controls

| Control or area | Location and behavior |
|---|---|
| New folder / Folder | Creates a directory below the selected/current destination. |
| Write directly / Text file | Creates a file; no text-file extension is appended automatically. Use the intended extension, such as `.txt`. |
| Write directly (web-only) / Document | Creates a `.ddjson` rich document; the extension is appended if absent. Desktop shows it as an inline suffix. |
| Type | Mobile selector offers Text file, Document or Folder; initial choice is Text file. |
| Name / inline file name | Enter one portable filename, not a path. The complete name including extension must fit 255 UTF-8 bytes. |
| Enter / Confirm | Desktop submits the inline name. Empty submission cancels. Invalid names show feedback and keep the edit. |
| Add / keyboard Done | Mobile creates the chosen type. Successful files/documents open their content screen; folders return to the previous view. |
| Cancel / Esc | Desktop cancels the inline edit. Losing focus only cancels an empty name; it does not save a nonempty draft. |
| Back | Mobile checks an entered unsaved name before leaving. Keep editing or discard it; creation blocks leaving while busy. |

## Conditions and results

Names must be valid portable single-entry names without path separators, a trailing period or reserved names such as `CON`. App-reserved paths are also rejected. The 255-byte limit includes the extension, so non-ASCII characters can reach it before the character counter.

Desktop new-file/folder creation adds a numbered suffix for a duplicate already known in its sibling list, such as `notes (1).txt`; check the resulting name. Mobile rejects an existing destination. Neither replaces an existing entry. A collision not yet reflected in the desktop list can still fail and require a refreshed list/different name.

Desktop uses the selected directory, a selected file's parent or the root with no selection. Mobile uses the displayed destination. A saved configuration, unavailable source or changed workspace is not a writable target. If recovery is required, inspect pending changes before repeating creation. Creating a missing app folder is a separate operation and does not recover deleted files.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/create-entry.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
