# Navigate terminal conversations and workspaces: screen reference

Switch DingDongs and threads without accidentally reconnecting the wrong folder.

## Open this screen

**Desktop:** Inside the cobell TUI conversation view.

**Mobile:** Mobile has its own chat screens; these keys/commands are desktop-terminal controls.

## Controls

| Control or area | Location and behavior |
|---|---|
| /switch | Opens the conversation/workspace selector. |
| /use N | Selects a listed DingDong. |
| /cobelly | Switches to the System DingDong. |
| /clear | Starts a fresh thread on the next message and discards pending shell context. |
| /resume [N] | Lists or opens an earlier loaded root thread. |
| /older | Loads earlier history. |
| /fork | Starts a child thread, within terminal depth limits. |
| /cd path | Changes this terminal’s shell directory without rebinding knowledge. |
| /stop / /retry | Stops work or requests another response to the latest saved message. |

## CLI

Type `/` to see commands; use arrows to select, Tab to complete and Enter to execute. Review the required argument before sending `/use N` or `/cd path`. `/dingdongs` opens management; `/switch` selects a conversation.

## Conditions and results

Existing bindings open their own directory; selecting an unbound DingDong can explicitly connect the displayed current folder. Cobelly has No workspace. Terminal threads have at most two levels: the first message creates a first-level thread, and /fork can create a second-level one. Each terminal has its own selected bot, thread and directory.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/conversation.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

[Connect a KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Use terminal input, scrolling and exit keys](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/keyboard.md)

Reviewed: 2026-10-03. UI labels use the English app language.
