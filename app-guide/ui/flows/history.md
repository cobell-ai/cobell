# Read Flow execution history and notices: screen reference

Inspect recorded runs and observations without changing the current Flow.

## Open this screen

**Desktop:** Flow row/editor → Execution history; execution banner or node → Notices.

**Mobile:** Flow row menu/editor → Execution history; run or node details → Events/Notices.

## Controls

| Control or area | Behavior |
|---|---|
| Run list | Shows recorded runs, their times/status and available summary counts. |
| New / latest / today summaries | Helps distinguish recent records; summaries are not run controls. |
| Manual / hook / scheduled counts | Summarizes recorded trigger origins where shown. |
| Older records | Loads older runs as history pagination is requested, including scrolling where supported. |
| Refresh / Retry | Mobile history refreshes recorded runs; retry controls reload failed initial or older-page reads. |
| Run selection | Opens the saved execution, final output/report state and node outcomes. |
| Nodes / Connections / Loops / Events | Mobile detail views inspect that run's recorded graph and events. |
| Notices / node notices | Opens observations for the selected execution or node. |
| Load more / Retry | Fetches additional notices or retries failed reads. |
| New observations | Desktop returns to newer observations when the list is scrolled away from the live tail. |
| Close / Back | Leaves the recorded view. |

## Conditions and results

A recorded graph is a snapshot, not an editable copy of the latest Flow. Opening history does not start a run. Missing final output can reflect an unfinished or failed final report; inspect node outcomes and notices. These records differ from a notification's trigger history, which only records triggered targets and conditions.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/history.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
