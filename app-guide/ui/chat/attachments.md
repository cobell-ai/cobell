# Send and open files or images: screen reference

Attach an ordinary file or image to a message and inspect received content.

## Open this screen

**Desktop:** Chat panel → open the room → composer → Send image / Send file, or More when the actions collapse.

**Mobile:** Second bottom tab Chat → open the room → composer → image/file action, or More in the compact action strip.

## Controls

| Control or area | Location and behavior |
|---|---|
| Send image | Opens image selection and upload. |
| Send file | Selects a regular file for upload. |
| Attachment progress / retry | Shows upload state and retries a failed attempt. |
| Desktop image bubble | Opens the image viewer. Loading shows a placeholder; a failed load shows an image error. |
| Mobile image bubble / failed preview | Opens the image viewer after loading. If loading fails, use a retry when offered or reopen the image from the current message. |
| Desktop file Save | Opens a save-location chooser before fetching the file. Choose a destination to download and write it. The file name, size and type icon are read-only; they do not open the file. |
| Mobile file Download file | Downloads the file first, then opens the system destination/export picker. Choose where to save it. The file name, size and icon are read-only. A long or unsupported suggested name can be cleaned or shortened. |
| Desktop Markdown View image / View image: caption | Opens Load image with a selectable address. OK loads an inline preview; Cancel or dismiss leaves it unloaded. The loaded Markdown preview has no viewer-opening gesture or retry button. |
| Mobile Markdown Load image / Load image: caption | Opens Load external image? with the address for review. Open loads the preview; Cancel leaves it unloaded. Tap a loaded preview to view it, or use a retry when offered after failure. |
| Desktop image viewer Close / image / backdrop / Escape | Any of these closes the viewer. A failed image decode shows a broken-image icon. |
| Mobile image viewer / Close | Pinch to zoom and drag to move the image. Close leaves the viewer. Reopen it from the current message after account or access changes. |
| Desktop Select file / Select image | For an ordinary upload above the limit, choose up to 10 files or 20 images. The first items up to that limit start selected. Scroll the file checkbox list or image grid; click to select or deselect. At the limit, deselect one before choosing another. |
| Selection Confirm (count) / Cancel / Close / backdrop | Confirm returns the selected items in their original picker order and continues the upload. It is disabled when none are selected. Cancel, Close or clicking outside leaves without uploading that selection. Image thumbnails toggle selection rather than opening a viewer. |

## Conditions and results

Ordinary attachments differ from KnowledgeBox imports and P2P offers. A failed upload is not a sent attachment. For Markdown external images, use View image or Load image and review the HTTPS address before confirming. A read-only history view can limit loading to images already cached on this device.

File saving shows a spinner and disables the save button during the operation. Desktop starts that busy state after a destination is chosen; mobile stays busy through download and the picker. A successful export shows File saved. Failure shows a save-error message, and the button becomes available after the attempt. Cancelling the destination picker leaves without exporting a file. A mobile save can retire when its account, message or navigation changes; return to the current message before trying again.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/attachments.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
