# Read and edit knowledge content: screen reference

Read file contents and save text or rich-document edits on the selected source device.

## Open this screen

**Desktop:** Management → Pure → select your DingDong → KnowledgeBox → select a file; content appears in resource tabs.

**Mobile:** Shortcuts → DingDong → select your Pure → Knowledge → Files → select a supported entry.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop local text/code editor | Opens a text file with the local editor toolbar. Save/Ctrl+S saves explicitly; Auto-save is initially enabled with a two-second delay after changes. See the separate editor-controls guide. |
| Desktop remote text | Shows a line range, previous/next page arrows, a search field and result rows. Submit a query with Enter; select a result to open its page. Unsaved edits block paging and result navigation. Save writes the edited range on the source device. |
| Mobile text / line range | Local text initially loads as one complete view within the supported read limit. Remote text can be paged. Edit File contents and press Save; this text flow has no Auto-save toggle. |
| Mobile Previous page / Next page | Navigates loaded ranges when available. Disabled with unsaved edits; save or discard/reload first. |
| Mobile Search file / Search | Searches the saved source file, with up to 256 characters per query. Keyboard Search also submits. Results show preview text and line numbers; tapping a result opens its page only when the draft is clean. |
| Rich document / reading mode | Supported `.ddjson` files use a formatted document view. Writable local desktop and mobile documents initially open in editing mode. View/Reading mode disables editing; Edit mode/Edit document returns to editing. |
| Rich Search | Desktop local and mobile rich views offer a search bar with previous/next matches. Mobile queries allow 256 characters, match without case sensitivity and show a match count. These matches use the rendered document rather than the paged-file search. |
| Rich Insert image / formatting | Inserts a supported image where offered. Mobile exposes its formatting tools through an expandable section. See the rich-formatting guide for individual formatting controls. |
| Rich Save / automatic save | Local desktop and mobile rich documents normally auto-save after two seconds without changes and also offer Save. Desktop remote rich documents offer an explicit Save button; they do not use the local editor's Auto-save toggle. |
| Image preview | Supports pan/zoom; it is not an image-editing screen. |
| Mobile Reload file | Reads the source again. A dirty draft requires a discard confirmation; Cancel keeps editing. |
| Mobile Knowledge folder | Shown for a local unavailable-folder error; opens workspace settings. |
| Desktop resource tab | Click its name to activate it. Opening the same entry again activates its existing tab. The strip scrolls horizontally; switching tabs keeps their buffers without confirming a save. |
| Desktop tab × / right-click → Close | Closes that tab after resolving any unsaved changes. The × is visible on the active or hovered tab. |
| Desktop right-click → Close other tabs | Keeps and activates the tab you right-clicked, even if a different tab was active. Resolves unsaved changes in the other tabs before closing them. |
| Desktop right-click → Close all tabs / Links switch | Resolves unsaved changes in all open resource tabs before closing them. Cancel or a failed save stops closing; a canceled Links switch returns to Files. |
| Mobile Back | Dirty content prompts to keep editing or discard. Saving blocks departure. Save using the content button before leaving if needed. |

## Conditions and results

Remote reads and writes require the source device and its knowledge access to be available. A metadata row alone does not prove readable content. Unsupported/binary files can show information without an editor; a malformed rich document that fails to open is not replaced with an empty document. Some remote `.ddjson` files can be presented in the text view instead.

Save failures keep a draft where possible. A revision conflict means the source changed; repeated Save does not force an overwrite. Preserve any needed draft text before reloading. The desktop conflict message's Refresh reloads source content; mobile Reload file asks to discard a dirty draft. Acknowledged saves can still be followed by a failed read.

Save files you need before closing tabs and follow each Save, Discard or Cancel prompt; Esc also cancels. Cancel does not undo saves already completed. Closing a tab does not delete its source file. Use the outer resource-tab controls to manage these tabs.

Save and check the result before using the profile header's Chat button or Back arrow, or leaving the Management detail. These actions do not use the resource-tab Save/Discard/Cancel check. Retention when switching between open file tabs does not imply retention after leaving KnowledgeBox.

Auto-save is not a substitute for checking a failure message. If the workspace changed, return to the file list and reopen the current entry. For paused unfinished changes, use the recovery guide.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/content-editing.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

[Use code-editor tabs, search and shortcuts](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-controls.md) · [Review unfinished mobile file changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md) · [Format a rich knowledge document](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/rich-formatting.md)

Reviewed: 2026-10-24. UI labels use the English app language.
