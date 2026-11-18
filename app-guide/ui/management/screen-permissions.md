# Configure Screen Use: screen reference

Select eligible devices and bound screen-inspection results.

## Open this screen

**Desktop:** Top navigation → Management → Gear → select the Gear → Screen Use configuration.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → Screen Use → Built-in configuration.

## Controls

| Control or area | Location and behavior |
|---|---|
| Enabled | Mobile built-in configuration enables or disables this Toolbox in the Gear. |
| Execution/target devices | Select or clear devices that may be inspected. Mobile also displays saved unknown-device references so they can be cleared. |
| Maximum UI nodes / Maximum nodes | Bounds screen structure output. |
| Maximum UI depth / Maximum depth | Bounds hierarchy traversal. |
| Maximum result bytes | Limits screen-structure data size in bytes. |
| Maximum screenshot bytes | Limits screenshot image size in bytes. |
| Screen sharing card | Mobile opens the system-approved sharing setup; saving Gear alone does not begin capture. |
| Save | Desktop starts the update and closes before confirmation. Mobile waits for the saved-value check. |
| Retry / Check saved settings | Mobile recovers a failed initial read or checks the result of an uncertain save. |
| Back | Mobile checks an unsaved draft before leaving; keep editing or discard it. |

## Numeric limits

| Field | Meaning |
|---|---|
| Maximum UI nodes / Maximum nodes | Limits the number of nodes in a screen-structure result. |
| Maximum UI depth / Maximum depth | Limits the depth of a screen-structure result. |
| Maximum result bytes | Limits the size of screen-structure data in bytes. |
| Maximum screenshot bytes | Limits screenshot image size in bytes. |

Enter whole numbers without commas or unit suffixes, using the values and guidance shown in the form.

On desktop, enter the intended number explicitly and check pasted values before saving.

On mobile, enter explicit positive whole numbers for Screen Use. Correct any field error before saving.

## Save and check the result

After saving on desktop, reopen the saved Gear to confirm the result. Cancel or Close before Save discards the draft.

If a mobile save fails or its result is uncertain, use Check saved settings before saving again. Review retained edits before keeping or discarding them.

## Conditions and results

Android and iOS can provide a shared-screen image after the user starts Screen sharing and grants system permission. Mobile does not provide UI structure, other app windows, Mouse Use or Keyboard Use. Screen sharing needs no Booster pairing. Saving this Gear policy does not start capture.

The device list, enabled permission, running session and OS capture consent are separate checks. An unknown/offline saved target does not prove execution readiness.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/screen-permissions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Configure Mouse Use and Keyboard Use](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/input-permissions.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

[Start or stop mobile screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/screen-sharing.md)

Reviewed: 2026-10-23. UI labels use the English app language.
