# Navigate terminal conversations and workspaces

Switch DingDongs and threads without accidentally reconnecting the wrong folder.

## Start here

**Desktop:** Inside the cobell TUI conversation view.

**Mobile:** Mobile has its own chat screens; these keys/commands are desktop-terminal controls.

## Desktop steps

1. Run cobell and select a DingDong/workspace.
2. Use /switch or /use N to choose another listed conversation.
3. Review Ready, Set up or unavailable workspace badges before confirming a folder connection.
4. Use /resume, /older or /fork for history and threads.
5. Use /cd only to change the terminal’s working directory.

## Mobile steps

1. Use the normal mobile chat/thread controls for mobile conversations.
2. Use the desktop terminal when you need the listed slash commands.

## CLI steps

Type `/` to see commands; use arrows to select, Tab to complete and Enter to execute. Review the required argument before sending `/use N` or `/cd path`. `/dingdongs` opens management; `/switch` selects a conversation.

## Completion, limits and recovery

Existing bindings open their own directory; selecting an unbound DingDong can explicitly connect the displayed current folder. Cobelly has No workspace. Terminal threads have at most two levels: the first message creates a first-level thread, and /fork can create a second-level one. Each terminal has its own selected bot, thread and directory.

Also find this under: switch bot, resume thread, workspace selector, fork, cd.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/conversation.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

[Connect a KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Use terminal input, scrolling and exit keys](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/keyboard.md)

Reviewed: 2026-10-03. UI labels use the English app language.
