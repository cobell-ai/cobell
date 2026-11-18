# Validate and save a Flow: screen reference

Distinguish graph integrity, execution readiness and persistence.

## Open this screen

**Desktop:** Editor → Save; load-time integrity problems open Flow data integrity check.

**Mobile:** Editor → Validate flow; structural problems can also be shown when saving.

## Controls

| Control or area | Behavior |
|---|---|
| Flow data integrity check / Detailed log | Desktop reports integrity problems and expands supporting details. |
| Show/Hide details / Confirm | Desktop toggles the detailed integrity log or closes the dialog. |
| Flow validation / issue list | Mobile identifies invalid graph relationships and, for execution validation, missing task assignments. |
| Done | Closes the mobile validation result. Issue entries are explanatory and do not open node editors. |
| Save / Save Flow | Persists the main editor's graph draft. An inspector's Apply/Save only resolves that inspector draft first. |
| Restore saved Flow | Mobile confirms replacement of unsaved changes with the saved graph. |
| Stay / Discard / Save | Mobile leaving confirmation keeps editing, abandons changes or saves before leaving. |
| Retry | Retries a failed graph load. |

## Conditions and results

Graph saving checks structural integrity. An incomplete execution assignment can remain in a saved graph; it must be completed before running. Unsaved graph changes block execution.

A successful structural check does not confirm Browser login, file permissions, external-service availability or eligible device-tool execution. Save failure is not a successful graph update. Mobile retains edits after a save failure so they can be retried.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/validation.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
