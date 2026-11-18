# Define Memory template variables: screen reference

Separate reusable instructions from values supplied by each Gear.

## Open this screen

**Desktop:** Management → Memory → editable private Memory → Content → Edit. Template variables in the saved-content view opens a read-only list when variables exist.

**Mobile:** Shortcuts → DingDong → Memory → select the Memory → Edit prompt → Add template variable or Template variables. The Template variables button directly on Memory detail opens a separate read-only saved list.

## Controls

| Control or area | Location and behavior |
|---|---|
| Prompt text | Uses exact `{{{name}}}` tokens. Complete tokens synchronize the definition list; repeated occurrences share one definition. Removing the last occurrence removes its definition from the draft. |
| Desktop Add template variable | Opens a name dialog. Add or Enter strips whitespace and characters other than letters, numbers, `_` and `-`; an empty result is rejected. Cancel inserts nothing. |
| Desktop insertion | Inserts at the selection's base position without replacing the selected text, then returns focus to the prompt. The same name may occur more than once. |
| Mobile Add template variable | Name dialog has a 100-character limit. Add/Enter trims outer whitespace, ignores an empty result and rejects an already defined name. Cancel inserts nothing. |
| Mobile insertion | Replaces the current selection with the token, or appends if there is no valid selection; returns focus to the prompt. Type an existing token directly to reuse its definition. |
| Default value / Description | Editable cards below desktop's prompt, or inside mobile prompt editor → Template variables. Changes affect the current prompt draft. Name is displayed rather than edited in these cards. |
| Delete variable | Removes the definition and all exact occurrences of its token from the draft, without a separate confirmation. Review the resulting prompt before saving. |
| Desktop Save / Cancel | Save awaits the Memory update and leaves prompt edit mode after success. Failure keeps editing. Cancel resets the unsaved prompt/variable draft. |
| Mobile variable-editor Back | Returns to the prompt with variable edits still in its draft. There is no separate Save in this child screen. |
| Mobile prompt Save / Back | Save persists prompt and variables together, shows success and stays in the prompt screen. Back with unsaved edits offers Cancel/Discard; saving blocks departure. |
| Mobile Check saved content / Retry | Check saved content reads saved content after uncertainty while retaining the draft; it does not save again. Retry handles a failed initial read. |
| Saved variable list | Desktop dialog: token, description, default/required status and Close. Mobile detail's Template variables: saved count, selectable text, required badge for empty defaults, Back and load Retry. Both are read-only and do not edit the prompt draft. |

## Conditions and results

A variable with an empty default requires a value in the Gear. Memory defaults/descriptions and a Gear's supplied values are separate settings. Use the same case and spelling in every token.

For names that work consistently in both apps, use letters, numbers, `_` or `-` without spaces. Desktop's Add dialog cleans other characters; mobile's dialog trims only the ends and limits the name to 100 characters. Mobile save rejects empty/padded/overlong names, malformed triple braces or mismatched definitions, and requires nonempty prompt text.

There is no name field for renaming an existing definition. Replace its tokens in the prompt, then review the new definition and re-enter its default/description. Removing all occurrences drops the old definition; adding the name again creates a new empty definition. Saving variables does not attach the Memory to a Gear or fill a Gear's required values.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Edit Memory content](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md) · [Set values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
