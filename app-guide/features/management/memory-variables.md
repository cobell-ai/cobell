# Define Memory template variables

Separate reusable instructions from values supplied by each Gear.

## Start here

**Desktop:** Management → Memory → editable private Memory → Content → Edit.

**Mobile:** Shortcuts → DingDong → Memory → select the Memory → Edit prompt. Use Template variables inside this editor to edit definitions; the same label on Memory detail is a read-only saved list.

## Desktop steps

1. Open Content → Edit. Place the cursor where the token should go.
2. Choose Add template variable, enter a name and press Add or Enter. The dialog removes whitespace/punctuation except `_` and `-`. It inserts at the selection's base position without replacing the selected text.
3. Or type an exact token such as `{{{tone}}}` directly. Repeated tokens share one definition; the cards below the prompt update after a short delay.
4. Set Default value and Description in the card. To remove a variable, use its delete icon; this removes all exact copies of its token as well as the definition from the draft.
5. Review the prompt and Save. Success leaves edit mode; failure keeps it. Cancel discards the prompt/definition draft. The saved-content Template variables dialog only displays values.

## Mobile steps

1. Open Edit prompt and place the cursor or select text to replace.
2. Choose Add template variable, enter a name of at most 100 characters and use Add or Enter. Outer whitespace is trimmed; blank input inserts nothing. An existing name is rejected in this dialog, so type its token directly to reuse it.
3. Open Template variables from inside the prompt editor. Edit Default value and Description, or delete a variable and all its exact tokens.
4. Go Back to the prompt. These edits remain in the draft; the variable screen has no separate Save.
5. Review and Save from the prompt screen. Success shows a message and stays there. Back with unsaved edits offers Cancel or Discard; saving blocks departure.
6. After uncertain saving, use Check saved content. It reads the saved content while retaining your draft and does not save again. Retry handles an initial read failure.

## Completion, limits and recovery

Use `{{{name}}}` with exact spelling and case. Letters, numbers, `_` and `-` without spaces work consistently across the two apps. Mobile save validates names, triple-brace syntax, matching unique definitions and nonempty prompt text.

An empty default means the Gear must supply a value. Saving a Memory does not attach it or fill those values. Inspect the saved list from Memory detail, then configure the Memory's values in each Gear separately.

To rename a variable, replace its tokens in the prompt and review the new definition. Removing the last occurrence drops the old definition, including its default/description. Re-adding the name starts an empty definition; re-enter those fields if needed.

Also find this under: triple braces, variable defaults, prompt parameters, template values.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/memory-variables.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Edit Memory content](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md) · [Set values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
