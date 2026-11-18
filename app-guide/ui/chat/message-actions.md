# Copy, edit, delete and inspect messages: screen reference

Use the action menu on the specific message you want to change or examine.

## Open this screen

**Desktop:** Hover a message for More, or right-click it.

**Mobile:** Open the message’s More menu.

## Controls

| Control or area | Location and behavior |
|---|---|
| Copy | Copies the message text, using a displayed translation or rewrite when present. Mobile formatted text copies as plain text; Markdown copy can retain markup. |
| Desktop text selection / Copy selection | Select a nonempty text range, then open the message menu and choose Copy selection. Copies that range as plain text; the item is absent without a selection. |
| Desktop formatted message preview | Text can be selected, while its content and checklist boxes are read-only. It uses the message menu for Copy selection instead of a floating selection toolbar. Click a formatted link to open it through the system link handler. |
| Mobile Select text | Opens a scrollable text-selection dialog with the native selection toolbar and Close. Select a range and use its Copy action. It uses the displayed translation/rewrite when present, converts formatted text to plain text and simplifies common Markdown marks. |
| View larger | Opens an expanded message view. Desktop offers this for eligible text messages. |
| Edit | Opens a supported message editor. |
| Done editing / Save | Applies an edit. |
| Edit history | Shows Original and later revisions. On desktop, scroll to read each version's text, title when present, author/editor and time. Other editors' names are emphasized; the rows have no restore action. Close leaves the history. |
| Delete / Delete message | Desktop ordinary-message Delete submits immediately without a confirmation window. Mobile ordinary-message deletion asks for confirmation. Thread deletion has its own confirmation. |
| Report | Opens the report flow. |
| Recipient badge | Opens the message's [stored recipients or exclusions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/recipient-filter.md). This is an audience rule, not a delivery or read receipt. |

## Desktop menu keys

While the message menu is open, use the key shown beside an available action. These are menu keys without Ctrl, Alt or the system modifier; they apply only while that menu is open. Escape closes the menu without choosing an action.

| Key | Action |
|---|---|
| S | Copy selection, when a text range is selected. |
| C | Copy. |
| V | View larger, when offered. |
| R | Reply, when offered. |
| E | Edit, when offered. |
| H | Hide or Unhide, when offered. |

## Desktop expanded view and editing

View larger has Copy, Edit history for an edited message, and the available Edit and Co-edit or Join co-edit actions. Co-edit closes the expanded view and opens the shared editor. Close or Escape leaves the expanded view; clicking its backdrop does not close it.

Edit switches the expanded view to a multiline text field. A DingDong message also has a Message title field. Done editing is disabled until the body or title changes. A DingDong title must contain text and be at most 120 characters after trimming; an invalid title shows an inline error and prevents saving. Cancel discards the draft and returns to viewing. Close or Escape discards the draft and closes the window without a discard confirmation.

The separate Edit dialog has the same text/title fields and save conditions. Cancel or Escape closes it without saving; clicking its backdrop leaves it open. Both desktop editors start with the original message text even when a translation or rewrite is displayed. They edit text rather than rich formatting: saving a formatted message through this single-person editor converts it to plain text.

Done editing closes the editor and submits the change. A failed initial save shows an error and reopens the separate editor with the submitted text and title. If that retry also fails, an error is shown without reopening another editor.

## Mobile expanded view, history and editing

View larger opens a full-screen view with selectable content, Copy and the available Edit history, Edit and Co-edit actions. Edit history or Co-edit closes that view before opening the next screen. Edit history is a scrollable sheet of Original and numbered revisions, with titles when present, editor names and times. Its text previews can be selected and copied; Close leaves the sheet. History has no restore action.

Edit opens a full-screen multiline text editor; DingDong messages also have a title field. Editing starts with the original text, even when a translation or rewrite was displayed. Saving a formatted message through this editor changes it to plain text. Save is available before changes and validates when pressed: the trimmed body must contain text, and a DingDong title must contain text and be at most 120 characters after trimming. Validation errors appear with the body field.

While saving, a spinner replaces Save; the fields, Cancel/Close and system Back are disabled. A successful save in View larger returns to its reading mode. A successful save from the separate editor closes it. A failed save keeps the editor and draft open with an error so it can be retried. Outside a save, Cancel in View larger returns to reading without saving; Close or Back leaves the view. The separate editor's Cancel or Back leaves without saving. There is no discard confirmation.

In View larger and history, use the native text-selection toolbar to copy a range. Select text has a separate dialog and an accessibility Copy action that copies its selection, or the whole dialog text when no valid range is selected. For a message with multiple interim sections, ordinary Copy includes all sections; Select text shows the latest section.

## Links in Markdown messages

HTTPS links in a Markdown message open an address confirmation. The address can be selected and copied. Desktop uses Open external link with OK and Cancel; mobile uses Open with Open and Cancel. Confirming opens the address in an external browser or app. Cancelling or dismissing the dialog leaves the link unopened. These controls do not open other URL schemes. Mobile also applies the confirmation to recognized HTTPS links in plain text.

Desktop Markdown text can be selected; its expanded view uses the text-selection toolbar. External-image buttons have a separate [image loading confirmation](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/attachments.md).

## Conditions and results

Available actions depend on author, message type, room state and permissions. Edits made by another person are marked separately. Editing, deleting, reporting and hiding from AI have different effects.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/message-actions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
