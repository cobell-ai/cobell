# Configure a Flow task node: screen reference

Assign the task's DingDong, Gear, prompt and execution behavior.

## Open this screen

**Desktop:** Editor → Node, or select an existing node → inspector.

**Mobile:** Editor → Add node, or tap a node → Node details.

## Controls

| Control or area | Behavior |
|---|---|
| Node name | Labels the task. |
| Assign / Change / DingDong and Gear | Chooses a DingDong and compatible Gear for this task. |
| DingDong / Gear tabs, Back, Confirm, Cancel | Assignment dialogs either choose the DingDong then Gear in successive steps or let an existing assignment be changed through tabs. Confirm accepts the current choices; Cancel abandons them. |
| No DingDong / No Gear | Clears an assignment where offered. An incomplete task cannot execute; a dialog requiring a complete assignment disables confirmation until both choices are valid. |
| Prompt / Edit | Edits task instructions. Desktop also supports double-clicking the prompt to edit, Ctrl+Enter to save that prompt draft and Esc to cancel it. |
| Intelligence level | Adjusts the task's available intelligence setting. |
| Data reception / Merge / Parallel | Appears for multiple incoming connections. Merge waits for all incoming paths for one execution; Parallel processes paths independently. |
| Self loop | Enables repeated execution of this node. |
| Iterations | Sets 2–999 repetitions when self loop is enabled. |
| Sequential / Parallel | Chooses iteration execution mode. |
| Max concurrent iterations | Available for parallel repetition; from 1 up to the iteration count. |
| External edge propagation | Sends to nodes outside the loop on the first or last iteration. |
| Connect from node / Connect to node | Fixes this node as connection source or target. |
| Duplicate / Delete | Copies or removes the node where offered. |
| Save / Apply / Cancel / Discard | Resolves the inspector's local draft. The main editor's Save/Save Flow persists graph changes. |

## Conditions and results

Every executable task needs a DingDong and compatible Gear. This Gear assignment is separate from the DingDong's personal chat room. Apply pending mobile inspector edits before connecting or duplicating when prompted.

Parallel incoming paths and parallel loop iterations are different settings. An execution snapshot's node view is read-only.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/nodes.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
