# Edit, duplicate or delete a Memory: screen reference

Maintain an existing private Memory and inspect which Gears use it.

Built-in missions use a separate [read-only detail screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/builtin-memory.md).

## Open this screen

**Desktop:** Management → Memory → select the object. Individual deletion is also in a private Memory card's menu.

**Mobile:** Shortcuts → DingDong → Memory → select the object → Overview for maintenance actions, or Edit prompt for content.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop name pencil / Save / Cancel | Edits a trimmed, required name of at most 40 characters. Save awaits the update; failure keeps editing. Cancel restores the saved name. |
| Desktop Content → Edit / Save / Cancel | Opens the plain prompt and variable cards. Save awaits the update and leaves edit mode after success; failure keeps it. Cancel discards this draft. |
| Desktop detail menu / mobile Overview → Lock DingDong editing | Blocks self-edits to this Private Memory across all Gears. Use the desktop Unlock DingDong editing action or turn the mobile switch off to unlock. [Memory self-editing and locks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/memory-self-edit.md) |
| Desktop detail-header Back | With changed name/prompt, offers Keep editing, Leave without saving or Save and leave before returning to Management. Save failure keeps the editor. This describes the header action, not every possible navigation route. |
| Mobile Overview → Rename | Opens a name dialog with the same 40-character display-label limit. Save or keyboard Done submits; success closes it. Cancel leaves the saved name. Buttons/field are blocked while sending; failure remains in the dialog. |
| Mobile Edit prompt / Template variables | Edits prompt and variable definitions together. Template variables directly on detail is the saved read-only list; inside Edit prompt it opens draft fields. |
| Mobile prompt Save / Back | Success shows a message and stays in the prompt screen. Dirty Back offers Cancel/Discard; saving blocks departure. |
| Mobile Check saved content / Retry | Reads saved content while keeping the draft after uncertainty, without saving again; Retry handles a failed initial read. |
| Supported types / data size / dates | Read-only information. Size measures prompt UTF-8 bytes rather than character count. Supported types has no detail-screen edit control. |
| Desktop Usage | Shows referencing Gears, DingDongs and room labels. These displayed names are not navigation buttons in this section. A per-Gear load failure offers Retry. |
| Mobile Gear in use | Gear rows open their details. Loaded DingDong usage includes room rows that open the chat. Usage failures offer Retry; a failed read is not evidence that nothing uses the Memory. |
| Desktop detail menu → Duplicate | Creates a separate private copy of saved name/content/variables/supported types; it does not use the unsaved prompt draft. The generated copy name is limited to 40 characters. |
| Mobile Overview → Duplicate | Refreshes the saved source, then creates a separate copy. Success shows a message without automatically opening the copy. An incomplete-copy notice offers Open for the named allocated item. |
| Desktop card/detail menu → Delete | Opens Cancel/Delete confirmation for one private Memory. Success removes it; detail deletion returns to Management. Failure reports an error. |
| Desktop Memory list → Edit → Delete (count) | Select private cards by row/checkbox. Delete starts immediately, with no additional confirmation. Requests run sequentially and stop at the first failure, so earlier items may already be deleted. |
| Mobile Select / long-press → Delete selected | Starts collection selection; rows/checkboxes toggle targets. Review the selected rows before opening the confirmation, which shows the count and deletion message. Successful rows are removed from selection; failures remain selected while other requests continue. |
| Cancel selection / desktop Escape | Leaves selection mode and clears the selection without deleting. Busy deletion blocks cancellation. |
| Private Memory image actions | Desktop avatar/menu or mobile Manage image opens the separate image workflow; desktop list avatar actions are disabled in selection mode. See the image guide. |

## Conditions and results

Only eligible owned private Memories offer mutation actions. Built-in System DingDong mission content is read-only. Editing a shared Memory can affect multiple Gears; inspect usage before changing or deleting it. Duplicating does not attach or substitute the copy in existing Gears.

After an uncertain operation, refresh the collection or inspect the named copy before retrying. Desktop bulk deletion is not atomic: check the current list after a failure. Mobile bulk failures can stay selected for review/retry. These screens provide no restore action for deleted Memories.

Name validation rejects double quotes, forward/back slashes, angle brackets, vertical bars and control characters. Use the variable guide for prompt token validation, default/description edits and deleting repeated tokens.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Define Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

[Collection controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) · [Memory images](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/object-images.md)

Reviewed: 2026-10-23. UI labels use the English app language.
