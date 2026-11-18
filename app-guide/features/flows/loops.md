# Configure repeated Flow execution

## Repeat a single task

Open the node inspector, enable Self loop and set 2–999 iterations. Choose sequential or parallel execution. For parallel execution, set the maximum concurrent iterations. Choose whether external connections receive output from the first or last iteration, then apply the node settings.

## Repeat a path of tasks

1. Open Loop on desktop or Loops → Add on mobile.
2. Select a start node with an outgoing path and no Self loop.
3. Select reachable end nodes and valid paths between them.
4. Set iterations, execution mode, concurrency and external propagation.
5. Create/Save the loop, then Save/Save Flow in the main editor.

## Edit or remove

Select a loop to change its paths or repetition settings. On desktop, use Done or Cancel to finish path editing. The start node cannot be changed in place; remove and recreate the loop for a different start. Deleting a loop preserves its nodes and connections.

## Completion and recovery

Resolve overlap or path errors before saving. Incoming connections from outside a loop must target its start node. First/last propagation selects one iteration's external delivery; it does not send output outside the loop after every iteration.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/loops.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
