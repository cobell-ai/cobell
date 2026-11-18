# Enter typed Toolbox values in Gear

Supply values in the private MCP Gear editor using its declared types.

## Start here

**Desktop:** Management → Gear → attached private Toolbox settings → Common settings / Authentication.

**Mobile:** Shortcuts → DingDong → Gear → your Gear → Connection → linked private Toolbox settings gear.

## Steps on desktop and mobile

1. Under Common settings, choose Common settings in Settings for to edit shared non-secret values. Select one execution device to edit only its overrides; inherited values appear as hints.
2. Enter plain text for string/datetime. Enter a JSON integer for integer/utcTimestamp, a finite JSON number for double64, and lowercase true/false for boolean.
3. Enter arrays as JSON, such as ["one", "two"], [1, 2] or [1.0, 2.0], matching the declared element type. All MCP values use text fields; there are no boolean switches, array chips/comma parser or date pickers here.
4. Use Reset value to remove an override and inherit common/default values. Clearing a string is an explicit empty string, not Reset. 0 and false are deliberate values too.
5. Enter secrets in Authentication on the current device. Show value/Hide value changes masking only. Repeat credential setup separately on another device.
6. Remove obsolete saved keys with their delete icons. Save validates provided values in all device overrides as well as the visible fields.
7. Save, then use the connection guide to sign in/check this device. An incomplete set of required inputs can be saved; fill the missing settings before expecting execution to work.

## Completion, limits and recovery

An input label can differ from its key, and * marks a required definition. Definition defaults, common values and device overrides are distinct. A successful settings save does not verify authentication or server readiness.

Invalid input/save failure keeps the draft for correction. Refresh asks to discard unsaved edits; inspect saved settings after a conflict or uncertain result before entering them again.

Also find this under: MCP array JSON, boolean text, inherited value, device override, actual Toolbox values.

## Related guides

[Use typed Toolbox option controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-option-values.md) covers forms that actually show switches, array previews or date/time buttons.

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/typed-values.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Define private MCP inputs and bindings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
