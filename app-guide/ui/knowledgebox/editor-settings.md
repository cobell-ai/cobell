# Change editor preferences: screen reference

Set local desktop text/code editor appearance and layout for the signed-in account.

## Open this screen

**Desktop:** Code/text editor toolbar → Editor settings (gear icon).

**Mobile:** A separate code Editor settings screen is not available. Use the controls provided by the Knowledge file content screen.

## Controls

| Control or area | Location and behavior |
|---|---|
| Font | Selects a bundled font or system monospace. Choices include JetBrains Mono, Fira Code, Cascadia Code, Source Code Pro, Inter, Pretendard and Noto Sans KR. |
| Font size | Slider from 10 to 22, in 0.5 steps; current size is displayed. |
| Light theme / Dark theme | Chooses editor syntax colors for each app appearance. Light: Atom One Light, GitHub, Xcode, Visual Studio. Dark: VS 2015, Atom One Dark, Monokai, Tokyo Night, Nord. |
| Line wrap | Changes long-line wrapping. |
| Code folding | Enables the editor's folding presentation. |
| Indent guide lines / Gutter divider | Changes indentation guides and the gutter separator. |
| Inlay hints / Document colors / Format on save | Values are stored; the editor does not currently apply them. Use the explicit Format action where supported. |
| Reset to defaults | Immediately applies/stores the default editor preferences; it is not a file-content reset. |
| Close | Returns to the document. Changes apply as controls are used; there is no Apply/Save step or discard-on-close behavior. |
| Loading / failed read → Retry | Waits for account-local settings or reloads them after a read failure. |

## Conditions and results

These preferences are stored locally for the signed-in normal account, rather than synchronized across devices. Defaults are JetBrains Mono 14, line wrap/folding/guides/gutter on, Atom One Light and VS 2015. Inlay hints and Format on save default off; Document colors defaults on, with the current behavior limitation above.

Appearance settings do not control file Auto-save. Use the local text editor's Auto-save toolbar toggle for that. Rich-document and remote-content views have their own controls. If local preference persistence fails, the active settings can revert; reopen and check the result.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/editor-settings.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
