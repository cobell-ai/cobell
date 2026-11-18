# Configure desktop language servers: screen reference

Find a desktop language-server executable and distinguish discovery from the editor's running process.

## Open this screen

**Desktop:** Open a supported local KnowledgeBox code file. Click its editor LSP badge when shown, or the file header's Language server settings action. The header action requires a local file with a registered server language.

**Mobile:** This installation/settings interface is desktop-only. Supported mobile Knowledge files use their content screen; the separate mobile code Editor is currently unavailable in normal use.

## Controls

| Control or area | Location and behavior |
|---|---|
| Language server settings / Search language or ID | Lists registered languages in name order; search matches display name or language ID without case sensitivity. |
| All / Ready / Missing | Filters executable discovery. Ready means a candidate file was found; it does not prove the server starts or every language request works. Missing includes unlocated/not-yet-resolved entries. |
| Errored | For runtime problems, inspect the active editor's error badge. |
| Re-scan all | Checks registered language entries. After installing a server or changing its path, use that language's Rescan. |
| Row Rescan / configure-dialog Re-scan | Checks that language's executable after installation or a path change. Reopen the file to verify the required features. |
| Configure | Opens this language's install guide, discovered path, custom-path preference and Silence checkbox. |
| Install commands / Copy / documentation link | Shows host-OS instructions. Copy puts a command on the clipboard; it does not execute or install anything. A documentation link opens an external application. |
| Current/custom path | Selectable path text. A displayed discovered path is not an editable command field. |
| Pick executable | Opens a native file picker and stores the selected file as a custom override. Cancel keeps the previous preference. No command-argument field is provided. |
| Clear | Removes the custom override and reruns normal candidate discovery; it does not delete the executable. |
| Silence this language | Stores a local per-language opt-out for later server setup. It does not uninstall the server or immediately terminate an already running process. |
| Restart | Offered in the active editor's error-badge dialog. After using it, reopen the file and check the required language features. |
| Close / settings load failure → Retry | Closes the dialog or reloads its account-local preferences. Path/Silence changes save as used, without a final Apply step. A failed preference save reverts the shown value and reports failure. |

## Active editor badge

| Badge state | Behavior |
|---|---|
| LSP... | Progress state; not clickable. |
| Server name | A server session started. Click for the current path/install settings; this does not guarantee every language feature is supported. |
| LSP none | Click for installation/discovery settings. |
| LSP error | Click for a runtime-unavailable banner and Restart. |
| Silenced / no registered server | Badge is hidden; use the eligible file header action to configure or uncheck Silence. |

## Conditions and results

Choose an existing language-server launcher or use normal executable discovery. Clearing a custom override restores normal discovery. Custom executable settings do not accept additional arguments; choose a launcher that works without them.

Preferences are local to the signed-in account. Installation changes do not hot-reconfigure the active editor. After discovery, close and reopen the file to request server setup again. To replace or silence an already running session reliably, quit and relaunch Cobell; Rescan alone does not do that. Save dirty files before closing.

After Restart, reopen the file and check the error badge and required language features. If an executable setting does not take effect, save your edits and relaunch Cobell. Ready does not guarantee that every language request succeeds.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/language-servers.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
