# Manage objects from the terminal

Create and configure DingDongs, Memories, Toolboxes, Gear and Browsers in the TUI.

## Start here

**Desktop:** Run cobell manage [category], or inside the TUI use F2 or /manage [category].

**Mobile:** Use Shortcuts for mobile object management; the terminal management UI runs with desktop.

## Desktop steps

1. Run cobell manage, optionally with a category.
2. Select an object and inspect its detail/action pane.
3. Use n to create or the detail actions to edit/duplicate/delete where offered.
4. Fill and save fields; then use the form’s Save action to persist the whole object.
5. Use F2 to return to chat.

## Mobile steps

1. Use Shortcuts → DingDong, Browser or Device to manage corresponding objects.
2. Use the desktop terminal when you need TUI management.

## CLI steps

`cobell manage dingdongs|memories|toolboxes|gears|browsers`. Conversation shortcuts include `/dingdongs`, `/memories`, `/toolboxes`, `/gears` and `/browsers`. Long-text editors use Enter for newline and F10 to save; single-line fields also accept Enter.

## Completion, limits and recovery

Saving a long-text field updates the draft; saving the form persists the object. Deletion has an explicit confirmation. Browsing management does not select a chat or bind a folder. Built-in objects show public summaries rather than hidden schemas. Actual secret inputs are masked and saved values are not returned to the terminal.

Also find this under: terminal inventory, F2, F10, create Memory, manage Gear.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/management.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

[Create Gear from Memories and Toolboxes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-03. UI labels use the English app language.
