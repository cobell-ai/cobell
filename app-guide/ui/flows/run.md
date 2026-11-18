# Run and control a Flow: screen reference

Start a saved graph and control the selected execution.

## Open this screen

**Desktop:** Flow editor → Run Flow or the Flow's run control.

**Mobile:** Flow row menu → Run Flow, or the editor's run action → run sheet.

## Controls

| Control or area | Behavior |
|---|---|
| Run Flow / cobell button | Requests execution. Opening the mobile run sheet alone does not start it. |
| Interrupt / pause | Pauses active work through the bot run controls. |
| Resume | Opens resumption controls; optional guidance can be supplied. |
| Terminate / stop | Ends the run through the available run controls. |
| Queue badge | Opens pending requests and their cancellation controls. |
| Execution banner | Shows pending, running, paused, stopped, error or completion/report-writing state. |
| Node status / outcome | Shows each node's recorded work and loop iteration information. |
| Run preview | Desktop's execution-preview strip clears the current object selection to show the run preview in the inspector. |
| Execution history | Mobile execution banner opens the displayed run's recorded details. |
| Notices | Opens observations for the run or selected node. |
| Retry | Retries a failed execution-state read. |
| Clear display | Available for an ended displayed run; returns to the current editable graph without deleting execution history. |

## Conditions and results

Save graph changes and complete all task DingDong/Gear assignments before starting. Feature/session availability and saving state can disable run controls.

While an execution or its report is displayed, the canvas shows a read-only execution graph. A completed report keeps editing locked until Clear display. Final-report writing is a separate stage after node work; a failed final report does not erase node outcomes. A disconnection notice describes state-reading connectivity and is not proof that remote work stopped.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/run.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
