# Use typed Toolbox option controls

Enter values when a Gear form displays switches, array previews or date/time buttons for a Toolbox's options.

## Start here

**Desktop:** Management → Gear → Create Gear or Add Toolbox → an option configuration step, when offered. Some compatible Toolbox settings also use these controls.

**Mobile:** Shortcuts → DingDong → Gear → Create Gear, or Connection → Linked toolboxes → a selected entry's configuration, when offered.

Available controls depend on the selected entry. Private MCP Common settings and Authentication use the [MCP text value form](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md).

## Desktop steps

1. Toggle flag options or a boolean value with its switch. Enter string values directly.
2. Enter valid integers or decimal numbers in the matching numeric fields. Check the displayed value before continuing.
3. Enter arrays as comma-separated items, for example `one, two` or `1, 2`. Whitespace is trimmed and empty items are omitted. This field splits on commas and does not decode JSON brackets/quotes or support an escaped comma inside one string item.
4. Check the array preview before continuing. Enter valid numeric items for number arrays. Preview chips are read-only; edit the text to change or remove items.
5. For datetime or utcTimestamp, use the date and time buttons and review the selected value. Cancel leaves the value unchanged.
6. Use Reset to default where offered to write the option's declared default into the draft. In desktop add/create forms, it is disabled when the current value already matches. Complete the enclosing Add, Save or Create action to persist the configuration.

## Mobile steps

1. Toggle flag options with their switches. For a boolean value, choose True or False from its dropdown. Enter string/integer/decimal values in the text field offered.
2. Enter array items separated by commas, or provide a typed JSON array. A string containing a comma needs JSON, for example `["one,two", "three"]`. Blank array input produces an empty array.
3. Check the array count and read-only preview. Correct any numeric or JSON input error before saving.
4. For datetime or utcTimestamp, use the date and time buttons, which display local values. Review the selection before continuing. Cancel leaves the value unchanged.
5. Use the restore icon when the option has a declared default. It copies that default into the draft; it does not remove an override to inherit another value. Finish with the enclosing form's configuration confirmation and Add, Save or Create.

## Use the picker dialogs

In the date calendar, use previous/next month, or open the year selector and choose a year, then a day. The pencil icon switches to text input; follow its displayed date format and correct validation errors. The calendar icon switches back.

In the time picker, choose hours or minutes and tap/drag the clock dial. Choose AM/PM when shown. The keyboard icon opens hour/minute text input; the clock icon returns to the dial. Confirm with OK to update the option draft, or Cancel to keep its previous value. Picker labels and 12/24-hour display follow the app/device locale.

## Completion, limits and recovery

utcTimestamp uses milliseconds since the Unix epoch. The controls display local date/time and a numeric timestamp; check the selected value before saving.

Changing a field updates the open form's draft. These controls have no independent Save action. Use [Gear creation](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) or [Gear attachment editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) for final submission, Back and recovery behavior. A restored default is still a draft until that submission succeeds.

Also find this under: comma array input, array preview, boolean switch, True False dropdown, date picker, timestamp milliseconds, option reset.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/toolbox-option-values.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Private MCP text values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [Gear attachments](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
