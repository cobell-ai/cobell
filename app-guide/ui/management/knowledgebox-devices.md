# Set KnowledgeBox device priority: screen reference

Select execution targets and order the preferences used when choosing an available device.

## Open this screen

**Desktop:** Management → Gear → select the Gear → KnowledgeBox Use settings → Tool execution/target devices.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → Priority devices → reorder icon. This is separate from KnowledgeBox Use policy settings.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop device row / checkbox | Selects or deselects a registered device. Newly selected known devices append to the selected order, ahead of retained unknown IDs. |
| Desktop priority number | Shows the selected order, starting at 1. Selected known devices appear above unselected devices. |
| Desktop drag handle | Offered only for selected known devices. Drag to reorder the selected set; tapping the handle does not toggle selection. |
| Desktop OS / login-status badge | Identifies the listed device; a registered row alone is not proof that its tools are usable now. |
| Mobile Available checkbox | Adds a selectable target. New selection requires an available device and a current runtime advertising at least one KnowledgeBox capability. |
| Mobile selected device / capability summary | Shows order, device and available file/shell/container capabilities. Unavailable selections remain visible rather than being silently deleted. |
| Mobile Up / Down / drag handle | Reorders selected available devices. Up/Down are disabled at the applicable boundary. Unavailable selections cannot be reordered through these controls. |
| Mobile Remove | Removes a selection, including an unavailable/stale one, without unregistering the device or deleting its files. |
| Mobile Save / Discard changes | Saves a changed order or resets the draft to the saved selection. Disabled while saving or with no changes. |
| Mobile Back | A dirty draft asks to keep editing or discard. Saving blocks departure. |
| Mobile Retry / Check saved connections | Retries a failed load, or reads saved selections after uncertainty while retaining the current draft. Checking does not save again. |
| Desktop Save / Cancel | Saves through the containing KnowledgeBox policy dialog, or discards its unsaved draft. |

## Conditions and results

Priority is used to prefer an available selected device with the needed tool when a target is not otherwise specified. It does not copy a KnowledgeBox folder, grant device permission or make every selected device support every tool. Check the actual source and workspace for file operations.

Desktop preserves previously selected IDs that are absent from its current device list when toggling/reordering known devices; those IDs are not silently removed. Mobile retains unavailable selections until removed and places them after known selections when editing order.

Android can provide file tools and available shell commands; iOS provides file tools; containers require a supported desktop. Empty selection can be saved for later setup, but execution still needs a target. If saving is uncertain, inspect the saved list before repeating it.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Device access](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

Reviewed: 2026-10-23. UI labels use the English app language.
