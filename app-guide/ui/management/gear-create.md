# Create Gear from Memories and Toolboxes: screen reference

Create a private Gear with selected Memories, Toolboxes and their values. Creating it does not equip it to a DingDong or Flow node.

## Open this screen

**Desktop:** Management → Gear → Add. An empty collection also offers Create New Gear.

**Mobile:** Shortcuts → DingDong → Gear → Create.

Use a normal signed-in account. Creation is unavailable in agent sign-in and mobile preview.

## Desktop controls

| Control or area | Location and behavior |
|---|---|
| Set up manually | Opens the staged creation form. |
| Create through conversation | Starts System DingDong assistance and opens its chat when the launch succeeds. Opening the conversation does not mean a Gear has been created. |
| Gear Name | Required, trimmed, at most 40 characters; invalid display-name characters are rejected. |
| DingDong Type | Required; initially unselected. Choose System or Pure. Clicking the selected chip clears it. Changing type removes incompatible selections and their values. |
| Select Memory | Compatible Memory checkboxes. Selecting fills available variable defaults; deselecting drops that Memory's configuration. Required System mission Memory cannot be unchecked. |
| Create memory | Offered when there are no Memories or no compatible Memories. Opens Memory creation, then refreshes the list. Select the new Memory after returning. |
| Select Toolbox | Compatible Toolbox checkboxes. KnowledgeBox Use is selected and locked where compatible; System's required Toolboxes are also locked. Deselecting an optional Toolbox drops its connection draft. |
| Template Variable Settings | One step for each selected Memory with variables. Every variable needs a nonblank value before proceeding. |
| Toolbox configuration steps | Offered for selected configurable Toolboxes. Built-in steps edit their permissions/settings; private MCP steps edit an unsaved connection draft. See the linked configuration guides below. |
| Previous / Next | Move through the steps required by the current selections while retaining their drafts. Previous on Basic Info returns to the method cards. |
| Final Confirmation / Create | Reviews the name, type, attachments and values, including MCP setup-needed notices. Create validates the whole form and sends it. |
| Close | Discards an unsent form without a separate unsaved-changes confirmation. Close, Previous, Next and Create are disabled during submission. |
| Retry after an MCP save failure | Continues setup on the Gear that was already created. Closing the flow leaves that Gear saved; do not create another merely to finish authentication. |

The Memory and Toolbox selection steps precede the per-item value/settings steps. Their number changes with the selections. Pure Gear does not require an added Memory; System includes its required components.

## Mobile controls

| Control or area | Location and behavior |
|---|---|
| Create (+) | Above the Gear collection; opens one scrolling form. |
| Name / Compatible DingDong type | Name is required and limited to 40 characters. Type defaults to Pure; System is also available. Changing type removes incompatible attachments and their values. |
| Create Gear with System DingDong → Start conversation | Card inside the form. Opens an assistance thread; a command-failed notice means the AI command was not accepted even if the thread opens. Manual form submission is separate. |
| Memories to use / Toolboxes to use | Checkboxes load each item's details before adding it. Incompatible or failed loads do not add an item. Deselecting removes its values from this draft. |
| Catalog Retry | Appears after the candidate list fails to load. Reloads the list, not a submitted creation request. |
| Create Memory | Shown after a loaded candidate list contains no owned Memories. Opens Memory creation while retaining this Gear form. Select the Memory after returning. |
| Template values / Reset to default | Under each selected Memory. Reset copies its current definition default; all variable values must still be nonblank before Create. |
| Built-in settings / private MCP settings | Inline sections for the selected capabilities. Device, Browser and connection values remain part of the creation draft until submitted. A separately created Browser has its own saved state. |
| Create | Validates and submits the form. Without private MCP attachments, a verified success normally opens the created Gear's detail. |
| Back | Asks to discard a changed form. Submission and child-creation preparation block departure. |
| Open created Gear | Appears when creation returned an allocated Gear but its saved configuration could not be verified. Opens that Gear for review; another Create is disabled. |
| MCP follow-up: Toolbox selector / Retry / Save / Close | Select a Toolbox to inspect its saved connection. Retry continues setup; Save applies current edits. Close opens the existing Gear even if setup remains incomplete. Wait for progress before acting again. |

## MCP draft and creation result

Before Create, select the current device to enter its local Authentication values and review them after changing device selections. Browser sign-in and connection checks are available in the saved connection editor. Finish required values and device choices before using the MCP Toolbox. iOS cannot execute stdio connections.

After an MCP setup failure, check whether the Gear was created. Use Retry or open that Gear's saved connection editor to finish setup. Retry does not create another Gear. Enter local credentials separately on each execution device.

On desktop, completed MCP setup closes the dialog. On mobile, successful setup leaves the follow-up editor open; Close opens the Gear detail. Closing does not delete the Gear or cancel a request already sent. If you leave before setup is complete, reopen the existing Gear's Toolbox settings and enter any missing local credentials there.

## Conditions and results

In the desktop Gear collection, choose Sys to find a private System Gear. All hides it while keeping the built-in System Gear visible. Mobile All types includes System Gear. See [collection controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/collections.md).

Missing device/Browser targets can remain for later setup. Invalid supplied settings, blank Memory variables and invalid container-runtime selections still block submission. A created Gear or successful credential save does not prove its tools can execute. Save any remaining settings, authenticate and check each intended execution device separately.

For a generic failure with an uncertain result, inspect the saved collection and Gear before repeating Create. The explicit mobile Open created Gear notice and the MCP post-creation Retry both refer to an already-created Gear.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md)

[MCP values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Browser access in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md)

Reviewed: 2026-10-23. UI labels use the English app language.
