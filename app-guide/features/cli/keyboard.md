# Use terminal input, scrolling and exit keys

Edit drafts and leave the TUI while preserving the intended operation.

## Start here

**Desktop:** Inside the cobell terminal.

**Mobile:** These are terminal controls, not mobile touch gestures.

## Desktop steps

1. Type the message; use Ctrl+J for a reliable multiline draft.
2. Use Enter to send.
3. Scroll with PageUp/PageDown and return to live output with Ctrl+End.
4. Use Alt+Up/Down to recall input.
5. Quit with /quit, or review the two-step Ctrl+C behavior.

## Mobile steps

1. Use the mobile composer’s normal text controls.
2. These terminal keyboard gestures require a desktop terminal session.

## CLI steps

Use `/locale LANGUAGE` to set a CLI-only language or `/locale app` to follow desktop. `/help` lists the active key bindings and commands.

## Completion, limits and recovery

Shift+Enter depends on terminal input modes and bindings; if it sends like Enter, use Ctrl+J. Esc first dismisses a menu/error/questions panel, then may stop work when no such overlay is open. Closing the TUI is separate from cobell logout. Hold Shift for native terminal text selection while mouse tracking is active.

Also find this under: new line, terminal shortcuts, scroll, draft recall, Ctrl+C.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/keyboard.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
