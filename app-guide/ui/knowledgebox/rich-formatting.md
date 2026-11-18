# Format a rich knowledge document: screen reference

Format supported `.ddjson` content using the opened document's controls.

## Open this screen

**Desktop:** Open a local rich KnowledgeBox document. Writable documents start in edit mode; its formatting toolbar has two horizontally scrollable rows. Remote documents use a different toolbar.

**Mobile:** Shortcuts → DingDong → your Pure → Knowledge → Files → supported document → Formatting. Writable documents start in edit mode; use Edit document if currently in Reading mode.

## Controls

| Control or area | Location and behavior |
|---|---|
| Undo / Redo | Reverses or reapplies document edits when history is available. |
| Bold / Italic / Underline / Strike | Formats selected text or subsequent typing at the cursor. |
| Clear format | Removes formatting attributes in the selection, including block attributes where present. It does not delete the text or discard the whole draft. |
| Text color / Background color | Opens the color dialog. A Material palette choice applies immediately. Color opens the custom picker; OK or keyboard Done confirms a valid custom/HEX value. |
| HEX / Clear / Cancel in the color dialog | HEX accepts 6 or 8 hexadecimal digits without `#`; invalid input disables OK. Clear immediately removes that color attribute. Cancel leaves formatting unchanged. |
| Checklist / Bulleted list / Numbered list | Changes the selected paragraph/list structure. |
| Alignment | Desktop local opens a choice menu; mobile offers left/center/right/justify buttons. |
| Quote / Code block / Increase indent / Decrease indent | Applies paragraph formatting. A code block here is a rich-document block, not the separate code editor. |
| Font | Opens choices: Sans Serif, Serif, Monospace, Ibarra Real Nova, SquarePeg, Nunito, Pacifico, Roboto Mono and Clear. Choosing a row applies it. |
| Size | Offers Small, Large, Huge and Clear; Clear removes the explicit size attribute. |
| Heading | Offers Heading 1, Heading 2, Heading 3 and Normal in the local desktop/mobile picker. |
| Line height | Offers 1, 1.15, 1.5 and 2 on both local desktop and mobile. |
| Mobile Inline code / Subscript / Superscript / Direction | Additional mobile toolbar styles. The local desktop two-row toolbar does not expose these buttons. |
| Link | Opens Text and Link fields, prefilled from selected text or an existing link. Both require nonempty values and a supported URL prefix. OK or keyboard Done applies; Cancel keeps the document unchanged. |
| In-document link actions | In reading mode, tap/click a link to open it. Desktop editing uses Ctrl/Meta+click. Mobile editing uses long-press for Open, Copy address or Remove link; removing the link keeps its text. |
| Insert image | Opens the system image picker; cancel adds nothing. Choose a supported file and keep referenced images available with the document. |
| Copy / Cut / Paste | Copy/Cut need a selection; Cut/Paste need editing. Paste availability also depends on clipboard content. Imported image content can require an available source device. |
| Formatting expansion on mobile | Shows/hides the formatting toolbar. Collapsing it or changing mode can cancel a pending formatting choice. |
| Search / Reading or View mode / Save | Uses the content screen's search, mode and save controls; see Content editing for local/remote persistence differences. |

## Link and clipboard limits

Use a complete supported URL for an in-document link, such as `https://example.com/`; a bare hostname is not accepted. Follow any link error shown by the editor. The [knowledge link collection](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/links.md) requires HTTPS.

Mobile and desktop remote image imports support raster images up to 20 MiB per source file. Follow any format, size or preview error shown by the app. Keep referenced images available with the document.

Keep referenced images available when copying rich content. On desktop, use Insert image for a native clipboard image. Mobile can import supported clipboard images. If pasting fails, copy again from an available source or insert a supported image file.

## Conditions and results

Choosing a font/size/heading/line-height row or Material color changes the document immediately; closing a picker without a choice does not. If the source, document or editing mode changes while a dialog/picker is open, reopen the control for the current document rather than expecting the old choice to apply.

Local desktop and mobile rich edits normally auto-save after two seconds and also offer Save. Desktop remote rich documents use explicit Save and a separate default toolbar; the custom picker details above describe local desktop/mobile. Read-only views limit editing. See [Content editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/content-editing.md) for conflicts, failed saves and leaving drafts.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/rich-formatting.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
