# Connect Flow nodes and choose data propagation: screen reference

Choose execution dependencies and whether a previous result is passed forward.

## Open this screen

**Desktop:** Editor → Conn, a node's source/target action, or select an edge.

**Mobile:** Editor → Add connection, node → Connect from/to node, or select a connection.

## Controls

| Control or area | Behavior |
|---|---|
| Source / Target | Chooses two different nodes. A fixed endpoint is supplied when starting from a node. |
| Previous result / Pass previous result | Makes the downstream task wait for the source and receive its result. |
| Dependency only | Makes the downstream task wait without passing the source's output. |
| Switch direction | Reverses the connection where valid. |
| Replace opposite connection confirmation | Resolves an existing connection in the other direction when switching. |
| Create / Save / Apply | Applies connection settings to the graph draft. |
| Delete / Cancel | Removes the selected connection or abandons connection creation. |

## Conditions and results

Source and target cannot be the same node. Use Self loop for single-node repetition. Duplicate, cyclic or loop-conflicting connections can be rejected.

Connections entering a multi-node loop from outside must enter its start node. A connection required by a loop cannot be reversed or removed without resolving the loop first. Save/Save Flow in the main editor persists accepted connection edits.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/connections.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
