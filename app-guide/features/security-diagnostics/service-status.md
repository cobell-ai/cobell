# Check connections and unavailable features

Distinguish a connection problem from missing configuration or unsupported functionality.

## Start here

**Desktop:** Click an issue notice in the main top bar. A reconnecting/checking indicator without an issue is not clickable. Startup failures have their own status screen.

**Mobile:** Fifth bottom tab More → Service status, or tap the status summary above the bottom tabs.

## Desktop steps

1. Open the issue notice in the top bar. When space is narrow, hover its icon to read the summary.
2. Scroll the affected-source rows and read the affected features, failure time and recovery state. The rows are read-only.
3. Use Retry when offered. It starts available checks and closes the dialog immediately.
4. Reopen the notice or inspect the affected feature to check the result. Closing the dialog does not mean recovery succeeded. Close or ordinary dismissal leaves without starting Retry.

## Mobile steps

1. Open More → Service status or tap the bottom status summary.
2. Read Chat and Device tools connection cards. An unavailable connection can offer Retry; pending checks show Retrying… and disable the action.
3. Read any information cards. A read failure reloads information; a card saying a change needs checking refreshes the saved result without repeating that change. Browser status-sync checks current browser status without repeating browser actions.
4. Retry one eligible card, or use Retry unavailable items to start the available checks. The combined control is disabled while recovery is pending or unavailable.
5. Inspect the affected feature after recovery. Use Back to return, with More as the fallback.

## Completion, limits and recovery

The app reconnects after interruptions. Cached data can remain visible during recovery. A disconnected Device tools stream is different from a disabled Gear capability, while a data-load failure is not an empty collection.

No active connections for this session. is an empty-status message, not a health check for every service. The mobile summary can be hidden or delayed; its absence does not prove an earlier change succeeded.

An uncertain room hide/leave result uses its own [chat-directory recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/directory.md). Other feature-specific result checks also remain separate. Use current controls after an account or page change; stale recovery controls can stop accepting actions.

Startup maintenance uses its own View detailed status/Check again controls. A required-update notice can replace the desktop status slot; follow the [update guide](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/updates.md) when shown.

Also find this under: offline, reconnect, service unavailable, stale data, connection.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/service-status.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/README.md)

[Review and send diagnostics](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/diagnostics.md) · [Check and apply an app update](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/updates.md)

Reviewed: 2026-10-24 (desktop status notice/dialog; mobile status summary, connection and information cards). UI labels use the English app language.
