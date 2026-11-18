# Manage objects from the terminal: screen reference

Create and configure DingDongs, Memories, Toolboxes, Gear and Browsers in the TUI.

## Open this screen

**Desktop:** Run cobell manage [category], or inside the TUI use F2 or /manage [category].

**Mobile:** Use Shortcuts for mobile object management; the terminal management UI runs with desktop.

## Controls

| Control or area | Location and behavior |
|---|---|
| Category tabs | dingdongs, memories, toolboxes, gears or browsers. |
| Arrows or j/k / Enter | Moves selection and opens an item/action. |
| Left/Right | Changes category. |
| Tab | Changes inventory/detail pane; on narrow terminals switches full views. |
| / | Searches the inventory. |
| n / r | Creates or refreshes all inventories. |
| F10 | Saves a field/form through its displayed action. |
| Esc | Returns or cancels an editor; does not stop chat AI. |
| F2 | Switches back to conversation while retaining drafts. |

## CLI

`cobell manage dingdongs|memories|toolboxes|gears|browsers`. Conversation shortcuts include `/dingdongs`, `/memories`, `/toolboxes`, `/gears` and `/browsers`. Long-text editors use Enter for newline and F10 to save; single-line fields also accept Enter.

## Conditions and results

Saving a long-text field updates the draft; saving the form persists the object. Deletion has an explicit confirmation. Browsing management does not select a chat or bind a folder. Built-in objects show public summaries rather than hidden schemas. Actual secret inputs are masked and saved values are not returned to the terminal.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/management.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

[Create Gear from Memories and Toolboxes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-03. UI labels use the English app language.
