# Rename, delete or describe knowledge entries: screen reference

Change a file/folder identity or its saved description and summary.

## Open this screen

**Desktop:** KnowledgeBox tree entry → Menu; metadata fields appear in the selected resource’s header/content panel.

**Mobile:** Knowledge file info/details → Rename, metadata edit or delete action.

## Controls

| Control or area | Location and behavior |
|---|---|
| Rename / F2 | Desktop row menu or F2 on a selected tree item starts inline renaming. The stem is initially selected for an ordinary file, leaving its extension outside that initial selection. Mobile opens a separate Rename form from the info sheet. |
| Inline Enter / confirm / Esc / cancel | Desktop Enter/checkmark confirms; Esc/cross cancels. An empty submission cancels. A nonempty edit is not saved merely by losing focus. |
| Description / Summary | Separate saved metadata fields: description up to 500 characters, summary up to 4,000. Editing these does not rewrite file contents. |
| Metadata expand/collapse / Save | Desktop shows/hides its metadata form and saves explicitly. Saving and access state can disable the form/actions. |
| Mobile info/details | Shows selectable path, modified date/time, file size and available description/summary. Close leaves the sheet. A folder also offers Add within it. |
| Edit description and summary / Save | Mobile opens the metadata form. Editing is unavailable while required local metadata is loading or failed; Save validates the fields. |
| Mobile Back | Checks changed name/metadata drafts before leaving; keep editing or discard. Saving disables leaving and conflicting actions. |
| Delete File / Delete Folder / Delete entry | Confirms removal from the owning device, including saved description/summary. A folder includes its files. Mobile shows the relative path and warns that deletion cannot be undone; its confirmation/cancel are disabled while sending. Cancel before confirmation keeps the entry. |
| Show in file explorer / Open with default app | Desktop local-entry controls reveal the path or open a local file externally. Remote entries do not offer local external opening. |

## Conditions and results

Names are portable single-entry filenames with a maximum of 255 UTF-8 bytes including extension. Invalid/reserved names and existing destinations are rejected. Renaming changes identity/path; description and summary are metadata. A DingDong can also maintain these fields.

Check the source device and path before deleting. A changed/retired workspace disables the old form; return to the file list and refresh before acting on the current entry. After an uncertain mutation or recovery-required message, inspect the destination and pending changes before repeating Save/Delete. Successful edits do not imply a following list refresh succeeded.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/entry-actions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
