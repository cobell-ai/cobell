# Run local shell commands and send their context

Run a terminal-local command and attach its result to the next DingDong message.

## Start here

**Desktop:** Use !command in the personal TUI conversation input.

**Mobile:** Use a desktop terminal for this workflow; mobile knowledge shell tools are configured separately through Gear.

## Desktop steps

1. Use /cd path if the terminal directory needs to change.
2. Enter ! followed by one command.
3. Wait for its output and exit status.
4. Write a normal message describing what you want DingDong to do with that context.
5. Use /clear instead if the retained context should be discarded.

## Mobile steps

1. Use the desktop TUI to run !command and attach output to a subsequent message.
2. For DingDong-executed mobile shell work, configure KnowledgeBox Use on an eligible Android device.

## CLI steps

Example: run `!git status`, wait, then send a normal request such as “Explain the working tree changes.” Use commands appropriate for the actual local shell and folder.

## Completion, limits and recovery

Each command requires its own ! prefix. Shell output alone is not published as a chat message and does not invoke AI. Commands are non-interactive. A failed chat delivery keeps the output rather than rerunning the command. /cd changes the shell directory, not KnowledgeBox ownership.

Also find this under: bang command, shell output, terminal context, working directory.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/shell-context.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

[Navigate terminal conversations and workspaces](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/conversation.md)

Reviewed: 2026-10-03. UI labels use the English app language.
