# Inspect local Toolbox execution history

Read local execution records and their recorded origin.

## Start here

**Desktop:** Click the shield icon near the upper-right to open Security.

**Desktop agent session:** Read the scrollable local summary on the [agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/desktop-agent-device.md). Its rows and origins do not open details or conversations. The gear opens History settings; the card has no dedicated Retry. The desktop steps below describe the personal Security screen.

**Mobile personal session:** Fifth bottom tab More → Security, or the Tool history row.

**Mobile agent session:** Scroll Toolbox executions on the [agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-device.md). These summary rows do not open details. Use History settings for retention controls, or Retry in a local storage-error notice. The mobile steps below describe the personal Security screen.

## Desktop steps

1. Open Security with the top-right shield and select Toolbox executions. The first tab is Shell approval.
2. Choose All or a Toolbox chip. Changing the filter returns to the first page. Use Previous/Next for pages of up to 50 records; scroll the table vertically or horizontally as needed.
3. Select a row to open its side panel. Read time, status, duration, any batch item and recorded origin. Select the value text to copy it; origin names do not open chats or Flows.
4. Close the side panel with its Close icon. A detail can remain selected when its row is outside the current filter/page; removing the retained record removes its detail.

## Mobile steps

1. Open More → Security → Toolbox executions. The first tab is Shell approval.
2. Choose All or a Toolbox, including MCP, from the Toolbox / tool dropdown. Changing the filter starts its list at the beginning. Scroll to find a record.
3. Tap a row for Execution details. Read or select its field values to copy them. Chat room, Flow and Node names describe the saved origin; they are not navigation links.
4. Use Back to return, with Security as the fallback. A missing/removed selection can show loading or empty text. Open History settings from the list to change retention.

## Read browser warnings

Expand Shared browser security when shown and review the warnings. Read the time, browser, opener, caller and Gear information, then check the current browser and Gear settings before retrying a refused request.

The warning rows are read-only. Its storage-error text has no dedicated Retry or deletion button. The execution-history storage error has a separate Retry; it does not rerun a tool.

Shared browser security warnings have separate retention from execution history. Do not rely on this warning list as a complete history.

## Completion, limits and recovery

History belongs to this account on this device; it is not the global activity of every device. Detailed tool inputs/results are not recorded in these activity records. Origin unavailable means the execution has no recorded origin metadata; missing names use Unnamed.

Choose All before treating an empty filtered view as no local history. Loading or a storage error can leave retained records visible. Use current-account/current-page controls; a changed history session retires the old mobile detail screen. Mobile Security's Back returns to the previous screen, with More as the fallback.

Also find this under: tool log, security shield, execution details, device audit.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/execution-history.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/README.md)

[Set local execution-history retention](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/history-settings.md)

Reviewed: 2026-10-24 (desktop/mobile personal execution history, mobile details, both browser-warning panels and agent-summary differences). Shell-approval child controls remain separate. UI labels use the English app language.
