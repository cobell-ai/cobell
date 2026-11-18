# Use terminal input, scrolling and exit keys: screen reference

Edit drafts and leave the TUI while preserving the intended operation.

## Open this screen

**Desktop:** Inside the cobell terminal.

**Mobile:** These are terminal controls, not mobile touch gestures.

## Controls

| Control or area | Location and behavior |
|---|---|
| Enter | Sends/accepts the current input or selected action. |
| Ctrl+J | Inserts a newline across supported desktop platforms. |
| Shift+Enter | Newline only if the terminal reports the modifier. |
| Alt+Up/Down / Up on empty input | Recalls prior accepted or cleared drafts. |
| PageUp/PageDown / mouse wheel | Scrolls the conversation. |
| Ctrl+Home / Ctrl+End | Goes to start / returns to live output. |
| Ctrl+U/K / Home/End | Deletes around the cursor or moves within the line. |
| Ctrl+C | Saves and clears the draft; a second press within two seconds quits. |
| /quit / /exit | Closes immediately. |
| F3 | Opens full error details. |

## CLI

Use `/locale LANGUAGE` to set a CLI-only language or `/locale app` to follow desktop. `/help` lists the active key bindings and commands.

## Conditions and results

Shift+Enter depends on terminal input modes and bindings; if it sends like Enter, use Ctrl+J. Esc first dismisses a menu/error/questions panel, then may stop work when no such overlay is open. Closing the TUI is separate from cobell logout. Hold Shift for native terminal text selection while mouse tracking is active.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/keyboard.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
