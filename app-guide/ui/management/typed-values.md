# Enter typed Toolbox values in Gear: screen reference

Enter actual values for the inputs defined by a private MCP Toolbox.

## Open this screen

**Desktop:** Management → Gear → attached private Toolbox settings → Common settings / Authentication.

**Mobile:** Shortcuts → DingDong → Gear → your Gear → Connection → linked private Toolbox settings gear.

## Controls

| Control or area | Location and behavior |
|---|---|
| Common settings → Settings for | Choose Common settings or one selected execution device. A device override replaces individual common values. Selecting the scope does not itself change values. |
| Typed value field | Uses a text field for every MCP type. A label may differ from its stable key; * marks a required definition. Description and inherited/default hint are displayed when present. |
| String / datetime | Plain text without JSON quotes. datetime must parse as a date/time, for example 2026-01-01T00:00:00Z. |
| integer / utcTimestamp | JSON integer text, such as 0. |
| double64 / boolean | JSON number or lowercase true/false. A number must be finite. There is no MCP boolean selector/flag switch here. |
| stringArray / intArray / doubleArray | JSON arrays such as ["one", "two"], [1, 2] or [1.0, 2.0]. This editor has no array chips, comma parser or checkmark parse button. |
| Authentication | Secret inputs for this local device, separate from the public scope selector. Show value/Hide value changes masking; it does not save or transfer a credential to another device. |
| Reset value | Removes the explicit value from the current draft. A device field then inherits common/default; a common field can use its definition default. Clearing a string instead saves an explicit empty string. |
| Obsolete input delete icon | Removes a stored value whose key is no longer defined. Review common, per-device and local-secret values when a definition changes. |
| Save | Validates supplied values, including overrides hidden under other device choices, then saves configuration and local secrets. Missing required inputs can be saved as incomplete; successful Save is not execution readiness. |

## Conditions and results

0, false, an empty string and an unset value differ. Strings/datetime are plain text; other types must be valid JSON of the declared type. There are no date/time picker controls in this private MCP value editor. Legacy option editors for other Toolbox types should not be used as instructions for this form.

Save before connection checks/sign-in. On type/save failure, correct the retained draft; stale settings require Refresh and another check. Refresh with unsaved changes asks to discard them. Definition edits and Gear actual values are separate saves.

## Related guides

[Use typed Toolbox option controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/toolbox-option-values.md) covers the conditional switch, array preview and date/time forms.

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Define private MCP inputs and bindings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
