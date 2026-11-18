# Answer DingDong questions in the terminal: screen reference

Use the bottom question panel and review all answers before submission.

## Open this screen

**Desktop:** A waiting DingDong opens the bottom questions panel; /answer reopens it.

**Mobile:** Use mobile’s DingDong question sheet instead of terminal keys.

## Controls

| Control or area | Location and behavior |
|---|---|
| Left/Right | Changes the question. |
| Up/Down | Chooses a suggestion. |
| Type / Write your own answer | Enters a custom answer. |
| Enter | Confirms an answer, then submits from the whole-set review. |
| Ctrl+J / supported Shift+Enter | Newline in a custom answer. |
| Tab/Shift+Tab | Changes questions while editing. |
| PageUp/PageDown | Scrolls long choices and review. |
| Esc | Hides the panel while retaining answers. |
| /answer / /stop | Reopens questions or explicitly ends the waiting run. |

## CLI

The chat draft is retained while answering questions. After submission the transcript shows the question/answer set.

## Conditions and results

Esc does not discard answers or stop the waiting AI by itself. Failed submissions preserve the answers for retry. Switching target/thread or ending the login session can invalidate the pending question set.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/questions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
