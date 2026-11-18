# Configure Screen Use

Select eligible devices and bound screen-inspection results.

## Start here

**Desktop:** Top navigation → Management → Gear → select the Gear → Screen Use configuration.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → Screen Use → Built-in configuration.

## Desktop steps

1. Open the Gear’s Screen Use configuration.
2. Choose the target devices.
3. Set Maximum UI nodes, Maximum UI depth, Maximum result bytes and Maximum screenshot bytes. Use the field descriptions below and the values shown in the form.
4. Save and check that the selected device supports screen inspection.

## Mobile steps

1. Open the Gear’s Screen Use configuration.
2. Enable the Toolbox, select execution devices and set numeric result limits. Clear obsolete unknown-device selections if shown.
3. Save the policy. Correct invalid input if saving is rejected. A failed read offers Retry; an uncertain save offers Check saved settings.
4. For a mobile screen image, tap the Screen sharing card or open More → Screen sharing and grant system capture permission. On iOS, use the broadcast button and Start Broadcast.
5. To leave an unsaved mobile draft, keep editing or confirm discard. Stopping screen sharing is a separate action in its sharing page/system controls.

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

## Completion, limits and recovery

Android and iOS can provide shared-screen images. Mobile does not provide UI structure, other app windows, Mouse Use or Keyboard Use. You perform taps and typing. Screen sharing requires no Booster pairing; saving Gear does not itself begin capture.

Also find this under: screen inspection, screenshot, hierarchy, capture limits.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/screen-permissions.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Configure Mouse Use and Keyboard Use](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/input-permissions.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

[Start or stop mobile screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/screen-sharing.md)

Reviewed: 2026-10-23. UI labels use the English app language.
