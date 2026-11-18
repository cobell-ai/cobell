# Use code-editor tabs, search and shortcuts

Find, replace and navigate text in the desktop local editor, then save the changed buffer.

## Start here

**Desktop:** Open a text/code KnowledgeBox entry; use the editor toolbar and document tabs.

**Mobile:** The separate code Editor is currently unavailable in normal use. Use the Knowledge file content screen for supported text instead.

## Desktop steps

1. Open a local KnowledgeBox text/code file. Use Undo/Redo for buffer history and the settings gear for font/theme/layout preferences.
2. Press Ctrl+F for Find or Ctrl+H for replacement. Enter a query and set case, whole-word or regular-expression matching as needed. Move through results with arrows, Enter/Shift+Enter or F3/Shift+F3.
3. For replacement, enter the replacement text and choose Replace or Replace all. Enter in replacement replaces one match; Alt+Enter in the find field with replacement open replaces all. Esc closes the panel.
4. Use Outline or Ctrl+Shift+O for document symbols, Ctrl+G for a line, and F12/Ctrl+F12 for definition/implementation. F2 renames a symbol, not the filename. Language actions require a configured server that supports them.
5. Format/Shift+Alt+F changes the buffer where supported. Fold all/Unfold all changes its presentation. Alt+Up/Down moves a line, Shift+Alt+Down duplicates it and Ctrl+/ toggles supported line comments.
6. Press Save/Ctrl+S. Auto-save starts enabled with a two-second delay after edits; toggle it in this local editor's toolbar. Check errors rather than assuming the timer saved a failed write.
7. Use the KnowledgeBox resource tab strip to select or close files. Close Others/Close All resolve dirty buffers with Save, Discard or Cancel. Switching existing tabs keeps drafts; a failed Save stops closure.

## Mobile steps

1. Open Shortcuts → DingDong → your Pure → Knowledge → Files and select supported text.
2. Use the content screen's Search file, result rows and Save. Save before paging or opening a search result.
3. For the full flow, read [Content editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/content-editing.md). The unavailable separate Editor's preview controls are not normal file-persistence instructions.

## Completion, limits and recovery

Ctrl-style desktop commands also accept Meta/Cmd. Read-only views and language servers without the needed capability can limit actions. Remote text uses the paged content view rather than this local toolbar; the local Auto-save toggle does not configure it.

Save conflicts preserve a draft where possible and block forced overwrite. Keep any needed text before a conflict message's Refresh reloads the source. The local editor's internal tab strip is hidden in KnowledgeBox. Its Ctrl+W/Ctrl+Tab shortcuts act on internal files; use the outer resource strip to select or close KnowledgeBox files.

Also find this under: code editor, find replace, document tabs, keyboard shortcuts.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/editor-controls.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

[Change editor preferences](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-settings.md) · [Configure desktop language servers](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/language-servers.md)

Reviewed: 2026-10-24. UI labels use the English app language.
