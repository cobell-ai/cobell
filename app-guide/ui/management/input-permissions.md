# Configure Mouse Use and Keyboard Use: screen reference

Select permitted input targets, action delay and clipboard behavior.

## Open this screen

**Desktop:** Top navigation → Management → Gear → select the Gear → Mouse Use or Keyboard Use configuration.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → the selected input Toolbox → Built-in configuration.

## Controls

| Control or area | Location and behavior |
|---|---|
| Enabled | Mobile built-in configuration enables/disables this input Toolbox in the Gear. |
| Execution/target devices | Select or clear supported desktop targets. Mobile can also show saved unknown references, which can be cleared. |
| Action delay (ms/milliseconds) | Delay for input actions, in whole milliseconds. The standard value is 2,500 ms; 0 removes the added delay. |
| Allow clipboard paste / Allow clipboard use | Keyboard clipboard-based paste and common clipboard shortcuts; off by default. |
| Save | Desktop starts an update and closes before confirmation. Mobile waits for the update/read check. |
| Retry / Check saved settings | Mobile retries a failed initial load or reconciles an uncertain save. |
| Back | Mobile checks an unsaved draft before leaving; keep editing or discard it. |

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

## Conditions and results

Clipboard permission and action delay are per-Gear settings. Current mobile hardware execution remains unavailable even after Booster pairing. Mouse/keyboard control requires an eligible connected target, not merely a saved configuration.

Mouse and Keyboard have separate device lists and delay values. Clipboard permission belongs to Keyboard Use. Configure them from mobile for a desktop target; selecting a phone or pairing Booster does not make it an input-execution target. Use the save and recovery controls above before relying on changed values.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/input-permissions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
