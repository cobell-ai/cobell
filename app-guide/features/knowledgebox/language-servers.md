# Configure desktop language servers

Prepare a desktop language server for local code navigation and formatting.

## Start here

**Desktop:** Open a supported local KnowledgeBox code file → file header Language server settings, or its editor LSP badge when shown.

**Mobile:** This setup interface is desktop-only. Mobile Knowledge file content remains available; the separate mobile code Editor is currently unavailable in normal use.

## Desktop steps

1. Open Language server settings and search by language name or ID. Use All, Ready or Missing to find entries. Ready indicates executable discovery, not verification of every language feature. Check the editor's error badge for runtime problems.
2. Choose Configure. Review the host-OS install instructions. Copy only copies a command; run the appropriate installation yourself outside this dialog if needed. Documentation links open externally.
3. For an existing server launcher, choose Pick executable. It stores a file path, with no extra-arguments field. Cancel keeps the old choice; Clear removes the override without deleting the file. An override is launched without additional arguments.
4. After installation or a path change, use that language's Rescan or the configure dialog's Re-scan. Reopen the file to check the required language features.
5. Save and close/reopen the code file to request setup again. If replacing or silencing an already running session, quit and relaunch Cobell so its stored preferences are applied to new setup.
6. Inspect the editor badge: LSP... is busy; a server name indicates a started session; LSP none opens installation settings; LSP error opens an unavailable banner and offers Restart. After Restart, reopen the file to set up another session.
7. Test the needed action, such as definition/implementation navigation or Format. A located/started server need not support every request.

## Mobile steps

1. Use the supported Knowledge file content screen to read/edit text.
2. Use a desktop local code file for this language-server setup and its language-assisted editor controls.

## Completion, limits and recovery

Path overrides and Silence save locally for the signed-in account as they are changed. Close does not cancel saved preferences; failures can revert them and show an action error. Retry reloads a failed preferences read.

Silence this language suppresses later setup/badges. It does not uninstall a server or stop an existing process immediately. To undo it when the badge is hidden, use the eligible local file's Language server settings → Configure and uncheck it.

Check the editor's error badge if language features fail, even when settings show Ready. Save unsaved edits before reopening the file or restarting Cobell.

Also find this under: LSP, autocomplete, formatter, executable path, install language server.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/language-servers.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
