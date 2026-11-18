# Choose DingDong notification sources: screen reference

Choose where a DingDong-notification hook listens. A source selector describes the originating work, not the responding target.

## Open this screen

**Desktop:** DingDong notification hook → Other sources or Flow notification hook → Add notification source.

**Mobile:** The same hook editors → Add notification source → source-selection screen.

## Controls

| Control or area | Behavior |
|---|---|
| Source type | Chat, Flow or All activity. |
| Chat → DingDong | Selects an available owned DingDong. |
| All other chat rooms / room checkboxes | Listens to this DingDong in all eligible other chat rooms or selected rooms. |
| Flow → Flow | Selects the originating Flow. |
| All nodes / node checkboxes | Listens to all nodes or selected nodes in that Flow. |
| Assigned DingDong filter | Optionally restricts the selected Flow nodes' events to the chosen assigned DingDong. No filter removes that restriction. |
| Node label | Shows node name and assigned DingDong, or Unassigned. Unassigned is a node label, not the No filter setting. |
| All activity → DingDong | Listens to that DingDong's chat activity and its work as an assigned Flow-node DingDong. |
| Add / Save | Adds the selector to the hook draft. |
| Delete source | Removes one selector from the draft. |
| Cancel / Back | Leaves without adding a selector. |

## Conditions and results

Chat requires a DingDong and selected rooms unless all rooms is chosen. Flow requires a Flow and selected nodes unless All nodes is chosen. All activity requires a DingDong. The hook matches any of its source selectors; adding multiple selectors does not require every source to publish together.

The Chat room selector omits the current responder/current room pair for an AI-response hook; use Current-room responder for that source. An unavailable saved filter must be reselected or cleared. Adding/removing a source edits the hook draft; save the whole hook afterwards.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/notification-sources.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
