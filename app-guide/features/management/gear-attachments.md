# Edit Gear attachments and values

Select attachments and set values for one Gear without editing their reusable definitions.

## Start here

**Desktop:** Management → Gear → editable Gear → Memory or Toolbox section.

**Mobile:** Shortcuts → DingDong → Gear → your private Gear → Connection → pencil beside Linked memories or Linked toolboxes.

## Desktop steps

1. Choose Add Memory and select at least one compatible item that is not already attached. Next opens variable steps where needed, then Final Confirmation.
2. Fill every variable with a nonblank value; defaults are prefilled where available. Previous retains the open wizard's draft. Add submits the attachments and values and closes after success.
3. For existing Memory values, use its settings icon → Memory config → Save. This trims and saves this Gear's values. It does not edit the original prompt/defaults or offer a version picker.
4. Drag an attached Memory to change priority. The update is sent immediately. Remove opens a confirmation and immediately sends the confirmed removal; neither action needs a later attachment Save.
5. Use Add Toolbox, complete its offered configuration steps and review Final Confirmation → Add. After attachment, its settings icon opens the appropriate built-in, private MCP or other values editor.
6. Closing an unsent wizard/config draft discards it. Closing after submitting does not cancel the request. On error/uncertain outcome, refresh saved Gear before repeating the operation.

Private Memory and Toolbox attachments have no version selector here. Review their current settings before saving changes.

## Mobile steps

1. Open the Linked memories pencil (Attached memories). Tapping a linked editable Memory opens the same editor at that selection, rather than its original definition.
2. Add available Memories, fill Template values and drag selected rows into priority order. Reset to default replaces that field with its definition default; an empty default still fails the required-value check. Required System mission Memory stays first.
3. Use Remove on an unwanted selected Memory and confirm. This changes only the draft. Choose Save to apply selections, values and order; success stays in the editor.
4. Return to Connection → Linked toolboxes pencil (Gear toolboxes). Select available compatible items. Unchecking a selected Toolbox asks for removal confirmation, then changes the draft. Toolbox order is not saved as priority.
5. Save private Toolbox attachment changes before opening their settings. On Connection, the name opens the definition and the settings gear opens this Gear's connection configuration. Built-in permissions and Priority devices are separate sections.
6. Review the selected Toolboxes and their connection settings before saving.
7. Discard changes restores the saved baseline. Back with a dirty draft asks to keep editing or discard; saving/configuration preparation blocks departure.
8. After a failed write, use Check saved connections. It reads the saved state while retaining differing edits and does not send the write again. Review the result before saving or discarding the retained draft. Retry on an initial load error reloads the editor.

For an entry that offers switches, array previews or date/time buttons, follow [Toolbox option controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-option-values.md). Private MCP inputs use their separate text value form.

## System Gear and the built-in default

Every System-type Gear keeps the built-in System mission Memory first and enables Internet Use, Cobell Controller and Notification Sender. These three Toolboxes have no settings or removal action in Gear. The mission cannot be removed; on desktop its visible Remove action does nothing and dragging it cannot change its saved first position. System Gear has no own KnowledgeBox or KnowledgeBox Use settings.

The built-in System Gear is not editable. On desktop, Add Memory, Add Toolbox and Memory drag controls can still appear, but submitting a change fails and does not save that configuration. Create a private System-type Gear instead; compatible extra Memories and Toolboxes can be added alongside its required components.

On mobile, the built-in Gear's Connection has no attachment pencils. Required Toolboxes appear as locked rows; tapping System mission Memory opens its read-only catalog page. Overview → Duplicate can create a private System Gear, which has attachment pencils and settings for optional built-ins. Its required Toolbox cards still have no settings action. Creating or copying Gear does not equip it: mobile Cobelly keeps the built-in default and has no Gear selection action, while desktop supports choosing another System Gear in DingDong settings.

## Completion, limits and recovery

Removing an attachment leaves the original Memory/Toolbox definition. Private mobile edits require a normal signed-in owner. Unavailable/incompatible entries cannot be newly selected; retained unavailable selections can be reviewed/removed. Required System components are protected; desktop also blocks attachment removal of KnowledgeBox Use.

An attachment saved to Gear is separate from equipping that Gear to a DingDong. It also does not verify device permissions, MCP authentication or runtime readiness.

Also find this under: attach Memory, remove Toolbox, per-Gear variables, connections.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/gear-attachments.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Configure KnowledgeBox Use permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

[Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Choose KnowledgeBox devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md)

Reviewed: 2026-10-23. UI labels use the English app language.
