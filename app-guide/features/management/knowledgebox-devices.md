# Set KnowledgeBox device priority

Choose targets for a Gear and put preferred devices first without moving their files.

## Start here

**Desktop:** Management → Gear → select the Gear → KnowledgeBox Use settings → Tool execution/target devices.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → Priority devices → reorder icon.

## Desktop steps

1. Open the KnowledgeBox policy's device list. Check the device name, OS and login status.
2. Select rows or checkboxes. Selected known devices move above unselected ones, and a newly selected device goes after the previously selected known devices.
3. Drag a selected device's handle to set its priority. Number 1 is first. Unselected rows have no reorder handle.
4. Save through the containing policy dialog. Cancel/close before saving keeps the prior policy.
5. Check that the intended DingDong has an accessible workspace on the device. Selection does not create or copy that folder.

## Mobile steps

1. Open Priority devices separately from the Gear's KnowledgeBox policy screen.
2. Select an Available device that advertises current KnowledgeBox tools. Review its file/shell/container capability summary.
3. Use drag handles or Up/Down to order selected available devices. Remove can also clear a stale/unavailable selection; it does not unregister the device.
4. Save the changed order. Discard changes resets the draft; Back with a dirty draft asks whether to keep editing or discard. Sending blocks departure and conflicting actions.
5. After an uncertain save, use Check saved connections. This reads the saved list while keeping the draft and does not send another save. Retry handles a failed initial load.

## Completion, limits and recovery

Automatic selection prefers an available target with the needed capability, in priority order, when a target is not otherwise clear. It does not grant device access or make files available from a different workspace. Android supports file tools and available shell commands; iOS file tools; containers need a supported desktop.

Desktop toggling/reordering preserves saved device IDs missing from the current list. Mobile keeps unavailable selections visible and allows removal, while reordering applies to available selections. Empty selection can be saved, but a target is required for execution.

Also find this under: target device, execution priority, ordered devices, unavailable device.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/knowledgebox-devices.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md)

Reviewed: 2026-10-23. UI labels use the English app language.
