# Inspect local Toolbox execution history: screen reference

Read local execution records and their recorded origin.

## Open this screen

**Desktop:** Click the shield icon near the upper-right → Security → Toolbox executions tab.

**Desktop agent session:** The [agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/desktop-agent-device.md) embeds a scrollable, read-only summary. Its rows and origin text do not open details or chat/Flow links. The settings gear opens History settings. Loading, empty and storage-error text can appear; this card has no dedicated Retry.

**Mobile personal session:** Fifth bottom tab More → Security → Toolbox executions tab, or the Tool history row.

**Mobile agent session:** The [agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md) embeds a scrollable Toolbox executions summary. Its rows do not open details; use History settings for retention controls and the storage-error Retry when offered. The personal Security screen's row/detail controls below do not apply to that summary.

## Controls

| Control or area | Location and behavior |
|---|---|
| Security tabs | Shell approval is first; Toolbox executions is second. See [shell approvals](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/shell-approval.md) for that child panel's actions. |
| Toolbox executions / list | Shows local execution records. |
| Toolbox filter | Desktop uses All/Toolbox chips; changing the filter returns to the first page. Mobile uses the Toolbox / tool dropdown, including All and MCP; changing it starts the filtered list at the beginning. |
| Browser security warning panel | Expands recorded browser warnings or their storage error when present. See the warning-panel section below. |
| Execution row | Desktop selects the row and shows a side panel. Mobile personal history opens a separate Execution details screen. Agent summaries remain read-only. |
| Time / status / duration / batch item | Describes the recorded operation. |
| DingDong / Chat room / Flow / Node | Recorded origin names in the details, not navigation links. Select the value text to copy it. Empty names show Unnamed. |
| Previous / Next page | Desktop shows up to 50 filtered records per page; boundary buttons are disabled. The table scrolls vertically and horizontally. Mobile uses a scrollable list without these page buttons. |
| Details Close / Back | Desktop Close clears the side-panel selection. Mobile Back returns to the previous screen, with Security as the fallback. |
| History settings | Opens local retention controls. |
| Retry | Retries local storage or read failures. |

## Execution details

Both layouts show local execution time, status, duration, tool and DingDong name. Chat room is shown for a recorded chat origin; Flow and Node are shown for a Flow origin. Batch item appears when batch information is recorded. These fields are selectable text.

The desktop selected detail can remain visible when a different filter or page hides its row; Close clears it. If the record is no longer retained, its detail disappears. On mobile, a missing record or a screen opened without a current row selection shows loading or empty text. A changed history session retires the old mobile detail screen.

## Browser security warning panel

Expand Shared browser security when shown and scroll the warning list. Review each warning's time, browser, opener, caller and Gear information. Check the current browser and Gear settings before retrying a refused request.

Warning rows are read-only. A warning-history storage error is text in this panel; it has no dedicated Retry or delete control. This warning history is separate from the execution-history storage warning and its Retry.

Shared browser security warnings have separate retention from execution history. Do not rely on this warning list as a complete history.

## Conditions and results

History belongs to this account on this device; it is not the global activity of every device. Detailed tool inputs/results are not recorded in these activity records. Origin unavailable means the execution has no recorded origin metadata.

An empty list can mean no records match the current Toolbox filter; choose All to check the full local list. Loading or a storage error can coexist with retained records. Retry does not rerun the recorded tool. Mobile Security's Back returns to the previous screen, with More as the fallback; use controls from the current account and screen.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/execution-history.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/README.md)

[Set local execution-history retention](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/history-settings.md)

Reviewed: 2026-10-24 (desktop/mobile personal execution history, mobile details, both browser-warning panels and agent-summary differences). Shell-approval child controls remain separate. UI labels use the English app language.
