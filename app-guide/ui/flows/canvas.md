# Navigate and edit the Flow canvas: screen reference

Arrange the graph and select the object to edit.

## Open this screen

**Desktop:** Flow → a Flow → editor.

**Mobile:** Flow → a Flow → editor → Canvas tools when needed.

## Controls

| Control or area | Behavior |
|---|---|
| Pan / zoom | Moves the viewport or changes magnification. Desktop also accepts Ctrl + plus/equal or minus while the canvas has focus. |
| Center canvas / zoom controls | Mobile Canvas tools help bring the graph back into view. |
| Node selection | Opens task settings. Desktop dragging moves the node; mobile uses a long press followed by dragging. |
| Connection selection | Opens connection settings. |
| Node / Loop / Conn | Desktop toolbar starts node creation, loop creation or connection creation. |
| Contextual toolbar | Desktop selection exposes relevant duplicate, delete, connection-source/target or loop-path actions. |
| Esc | Desktop exits loop-path editing, cancels loop creation or clears the current selection, depending on the active mode. |
| Expand / Collapse toolbar | Changes the desktop toolbar presentation. |
| Desktop inspector's upper boundary | Drag up or down to resize within the available space. This changes panel presentation without saving the graph and is available in read-only views where shown. |
| Add node / Add connection / Loops | Mobile controls open the corresponding editor or list. |
| Dir / Flow direction | Changes graph direction settings. Mobile Canvas tools also offers horizontal/vertical layout. |
| Left-to-right / Right-to-left / Top-to-bottom / Bottom-to-top | Direction-dialog choices for the horizontal and vertical axes. Apply these settings, then save the graph. |
| Clear / Clear all nodes | Confirms removal of all nodes, connections and loops from the draft graph. |
| Save / Save Flow | Persists the current graph draft, including layout changes. |
| Restore saved Flow | Mobile confirms replacement of the draft with the saved graph. |

## Conditions and results

Moving a mobile node or applying a layout changes the draft; it does not automatically save the graph. Cancelling a drag restores that drag's starting position. Canvas layout is separate from changing a connection's source and target.

An active run or a displayed execution report makes graph editing unavailable. For an ended run, use Clear display to return to the editable graph. Clearing the draft graph preserves the Flow itself and is distinct from deleting a Flow.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/canvas.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
