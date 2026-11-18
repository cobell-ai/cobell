# Run local shell commands and send their context: screen reference

Run a terminal-local command and attach its result to the next DingDong message.

## Open this screen

**Desktop:** Use !command in the personal TUI conversation input.

**Mobile:** Use a desktop terminal for this workflow; mobile knowledge shell tools are configured separately through Gear.

## Controls

| Control or area | Location and behavior |
|---|---|
| !command | Starts one non-interactive local shell command. |
| Command progress/output | Shows command, directory, exit code and captured output. |
| /cd path | Changes the directory for subsequent commands. |
| Next normal message | Sends retained shell context with one user message and invokes DingDong once. |
| /clear | Discards pending shell context. |
| Failed delivery / retry | Retains results without rerunning the command. |

## CLI

Example: run `!git status`, wait, then send a normal request such as “Explain the working tree changes.” Use commands appropriate for the actual local shell and folder.

## Conditions and results

Each command requires its own ! prefix. Shell output alone is not published as a chat message and does not invoke AI. Commands are non-interactive. A failed chat delivery keeps the output rather than rerunning the command. /cd changes the shell directory, not KnowledgeBox ownership.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/shell-context.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

[Navigate terminal conversations and workspaces](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/conversation.md)

Reviewed: 2026-10-03. UI labels use the English app language.
