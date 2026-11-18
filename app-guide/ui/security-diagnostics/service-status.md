# Check connections and unavailable features: screen reference

Distinguish a connection problem from missing configuration or unsupported functionality.

## Open this screen

**Desktop:** Click an issue notice in the main top bar. A reconnecting/checking indicator without an issue is not clickable. In a narrow slot, hover the icon to read its tooltip. Startup failures have their own status screen.

**Mobile:** Fifth bottom tab More → Service status, or tap the status summary above the bottom tabs.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop issue notice | Opens the Service status dialog. An issue or required-update notice can replace the top-bar Cobelly input; a required update takes priority. |
| Desktop issue rows | Scrollable, read-only affected-source/feature, failure-time and recovery information. Rows do not have individual Retry buttons. |
| Desktop Retry | Offered when there are retryable issues. Starts the available checks and closes the dialog immediately; closing is not a success result. Reopen the notice or inspect the affected feature. |
| Desktop Close / dismiss | Closes the dialog without starting its Retry action. |
| Mobile warning above tabs | Opens this screen while the warning and session are current. It does not retry anything by itself. |
| Mobile connection cards | Chat and Device tools can show Connected, Waiting for connection, Reconnecting, Checking connection or Connection unavailable. Last failure is shown when known. |
| Mobile connection Retry | Appears for an unavailable connection. While pending, shows Retrying… and disables the button. It can also be disabled when recovery is not currently allowed. |
| Mobile unavailable-information cards | Identify the affected information and last failure. Each has its own Retry, disabled while pending or when recovery is unavailable. |
| Mobile Retry unavailable items | Offered when there are eligible connection checks or information issues. It starts those checks; the button is disabled while recovery is pending or unavailable. |
| Mobile Back | Returns to the previous screen, with More as the fallback. |
| Mobile No active connections for this session. | An empty-status message, not confirmation that every service is healthy. |

## Conditions and results

The app reconnects after interruptions. Cached data can remain visible during recovery. A disconnected Device tools stream is different from a disabled Gear capability, while a data-load failure is not an empty collection.

On mobile, a failed-read card asks to reload information. A card saying a change needs checking refreshes the saved result rather than repeating that change. Browser status-sync guidance checks current browser status without repeating browser actions. Read the card before using Retry.

Service status does not replace a feature's own result-check or recovery controls. For example, a room's uncertain hide/leave result uses its [chat-directory recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/directory.md). An error or the absence of a status warning alone does not establish whether an earlier change took effect.

Use controls from the current session and page. A stale notice or a control covered by another route can stop accepting actions. Startup maintenance controls such as View detailed status and Check again belong to the startup screen, not these signed-in status cards.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/service-status.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/README.md)

[Review and send diagnostics](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/diagnostics.md) · [Check and apply an app update](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/updates.md)

Reviewed: 2026-10-24 (desktop status notice/dialog; mobile status summary, connection and information cards). UI labels use the English app language.
