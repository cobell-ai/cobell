# Create a reusable Memory: screen reference

Create a private instruction template, then attach it to Gear separately.

## Open this screen

**Desktop:** Management → Memory → Add in a populated header, or Create Memory in the empty state.

**Mobile:** Shortcuts → DingDong → Memory → Create (+) above the collection list.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Set up manually / Create through conversation | Manual opens a two-step form. Conversation launches System DingDong assistance and closes this dialog when launch succeeds. Opening the chat does not prove a Memory was created. |
| Memory name / Name | Required, trimmed display label, at most 40 characters. Reserved/control characters are rejected at validation. |
| Desktop All / DingDong type chips | All defaults on. Turn it off to choose System or Pure individually. An empty selection also means all supported types. |
| Desktop Next | Goes from name/types to content after checking that the name is nonempty. Full name validation runs on Create. |
| Desktop Previous | From content returns to name/types; from the first step returns to the creation-method cards. It preserves the draft while this dialog remains open. |
| Content / Prompt content | Nonempty working instructions. Desktop uses the second step; mobile keeps it in the same creation form. |
| Desktop Add template variable / cards | Name dialog inserts an exact triple-brace token. Cards edit defaults/descriptions or delete the definition and all exact tokens. See the variable guide for name cleanup and insertion behavior. |
| Mobile variable-name field / Add icon / Enter | Inline field, at most 100 characters. Trims outer whitespace; rejects empty, duplicate or brace-containing names. Replaces selected prompt text with the token, or appends if selection is invalid, then clears the name field. |
| Mobile variable chip delete | Removes its definition and every exact token from the prompt draft. Complete tokens typed directly also synchronize the chips. Creation has no default/description fields; edit those after creation in Edit prompt. |
| Mobile supported-type chips | Keep All types or choose Pure. Removing the individual choice returns to All types. |
| Mobile conversation icon | Header action Create Memory with System DingDong starts assistance. A failed AI command can still open the created thread with a failure message; inspect the result before retrying. |
| Desktop Create / close | Create awaits the request; Create/Previous are blocked while submitting. Success closes the dialog; an error keeps it. Close dismisses without submitting a new request and does not cancel one already sent. |
| Mobile Create / Back | Sends a validated draft and normally opens the created Memory detail. Dirty Back offers keep editing/discard; submission and assistance sending block departure. |
| Mobile incomplete-created notice / Open | A Memory ID was allocated but the saved content could not be confirmed. Open that item to inspect it; the form no longer offers another Create for that result. |

## Conditions and results

Display names can contain spaces and common punctuation, but not double quotes, forward/back slashes, angle brackets or vertical bars; control characters are also rejected. Supported types describe compatibility. The supported-type display on an existing Memory is read-only.

Memory is reusable instructions, not chat history. Mobile validates complete `{{{name}}}` tokens and matching unique definitions before creating. An empty default requires a value in Gear. Creating or opening assistance does not equip the Memory or complete a DingDong's configuration.

After an uncertain desktop create, refresh the list before repeating it. On mobile, inspect the named incomplete Memory through Open before creating another. A conversation message/thread is not a creation confirmation.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-create.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Define Memory template variables](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-variables.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

[Maintain a Memory](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md)

Reviewed: 2026-10-23. UI labels use the English app language.
