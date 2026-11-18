# Use typed Toolbox option controls: screen reference

Controls shown conditionally in Gear option configuration forms. Available forms depend on the selected Toolbox.

## Open this form

**Desktop:** Management → Gear → Create Gear or Add Toolbox → option configuration step when offered; compatible existing Toolbox settings can also show it.

**Mobile:** Shortcuts → DingDong → Gear → Create Gear, or Connection → Linked toolboxes → selected entry configuration when offered.

Private MCP Common settings and Authentication use their separate text fields. See [MCP typed values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/typed-values.md).

## Desktop controls

| Control | Behavior |
|---|---|
| Flag / boolean switch | Changes the option's boolean draft value. A flag is a separate on/off option rather than a string to type. |
| String input | Updates the string draft as typed. |
| Integer input | Enter a whole number and check the displayed value before continuing. |
| Decimal input | Enter a valid decimal number and check the displayed value before continuing. |
| Array input | Enter comma-separated items in the requested type and check the preview. String brackets and quotes are treated as text; do not add JSON syntax in this desktop field. |
| Array preview count/chips | Displays the current parsed draft; chips have no delete action. Edit the text to remove an item. There is no parse/checkmark button in this field. |
| Date button | Opens the date picker. Confirm selects the date; Cancel makes no change. Review the displayed date/time. |
| Time button | Opens the time picker. Confirm selects the time; Cancel makes no change. Review the displayed date/time. |
| Timestamp / formatted date | Read-only preview. utcTimestamp stores epoch milliseconds, while the picker uses local date/time. |
| Reset to default, when offered | Copies a declared default into the draft. Disabled when already equal in desktop add/create forms. It does not save the enclosing Gear. |

## Mobile controls

| Control | Behavior |
|---|---|
| Flag switch / boolean dropdown | Flag options use switches; a typed boolean value uses True/False choices. |
| String / integer / decimal field | Edits the text input for the enclosing form's type validation. A numeric keyboard does not guarantee that the value is valid. |
| Array field | Accepts comma-separated items or a typed JSON array. Blank input produces `[]`. Use JSON for a string containing a comma. Wrong element types, invalid numeric items and invalid JSON stay invalid for form validation. |
| Array count/chips | Shown for a valid, nonempty array. Read-only; change/remove items in the text. Valid JSON may display as comma-separated text if no item itself contains a comma. |
| Date / time buttons | Display local values. Select the intended date and time and review the result. Cancel makes no change. |
| utcTimestamp number | Read-only epoch milliseconds below the buttons when a value is present. |
| Restore icon, when offered | Copies the declared default into the draft. No default means no active restore action. The updated field still needs the enclosing form's submission. |

## Picker dialog controls on both platforms

| Control | Behavior |
|---|---|
| Calendar previous / next month | Moves the visible month within the allowed dates. Choose a day from the grid. |
| Calendar year selector | Opens the year list. Select a year, then choose the day. |
| Date pencil / calendar icon | Switches between typed date input and calendar selection. Follow the shown date format; invalid/out-of-range input needs correction before confirmation. |
| Time hours / minutes / clock dial | Chooses the active part and selects its value by tapping or dragging the dial. |
| AM / PM, when shown | Chooses the half-day in a 12-hour display. |
| Keyboard / clock icon | Switches between hour/minute text fields and the clock dial. |
| OK / Cancel | OK applies a valid picker selection to the option draft. Cancel leaves its previous value. Final Gear submission is still separate. Labels and 12/24-hour display follow the app/device locale. |

## Conditions and results

These controls edit a draft; use the containing form's Save to apply it. After changing accounts, reopen the current form before editing.

For final Add/Save/Create, Back and uncertain-write recovery, follow the enclosing [Gear attachments](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/gear-attachments.md) or [Create Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/gear-create.md) guide.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-option-values.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
