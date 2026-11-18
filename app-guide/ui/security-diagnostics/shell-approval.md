# Shell approval: screen reference

**Desktop:** Security shield → Shell approval tab, or a Shell approval card in the originating chat. **Mobile:** More → Security → Shell approval, or the request's chat card. Only the owner using normal sign-in can decide.

| Control or area | Behavior |
|---|---|
| Origin, device, purpose and command | Identifies the run, execution device and requested commands. A known device name includes its ID; otherwise the ID is shown. Commands are selectable text. |
| Answer by / Wait until you answer | Shows whether the pending request has a deadline. |
| Allow once | Immediately submits a one-time decision for the presented request; there is no extra confirmation. |
| Allow for 5 / 15 / 60 min | Creates timed access for this run on this device. |
| Custom duration (minutes) → Allow / keyboard submit | Digits only, at most four characters; accepts a whole number from 1 to 1440. Invalid input shows a field error. Correct it and submit again; editing alone does not clear that error. |
| Deny | Rejects the pending request. |
| Access expires at / Revoke timed access | Shows expiry or revokes an active grant. |
| Pending approvals / Active timed access | The scrollable account-wide panel puts pending requests before active timed grants. Resolved requests without an active grant leave this list; the originating chat card can retain their status. |
| Approval badge / tooltip | Counts pending requests only. Zero hides the badge; active timed access alone is not counted. An exclamation mark and unavailable tooltip indicate a failed approval read. |
| Loading / read failure | Loading replaces the list with progress. A failed read shows the unavailable message and Refresh, which reloads that list. |
| Decision progress / failure | Shows a progress bar during submission. Pending-choice buttons and custom input are disabled during submission, after a submission failure, or once the response deadline passes. |
| Card Refresh after a failed decision | Reads the current request without repeating the decision. Check the returned status before choosing again. |
| Revoke timed access availability | Offered only for an unexpired timed grant and disabled while submitting. It can remain available after a failed revoke; refresh the current state before another attempt. |
| Status | Distinguishes pending, approved, denied, timed out without execution, cancelled, revoked and expired. Execution dispatched is a separate notice. |

Timed access applies to the current run and execution device, not every DingDong or device. Other tool permissions remain separate. Revoking access does not stop a command already started; commands dispatched before expiry may finish. Approval is separate from proof that execution completed.

Dates use local time. A submission error alone does not establish whether the decision was accepted. Refresh checks its current state; it does not undo an accepted decision or stop a command already dispatched.

Use the request owner's current normal account and Shell approval tab. Refresh after changing accounts or returning to the page. Leaving does not cancel a decision already sent. Other owners and agent sessions cannot approve it.

**Timeout setting:** In the Gear's KnowledgeBox Use configuration, Continue after approval timeout and Approval timeout (seconds) accept 1–86400 seconds. When enabled, a timed-out command is not executed and the DingDong can continue within existing permissions. Turning it off keeps waiting.

The seconds field accepts up to five digits. Enable the timeout switch, enter a valid duration and save the configuration. Follow any field error; controls may be unavailable when the configuration cannot be edited.

[Approval steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/shell-approval.md) · [Local execution history](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/execution-history.md)

Reviewed: 2026-10-24 (desktop/mobile approval cards, account lists, badges and timeout-setting widget; larger callers and server enforcement remain separate). Labels use the English app language.
