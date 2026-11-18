# Create a reusable Memory

Create a private instruction template, then attach it to Gear separately.

## Start here

**Desktop:** Management → Memory → Add, or the empty state's Create Memory.

**Mobile:** Shortcuts → DingDong → Memory → Create (+) above the list.

## Desktop steps

1. Choose Set up manually. Create through conversation instead starts System DingDong assistance; review any resulting Memory separately.
2. Enter a trimmed name of at most 40 characters. All supported types defaults on. Turn All off to choose System or Pure individually. An empty supported-type selection means all types.
3. Choose Next to reach content. Previous returns to name/types and then method selection, retaining the open dialog's draft.
4. Write nonempty Content. Add template variables if needed, then set their defaults/descriptions in the cards below it.
5. Choose Create. Full name/content checks run here. Success closes the dialog; a failure keeps it. Closing a dialog does not cancel a request already sent, so check the list before creating again after uncertainty.
6. Attach the created Memory to the intended Gear and fill required values there.

## Mobile steps

1. Enter Name and nonempty Prompt content in the same form. The name limit is 40 characters; outer whitespace is trimmed.
2. If using variables, type exact `{{{name}}}` tokens or enter a name in the inline variable field and use Add/Enter. It replaces selected content or appends if there is no valid selection. Names are at most 100 characters; empty, duplicate or brace-containing names are rejected.
3. Review detected variable chips. Deleting a chip removes all exact tokens. Set defaults/descriptions after creation through Edit prompt → Template variables.
4. Keep All types or choose Pure. Clearing the individual choice returns to All types.
5. Tap Create and inspect the opened Memory. If the screen reports that the Memory was created but could not be confirmed, use Open on that item before making another.
6. The header conversation icon opens System DingDong assistance. A sent message or opened thread alone is not creation success; review the resulting Memory in the collection.
7. Back with unsaved edits offers keep editing/discard. Sending creation or assistance blocks departure. Attach the completed Memory to Gear separately.

## Completion, limits and recovery

Memory stores reusable instructions rather than chat history. Name validation rejects double quotes, forward/back slashes, angle brackets, vertical bars and control characters. Mobile also checks exact triple-brace syntax and matching unique definitions.

Supported types describe compatibility; they do not unlock hidden features. Empty supported-type lists mean all types. Existing Memory detail displays supported types without an edit control.

Creation does not attach the Memory or supply its required Gear values. After uncertainty, inspect the saved list or the named incomplete item before repeating creation. See the variable guide for insertion, defaults and deletion behavior.

Also find this under: system instructions, prompt template, reusable role, create Memory.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/memory-create.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Define Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

[Maintain a Memory](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md)

Reviewed: 2026-10-23. UI labels use the English app language.
