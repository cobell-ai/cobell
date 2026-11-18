# Configure repeated Flow execution: screen reference

Repeat one node or a connected group a configured number of times.

## Open this screen

**Desktop:** Node inspector → Self loop, or toolbar → Loop → self/multi-node loop. Select an existing loop to edit it.

**Mobile:** Node details → Self loop, or editor → Loops → Add/Edit.

## Controls

| Control or area | Behavior |
|---|---|
| Self loop | Repeats only the selected task node. |
| Start node | Starts a multi-node loop. It must have an outgoing path and cannot already use Self loop. |
| End nodes / path selection | Chooses one or more reachable end nodes and the included paths. |
| Iterations | Sets 2–999 repetitions. |
| Sequential / Parallel | Runs iterations in sequence or allows concurrent iterations. |
| Max concurrent iterations | Limits parallel iterations, from 1 to the configured iteration count. |
| External edge propagation | Chooses first-iteration or last-iteration delivery to nodes outside the loop. Available on desktop and mobile. |
| Reset / Cancel / Create loop | Desktop creation controls reset path selection, abandon creation or apply the loop. |
| Edit paths / Done / Cancel | Desktop controls for changing an existing loop's paths. |
| Save loop / Delete loop | Mobile applies loop settings or removes the loop. Deletion preserves its task nodes and connections. |

## Conditions and results

Multi-node loops need valid complete paths from the start to selected ends. Conflicting or overlapping loop assignments are rejected. An existing multi-node loop's start node is fixed; recreate the loop to change it.

Repetition ends at the configured count. External propagation occurs once at the chosen iteration; a multi-node loop waits for its end nodes for that iteration. Loop settings apply to the graph draft and still require Save/Save Flow.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/loops.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
