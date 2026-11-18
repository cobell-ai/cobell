# Edit Gear attachments and values: screen reference

Select attachments, set this Gear's Memory values and open its Toolbox configuration.

## Open this screen

**Desktop:** Management → Gear → select an editable Gear → Memory or Toolbox section.

**Mobile:** Shortcuts → DingDong → Gear → select your private Gear → Connection. Use the pencil beside Linked memories or Linked toolboxes. Tapping an editable linked Memory also opens Attached memories at that selection.

## Desktop controls

| Control or area | Location and behavior |
|---|---|
| Add Memory → selection | Lists compatible Memories that are not already attached. Select at least one to continue with Next. Deselecting also clears that item's new configuration draft. |
| Template Variable Settings | Adds a step for each selected Memory that has variables. Defaults are filled where available; every variable needs a nonblank value before Next. Previous retains the open wizard's selection and values. |
| Final Confirmation → Add | Reviews the selected Memories, then submits their attachment/configuration together. Success closes; failure shows an error and keeps the dialog. |
| Attached Memory settings icon | Offered when variables exist. Memory config edits this Gear's values, not the Memory definition. Save requires nonblank values, trims them and closes after success. Cancel/close dismisses the open draft. |
| Memory drag handle | Reorders attached Memories and sends the update immediately. There is no separate attachment Save button afterward. |
| Add Toolbox | Same selection/configuration/Final Confirmation wizard. Lists compatible items not already attached/enabled. Built-in configuration, options and headers add steps where applicable. Complete the requested settings before Next/Add. |
| Attached Toolbox settings | Built-in items open their permission/configuration dialog; private MCP items open their Gear connection editor. Other configured Toolboxes use their values editor. |
| Remove icon | Opens Cancel/Remove confirmation. Confirming immediately submits removal from this Gear, including its stored attachment configuration. It does not delete the Memory/Toolbox definition. |
| Wizard Previous / close | Previous keeps the open draft. Closing does not send an unsent draft or cancel a request already sent; refresh saved Gear after an uncertain result. |
| System mission Remove / drag | The required built-in mission cannot be removed. A visible Remove action does nothing; dragging cannot change its saved first position. |
| Required System Toolbox cards | Internet Use, Cobell Controller and Notification Sender have neither settings nor removal actions. This applies to private System Gear too. |

Private attachments have no version selector here. Use the existing Memory configuration dialog to edit its values.

## Mobile controls

| Control or area | Location and behavior |
|---|---|
| Linked memories pencil / linked Memory | Opens Attached memories. Selected rows are numbered; Available to attach contains remaining definitions with their availability. Choosing an available item adds it to the draft and fills its variable defaults. |
| Template values / Reset to default | Edits per-Gear strings. The restore icon copies the definition's default into that field, including an empty default. All defined variables must still have nonblank values to Save. |
| Selected Memory drag handle | Reorders the draft's priority. Required System mission Memory stays first and has no remove/drag control. |
| Selected Memory Remove | Cancel/Remove confirmation removes the attachment only from the draft. Save is still required. |
| Linked toolboxes pencil | Opens Gear toolboxes for private selections. Built-in Toolbox settings have their own section on Connection. Toolbox list order is not stored as execution priority. |
| Toolbox checkbox | Adds an available compatible item. Unchecking a selected item asks for confirmation and then changes the draft. Removing/reselecting also loses that selection's unsaved configuration. |
| Toolbox configuration | For an already saved private attachment, available when selection edits are saved. Save attachment changes first, then open its settings from Connection. |
| Save / Discard changes | Available for a changed draft while idle. Save waits for the result and stays in the attachment editor. Discard changes restores its saved baseline. |
| Back | With changes, asks to keep editing or discard. Saving blocks departure; Toolbox configuration preparation also blocks it. |
| Retry / Check saved connections | Retry reloads a failed initial read. After a failed write, Check saved connections reads saved state without submitting another save and retains differing selections/edits. Review the refreshed result before Save or Discard changes. |
| Linked Toolbox name / settings gear | The name opens its definition; the settings gear edits this Gear's values. Linked Memory names instead open this Gear's attachment editor. |
| Built-in Toolbox / Priority devices | Separate Connection entries for built-in permissions and KnowledgeBox device order; these are not private Toolbox selection checkboxes. |
| System mission Memory row | Opens the read-only built-in mission page, including from private System Gear. It does not open the ordinary attachment values editor. |
| Required System Toolbox cards | Internet Use, Cobell Controller and Notification Sender are required. Built-in Gear shows locked rows; private System Gear shows required cards without a settings action. |
| Built-in System Gear Connection | Has no attachment pencils. Overview → Duplicate creates a separate private Gear; it does not change Cobelly's fixed built-in Gear selection on mobile. |

## Conditions and results

Conditional option forms with switches, array previews or date/time buttons are described in [Toolbox option controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/toolbox-option-values.md).

Private mobile edits require a normal signed-in owner; preview/agent-login/read-only entries do not provide these mutations. Unavailable or incompatible entries cannot be newly selected. Existing unavailable selections remain visible for review/removal. System Gear has no own KnowledgeBox or KnowledgeBox Use settings. Desktop also prevents removing KnowledgeBox Use through the attachment Remove action where that capability is supported.

The built-in System Gear cannot save configuration changes. Desktop can still show Add Memory, Add Toolbox and Memory drag controls there; submitting fails. Use a private System-type Gear for compatible extra attachments. Desktop can equip another System Gear through DingDong settings; mobile Cobelly's Gear selector is disabled and remains on its built-in default.

Attachment values affect this Gear; editing the original Memory/Toolbox is a separate action. Attaching does not equip a DingDong or establish that every device/runtime can execute its tools. Review saved connections before repeating an uncertain write.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Configure KnowledgeBox Use permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

[Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Choose KnowledgeBox devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md)

Reviewed: 2026-10-23. UI labels use the English app language.
