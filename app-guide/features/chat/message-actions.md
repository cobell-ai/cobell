# Copy, edit, delete and inspect messages

Use the action menu on the specific message you want to change or examine.

## Start here

**Desktop:** Hover a message for More, or right-click it.

**Mobile:** Open the message’s More menu.

## Desktop steps

1. Open a message’s right-click or More menu.
2. Use Copy, View larger or Edit history to inspect it. To copy part of a message, select the text first, then choose Copy selection in its menu. This copies plain text. If a translation or rewrite is displayed, Copy uses that displayed text.
3. For an editable message, choose Edit, change its text and choose Done editing. A DingDong message also has a title field; its title must contain text and be at most 120 characters after trimming. Saving is disabled until the body or title changes and the title is valid.
4. Choose Delete only after checking the target: an ordinary desktop message is deleted without a separate confirmation window. Thread deletion asks for confirmation.

Formatted message previews allow text selection. Their checklist boxes and text remain read-only; use the separate Edit action when available to change the message. Open the message menu for Copy selection. A link inside a formatted desktop message opens through the system link handler when clicked.

An open desktop message menu also accepts the displayed action keys: S for Copy selection, C for Copy, V for View larger, R for Reply, E for Edit and H for Hide/Unhide. Only available actions respond. Use these keys without Ctrl, Alt or the system modifier. Escape closes the menu.

View larger provides Copy, Edit history for edited messages and any available Edit or Co-edit/Join co-edit action. In its editor, Cancel discards changes and returns to viewing; Close or Escape discards changes and closes the window. In the separate Edit dialog, Cancel or Escape closes without saving. Neither editor closes when its backdrop is clicked.

Desktop single-person editing starts with the original text, including when you were viewing a translation or rewrite. It uses text fields; saving a formatted message this way converts it to plain text. A failed initial save reopens the separate editor with the submitted draft. A failed retry shows an error without another reopening.

## Mobile steps

1. Open the message’s More menu.
2. Use Copy, Select text, View larger or Edit history as needed. Select text opens a scrollable selection window: select a range, use the native toolbar's Copy action, then Close. It uses the displayed translation or rewrite when present, makes formatted content plain text and simplifies common Markdown marks. Ordinary Copy can retain Markdown markup.
3. For a supported edit, choose Edit and Save. The trimmed body must contain text; a DingDong title must also contain text and be at most 120 characters after trimming. These checks run when Save is pressed.
4. Choose Delete message and confirm only for the intended message.

View larger has selectable content, Copy and any available Edit history, Edit and Co-edit actions. History and Co-edit close the larger view before opening their screen. History lists the original and later revisions with text, titles when present, editor names and times. Select its text to copy, then Close; it has no restore action.

Mobile editing starts from the original text. Saving formatted content through this editor changes it to plain text. In View larger, Cancel returns to reading without saving, and Close or Back leaves. In the separate editor, Cancel or Back leaves without saving. These actions have no discard confirmation.

During a save, wait for the spinner: fields, Cancel/Close and system Back are disabled. Success returns View larger to reading, or closes the separate editor. Failure leaves your draft open with an error; correct it or retry Save.

## Completion, limits and recovery

On desktop, Edit history lists the original followed by numbered revisions. Scroll to read their text, title when present, author/editor and time, then Close. Another person's editor name is emphasized. History rows do not restore an earlier version.

To follow an HTTPS link in a Markdown message, select it and review the displayed address. Use OK on desktop or Open on mobile to open it in an external browser or app. The address is selectable for copying. Cancel or dismiss leaves it unopened. Other URL schemes are not opened through these Markdown controls. Mobile also confirms recognized HTTPS links in plain text. For an external image, use the separate [image loading controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/attachments.md).

Available actions depend on author, message type, room state and permissions. Edits made by another person are marked separately. Editing, deleting, reporting and hiding from AI have different effects.

Also find this under: message menu, edit history, delete message, copy text, large view.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/message-actions.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
