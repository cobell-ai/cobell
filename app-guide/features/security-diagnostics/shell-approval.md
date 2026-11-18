# Review a requested shell command

1. Use the owner's normal sign-in. Open the request card in its chat, or desktop Security shield / mobile More → Security → Shell approval.
2. Read the origin, execution device, purpose and each command. Unrestricted shell execution can run code and change files accessible to Cobell.
3. Choose Allow once, Deny or timed access for 5, 15 or 60 minutes. Choices submit immediately without another confirmation. For another duration, enter 1–1440 whole minutes, then choose Allow or submit from the keyboard. The field accepts at most four digits; correct invalid input and submit again to clear its error.
4. Wait for submission to finish and read the current status. If controls are unavailable or the response period has ended, refresh the request before deciding what to do next.
5. If a read or decision fails, use the offered Refresh and inspect the current status before choosing again. Refresh does not repeat or undo the earlier decision. A submission error alone does not show whether it was accepted.
6. Review active timed grants in the same Security tab. Revoke timed access when no longer needed. It is offered only before expiry and disabled during submission; if revocation fails, refresh before another attempt.

Timed access is limited to this run on this device. It does not authorize other runs, devices or tool permissions. Revocation and expiry prevent further use of the grant; they do not stop already dispatched commands. Check [execution history](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/execution-history.md) separately for execution status.

The Security list shows pending requests followed by active grants; it is not a history of every decision. Finished requests without active timed access leave this list, while their chat cards can retain status. The badge counts pending requests only; active grants do not add to it, and an exclamation mark indicates unavailable approval data.

Use the request owner's current normal account and Shell approval tab. After changing accounts or returning to the page, refresh the request before acting. Leaving the page does not cancel a decision already sent. Other owners and agent sessions cannot approve it.

## Set how long requests wait

Open the Gear's KnowledgeBox Use configuration on desktop or mobile. Continue after approval timeout enables a deadline of 1–86400 seconds. If it expires unanswered, the command is not executed and the DingDong can continue within its existing permissions. Disable the setting to keep waiting for an answer. Save the Gear configuration.

Enter up to five digits in Approval timeout (seconds). Enable the switch to edit the duration and correct any field error. Save the configuration to apply the setting.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/shell-approval.md) · [KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md)

Reviewed: 2026-10-24 (desktop/mobile approval cards, lists, badges and timeout-setting widget; larger callers and server enforcement remain separate).
