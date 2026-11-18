# Create Gear from Memories and Toolboxes

Create a private Gear containing the Memories, Toolboxes and values a DingDong should use. Equip it separately after creation.

## Start here

**Desktop:** Management → Gear → Add, or Create New Gear in an empty collection.

**Mobile:** Shortcuts → DingDong → Gear → Create.

Use a normal signed-in account. Creation is unavailable in agent sign-in and mobile preview.

## Create manually on desktop

1. Choose Set up manually. Enter a nonblank Gear Name of at most 40 characters and choose System or Pure as the DingDong Type. There is no preselected type.
2. In Select Memory, check compatible Memories. You can leave optional Memories unselected. If no suitable Memory exists, use Create memory, finish that separate dialog and select it after returning.
3. In Select Toolbox, choose the compatible capabilities. KnowledgeBox Use is selected where compatible and cannot be unchecked. System adds its required mission Memory and Toolboxes.
4. Continue with Next. Each selected Memory with variables gets a settings step. Defaults are filled where available, but every variable needs a nonblank value.
5. Complete the offered Toolbox steps. Private MCP steps hold unsaved connection values and this device's credential draft; built-in steps hold their capability settings. See the related guides for device, Browser and permission controls.
6. Review Final Confirmation → Create. If private MCP setup is requested, complete it for the created Gear and check the result.

Previous retains the selected items' drafts. On Basic Info it returns to the method cards. Changing type removes incompatible attachments and their values; deselecting an attachment drops its configuration. Closing an unsent desktop form discards it without a separate confirmation. Navigation and Close are disabled while submitting.

## Create manually on mobile

1. Open Create (+) above the Gear collection. Enter Name, at most 40 characters. Compatible DingDong type defaults to Pure; System is also available.
2. Select Memories to use. Details load before an item is selected; incompatible selections or failed loads are rejected. If the catalog fails, use Retry. If the loaded list has no owned Memories, Create Memory opens a child form and retains this Gear draft; select the result after returning.
3. Fill every selected Memory's Template values. Reset to default copies its definition default; a blank default still needs a value.
4. Choose Toolboxes to use and complete the inline settings. Deselecting drops that attachment's draft. Changing type removes incompatible selections; System retains its required components.
5. Choose Create. A verified success without private MCP attachments normally opens the saved Gear's detail. MCP attachments lead to the follow-up setup screen described below.

Back with changes asks whether to discard them. Submission and child-creation preparation block departure. A Browser created from this form is saved separately; check its selection in the Gear as well.

## Use conversation assistance

On desktop, choose Create through conversation on the method cards. On mobile, use Create Gear with System DingDong → Start conversation inside the form. Cobell opens a System DingDong conversation to continue the request. Starting or opening this thread is not confirmation that the Gear exists. Inspect the conversation's result and the Gear collection. On mobile, a command-failed notice means the AI command was not accepted even when the thread opens.

## Finish private MCP setup on the same Gear

During creation, select the current device to enter its local Authentication fields and review them after changing device selections. Browser sign-in and connection checks are available in the saved connection editor. Enter credentials separately on each execution device.

If MCP authentication setup fails, the Gear may already exist. Check the result and finish setup on that Gear:

- **Desktop:** If Final Confirmation says the Gear was created but MCP setup is incomplete, use Retry on that Gear. Closing the flow leaves the created Gear saved.
- **Mobile:** Use the follow-up screen to finish setup. Select a Toolbox to inspect its connection and save current values, or use Retry when offered. Close opens the existing Gear even if some setup remains.

Retry continues setup on the same Gear; it does not create another Gear. If connection settings need changing, open the saved Gear's Toolbox editor. Enter missing credentials on each execution device instead of creating a replacement Gear.

## Completion, limits and recovery

To find a newly created System Gear on desktop, select Sys in the Gear collection. All hides ordinary private System Gear while retaining the built-in one. Mobile All types includes System Gear. See [collection controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) for sorting, summary rows and refresh.

All Memory variables and supplied setting types must pass validation. Missing execution devices, Browser targets or required MCP values can remain incomplete for later setup. Invalid container-runtime selections still block creation. iOS cannot run stdio even if its configuration is saved.

If mobile says the Gear was created but saved settings are unverified, use **Open created Gear**. Creation has already returned a Gear; the form disables another Create. Review that Gear's saved connections and correct them there.

For other errors where the result is uncertain, inspect the collection before resubmitting. Closing after a request was sent does not cancel its saved result. Creation and credential saving do not verify a working MCP connection: use the saved editor's authentication and Check this device controls on each intended execution device, then equip the Gear to a compatible DingDong or Flow node.

Also find this under: configuration bundle, new Gear, combine prompt and tools.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/gear-create.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md)

[MCP values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Browser access in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md)

Reviewed: 2026-10-23. UI labels use the English app language.
