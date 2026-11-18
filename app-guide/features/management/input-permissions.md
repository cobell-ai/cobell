# Configure Mouse Use and Keyboard Use

Select permitted input targets, action delay and clipboard behavior.

## Start here

**Desktop:** Top navigation → Management → Gear → select the Gear → Mouse Use or Keyboard Use configuration.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → the selected input Toolbox → Built-in configuration.

## Desktop steps

1. Open the Gear’s Mouse Use configuration and choose target devices and delay.
2. Open Keyboard Use and choose target devices, delay and clipboard permission.
3. Save both configurations.
4. Verify the selected desktop supports the requested operation.

## Mobile steps

1. Open the Gear’s Mouse Use or Keyboard Use configuration.
2. Enable the selected Toolbox, choose supported desktop targets and set numeric action delay. Clear obsolete unknown-device selections if shown.
3. For Keyboard Use, set clipboard permission deliberately.
4. Save; use a supported desktop target because this mobile app does not execute these hardware actions. A failed load offers Retry. After an uncertain save, use Check saved settings before retrying a change.
5. Repeat for the other input Toolbox if needed; the settings are separate. Back checks unsaved mobile changes before leaving.

## Action delay and clipboard

Action delay uses whole milliseconds; enter 2500, for example, without commas or units. The standard delay is 2,500 ms (2.5 seconds); 0 removes this added delay. Check the saved value after changing it.

- Mouse Use applies the configured delay to mouse input actions.
- Keyboard Use applies the configured delay to keyboard input actions.
- Mouse and Keyboard retain independent delay values and target-device lists.

Enter an explicit nonnegative whole number and correct any field error before saving.

Keyboard clipboard permission is off by default. Enabling it allows clipboard-based paste and copy/cut/paste shortcuts, which can read or change clipboard contents. Pasting can temporarily replace clipboard contents; restoring previous contents and all formats is not guaranteed. Allow clipboard access only when needed.

## Save and check the result

After saving on desktop, reopen the Gear to confirm the result. Cancel or Close before Save abandons the draft.

Mobile Save waits for the update and saved-value check, then leaves on success. Check saved settings after a failed/uncertain save reads the result without resending the update. It can retain differing edits; review those before saving again or using Back → discard changes. Mouse and Keyboard are saved separately.

## Completion, limits and recovery

Clipboard permission and action delay are per-Gear settings. Current mobile hardware execution remains unavailable even after Booster pairing. Mouse/keyboard control requires an eligible connected target, not merely a saved configuration.

Also find this under: mouse automation, keyboard, hotkeys, paste, action delay.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/input-permissions.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
