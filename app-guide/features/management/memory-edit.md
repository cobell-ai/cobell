# Edit, duplicate or delete a Memory

Maintain an existing private Memory and inspect which Gears use it.

Built-in missions use a separate [read-only detail screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/builtin-memory.md).

## Start here

**Desktop:** Management → Memory → select the object. A private card's menu also offers individual deletion.

**Mobile:** Shortcuts → DingDong → Memory → select the object → Overview for maintenance actions, or Edit prompt for content.

## Desktop steps

1. Inspect Usage before changing shared instructions. It lists Gears, DingDongs and room labels; these names are display-only here. Retry a failed usage read.
2. Use the name pencil to rename, or Content → Edit for the prompt and variable cards. Names are trimmed, required and limited to 40 characters.
3. Save the relevant edit. Success exits that edit mode; an error keeps it. Cancel discards it. The detail-header Back action offers Keep editing, Leave without saving or Save and leave if name/prompt changes remain.
4. For a separate copy, use the detail menu → Duplicate. It copies saved content/variables/supported types rather than the current unsaved draft, with a generated name limited to 40 characters. Check the list for the copy.
5. For one deletion, use the card/detail menu → Delete and review the confirmation. Cancel keeps the item. The detail route returns to Management after success.
6. For bulk deletion, use the collection's Edit, select private cards and press Delete (count). This starts without another confirmation. It stops on the first failure and may have deleted earlier items; refresh and review before retrying. Cancel or Escape exits selection when not deleting.

## Mobile steps

1. Inspect Gear in use. Tap a Gear to open it, or an available room row under DingDong usage to open the chat. Retry failed usage reads.
2. In Overview, use Rename for a trimmed name of at most 40 characters; Save/keyboard Done submits and Cancel dismisses. Failure keeps the dialog for correction.
3. Open Edit prompt, edit the content/variables and Save. Success stays in this screen. Dirty Back offers Cancel/Discard. Check saved content reads after uncertainty while retaining edits and does not save again.
4. Use Overview → Duplicate for a copy of the refreshed saved source. Success shows a message. If a named copy could not be confirmed, use the notice's Open to review it before duplicating again.
5. Overview → Delete opens the individual confirmation. For bulk work, return to the collection, use Select or long-press a row and review the selected names. Press Delete selected, then check the count and message before confirming; the dialog does not list every name.
6. Bulk deletion continues after individual failures: successful targets leave selection and failures remain selected. Review the error count before retrying. Cancel selection or its Back action clears selection while no deletion is running.

## Completion, limits and recovery

Built-in System DingDong mission content is read-only. Owned private Memories offer the applicable edit/copy/delete actions. Supported types and prompt size/dates are informational; the detail screen does not edit supported types. Size is UTF-8 bytes, not character count.

Editing a shared Memory can affect multiple Gears. A duplicate is a separate item and does not replace attachments in existing Gears. Deleting has no restore action in these screens. Refresh after an uncertain write or partial bulk failure before repeating it.

Also find this under: edit prompt, copy Memory, delete instructions, Memory usage.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/memory-edit.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Define Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

[Collection controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) · [Memory images](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/object-images.md)

Reviewed: 2026-10-23. UI labels use the English app language.
