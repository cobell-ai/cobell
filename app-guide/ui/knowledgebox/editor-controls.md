# Use code-editor tabs, search and shortcuts: screen reference

Use the desktop local text/code editor's toolbar, search and keyboard controls.

## Open this screen

**Desktop:** Open a local text/code KnowledgeBox entry; use its editor toolbar. Manage files through the enclosing resource-tab strip.

**Mobile:** The separate code Editor screen is currently unavailable in normal use. Supported Knowledge files use the content screen described in [Read and edit knowledge content](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/content-editing.md).

## Controls

| Control or area | Location and behavior |
|---|---|
| Undo / Redo | Reverses or reapplies editable-buffer changes; requires undo/redo history. |
| Find / Toggle replace | Opens the find bar and optionally the replacement row. Ctrl+F toggles Find; Ctrl+H opens replacement mode. |
| Search input / match counter / previous / next | Updates matches and moves through them. Enter in the find field moves next; Shift+Enter moves previous. F3/Shift+F3 also navigate. |
| Match case / Match whole word / Use regular expression | Changes how the local editor matches the query. |
| Replacement input / Replace / Replace all | Replaces the current match or all matches. Enter in replacement submits one replacement; Alt+Enter from the find field in replacement mode replaces all. |
| Find close / Esc | Hides the find panel. Tab from the find field moves to replacement when its row is open. |
| Outline | Requests document symbols from the configured language server; selecting a result moves to it. Empty results are reported. |
| Format | Requests document formatting where a language server is configured and supports it. This edits the buffer and still needs persistence. |
| Fold all / Unfold all | Changes code folding; it does not change saved file text. |
| Auto-save | Initially enabled with a two-second delay after edits. The toggle applies to this editor controller, separately from appearance settings. |
| Save | Saves a changed writable buffer. A conflict blocks another overwrite until the current source is reloaded. |
| Editor settings | Opens local font/theme/layout preferences. |
| Resource tab select / close / Close Others / Close All | Selects an open KnowledgeBox buffer or closes the chosen set. Dirty closure prompts Save, Discard or Cancel; switching open tabs keeps drafts. |

## Desktop keyboard controls

| Shortcut | Behavior |
|---|---|
| Ctrl+S | Save. |
| Ctrl+G | Go to line: enter a line number and Go/Enter, or Cancel. |
| F12 / Ctrl+F12 | Go to definition / implementation through the configured language server. |
| F2 | Rename the symbol at the cursor through the language server. Enter a new symbol name and confirm; this is different from renaming a file in the tree. |
| Ctrl+Shift+O | Open the document outline. |
| Shift+Alt+F | Format the document where supported. |
| Alt+Up / Alt+Down | Move the current line. |
| Shift+Alt+Down | Duplicate a line. |
| Ctrl+/ | Toggle a line comment for a supported language. |
| Ctrl+W / Ctrl+Tab / Ctrl+Shift+Tab | Acts on the local editor's internal files, not the outer KnowledgeBox resource tabs. Its internal strip is hidden in KnowledgeBox; use the outer strip to select/close resources. |

## Conditions and results

Ctrl-style commands also accept Meta/Cmd. Symbol actions and formatting depend on the active language server and its supported requests; a toolbar button alone does not guarantee a result. Read-only views do not offer normal write actions.

This toolbar belongs to the local desktop editor. Remote KnowledgeBox text uses a different paged view with explicit Save, and mobile Knowledge text uses its own content screen. Do not apply the local Auto-save toggle, replacement controls or language-server shortcuts to those views.

If a conflict message offers Refresh, keep any needed draft before using it: reloading replaces the editor buffer with the current file. A failed Save is not a successful close.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-controls.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

[Change editor preferences](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-settings.md) · [Configure desktop language servers](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/language-servers.md)

Reviewed: 2026-10-24. UI labels use the English app language.
