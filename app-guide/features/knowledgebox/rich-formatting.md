# Format a rich knowledge document

Format a `.ddjson` document, insert links/images and save the resulting content.

## Start here

**Desktop:** Open a rich KnowledgeBox document. Writable local documents start in edit mode; remote documents have their own toolbar and explicit Save.

**Mobile:** Shortcuts → DingDong → your Pure → Knowledge → Files → document → Formatting. Choose Edit document first if currently in Reading mode.

## Desktop steps

1. Open a local rich document, select text or place the cursor for subsequent typing. Scroll either toolbar row horizontally to reach its remaining controls.
2. Use styles, lists, quote, code block, indentation or the Alignment choice menu. Font/Size, Heading and Line height open pickers; selecting a row applies it. Heading offers 1–3 or Normal; line height offers 1, 1.15, 1.5 or 2.
3. For text/background color, select a Material swatch to apply it immediately, or choose Color for the custom picker/HEX. Enter 6 or 8 HEX digits without `#`, then OK/keyboard Done. Clear removes only that color; Cancel does not apply it.
4. Use Link to enter the display Text and address, then OK. Both must be nonempty and the address needs a supported prefix such as `https://`, `http://` or `mailto:`. Selecting an existing link prefills its text/address; changing it replaces that link's text and attribute.
5. Use Insert image and choose a supported file. Keep referenced image files available with the document. Use this action for native clipboard images on desktop.
6. Use Copy/Cut/Paste for a selection and available clipboard data. Image references from an incompatible or changed KnowledgeBox source can be rejected; copy again from the current source.
7. Save and review in View mode. Local rich edits also normally auto-save after two seconds. Remote documents use a different default toolbar and explicit Save; do not assume the local picker layout or automatic saving applies there.

## Mobile steps

1. Open the supported document and expand Formatting while editing. If in Reading mode, choose Edit document first.
2. Select text or a paragraph and apply styles, font/size, colors, lists, alignment, heading, line height or indentation. Mobile also offers inline code, subscript, superscript and direction controls.
3. Font/size/heading/line-height choices apply when tapped. Color uses the same immediate Material choice or confirmed custom/HEX flow as local desktop. Clear format removes selected formatting attributes without deleting the text.
4. For Link, enter nonempty Text and a supported address, then OK or keyboard Done. A bare hostname is not accepted. In editing mode, long-press a link for Open, Copy address or Remove; Remove keeps its text. Reading mode taps open links directly. This is different from adding an HTTPS reference to the separate Links collection.
5. Use Insert image to pick and import an image for this document. Copy/Cut require a selection; Paste requires supported clipboard content. Image preparation can require source access and can fail without insertion.
6. Check Save or the saved confirmation after automatic saving, then use Reading mode if desired. Collapsing Formatting or switching modes/documents can cancel a pending picker; reopen it for the current selection.

## Completion, limits and recovery

Local desktop/mobile font choices include Sans Serif, Serif, Monospace, Ibarra Real Nova, SquarePeg, Nunito, Pacifico and Roboto Mono; Clear removes an explicit font. Size offers Small, Large, Huge and Clear. These are document attributes, separate from code-editor appearance settings.

Mobile and desktop remote image imports support raster images up to 20 MiB per source file. Follow any image-format, size or preview error shown by the app. Keep referenced images available with the document.

Undo/Redo require history. Read-only documents limit editing. If an action was rejected after the source changed, return to the current file and copy/choose again. Refer to [Content editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/content-editing.md) for save conflicts and dirty-draft handling.

Also find this under: bold, lists, rich text, document toolbar, image insert.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/rich-formatting.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
