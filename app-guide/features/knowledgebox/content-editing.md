# Read and edit knowledge content

Edit the selected device's text or rich-document contents and check the save result.

## Start here

**Desktop:** Management → Pure → select your DingDong → KnowledgeBox → select a file; content appears in resource tabs.

**Mobile:** Shortcuts → DingDong → select your Pure → Knowledge → Files → select a supported entry.

## Desktop steps

1. Select the source device and file in the KnowledgeBox tree. Images open a pan/zoom preview; text and supported `.ddjson` documents have editors. Unsupported files can still show information.
2. For a local text/code file, edit and use Save/Ctrl+S. Auto-save starts enabled with a two-second delay; its toolbar switch changes that editor's behavior.
3. For remote text, check the displayed line range. Save the edited range before using previous/next arrows or selecting a search result. Enter in the remote search field searches the saved source file.
4. For a local rich document, use its view/edit toggle, Search and Insert image where offered. Edits normally auto-save after two seconds; Save is also available. A remote rich document uses its explicit Save action.
5. Click a resource tab's name to switch without losing its buffer. Reopening the same entry activates its existing tab. Scroll the strip horizontally to find more tabs.
6. Use × on the active/hovered tab, or right-click a tab for Close, Close other tabs or Close all tabs. Close other tabs keeps and activates the tab you right-clicked. The local code editor's internal tab strip is hidden here; its Ctrl+W/Ctrl+Tab shortcuts do not control the resource strip.
7. Save files you need before closing tabs. Follow each Save, Discard or Cancel prompt; Esc also cancels. Cancel does not undo saves already completed. Canceling a switch to Links returns to Files. Closing tabs keeps their source files.
8. Before using the profile header's Chat button or Back arrow, or leaving the detail page, save and check the result. These actions do not run the resource-tab Save/Discard/Cancel check. Keeping buffers between open file tabs does not guarantee keeping them after leaving KnowledgeBox.

## Mobile steps

1. Select the source device, then tap a file in Knowledge → Files. The content screen shows its relative path and any access/read failure.
2. For text, edit File contents and press Save. Local text initially uses one complete loaded view within the supported read limit; remote text can use pages. Previous page/Next page and search-result navigation stay disabled while there are unsaved edits.
3. To search saved text, enter up to 256 characters in Search file and press Search or the keyboard action. Tap a result's preview/line to load that page after saving the draft.
4. A writable rich document starts in editing mode. Reading mode/Edit document switches modes; Search finds rendered-document matches with previous/next controls. Insert image and the expandable formatting section are available while editing. Rich edits normally auto-save after two seconds and also offer Save.
5. Check the saved confirmation or failure message. Back with a dirty draft asks whether to discard or keep editing. Reload file also confirms discarding a dirty draft. Saving blocks conflicting actions and leaving.

## Completion, limits and recovery

Remote content requires an available source device and knowledge access. An image is a preview, and unsupported/binary files may have only information. Invalid rich content that fails to open is kept unchanged; some remote `.ddjson` content can fall back to text editing.

For a revision conflict, keep any needed draft text before reloading the current source. Repeated Save does not force an overwrite. The desktop conflict message's Refresh reloads the editor; mobile Reload file asks to discard changes. A save can succeed even if the next read fails, so check the current content before repeating it.

If a local mobile folder is unavailable, use the Knowledge folder button. Reopen from the list after a workspace/source change. Use the recovery guide if unfinished file changes pause updates. The separate mobile code Editor and its settings are currently unavailable in normal use; this Knowledge file screen remains available for supported content.

Also find this under: read file, edit document, rich text, search knowledge, remote preview.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/content-editing.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

[Use code-editor tabs, search and shortcuts](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-controls.md) · [Review unfinished mobile file changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md) · [Format a rich knowledge document](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/rich-formatting.md)

Reviewed: 2026-10-24. UI labels use the English app language.
