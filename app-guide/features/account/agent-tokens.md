# Create and manage agent sign-in tokens

## Start here

**Desktop:** Profile → Agent Sign-in Token.

**Mobile:** Home profile header or More profile card → Profile → Agent Sign-in Token Management.

## Create and save a token

1. Open token management, refresh a failed read and review active/retained capacity.
2. Choose Generate New Token/Create token.
3. Enter a 1–40-character display label. Spaces are allowed; obey the field's character restrictions.
4. Select 30, 90 or 240 days, one or two calendar years, or a custom date. Desktop defaults to 90 days; mobile requires a choice.
5. For a custom date, use the calendar or localized date input, then confirm. Read the resolved expiry and generate.
6. In the one-time result, use Copy to Clipboard/Copy token or Download as File/Save as file. Wait for success; retry a failed export before closing.
7. Choose Confirm/Done. The list keeps token metadata, not a retrievable copy of the secret.

## Manage access

Refresh the list and inspect the intended token's state. Revoke stops active or plan-paused access permanently. Reactivate resumes an eligible plan-paused token using an available active slot, with the same secret and expiry. Delete permanently invalidates a token and releases retained capacity. Each action requires confirmation; Cancel abandons it.

## Leave an unfinished form

Desktop Cancel leaves creation. Mobile Back asks before discarding an edited name or expiration; Cancel keeps editing. The one-time result instead uses Confirm/Done, so copy or save the secret before leaving it.

## Conditions and recovery

Only personal sessions manage tokens. The creation limit uses retained tokens, including revoked and expired ones; delete a retained token to free capacity. Active access and retained capacity are different counts. Increasing a plan does not automatically reactivate a plan-paused token.

The result is shown only once. After Confirm/Done closes it, the secret cannot be reopened from the token list. A copied token or saved file remains outside the result view; keep it private. A text-selection Copy can copy only the selected characters, so use the dedicated copy button for the whole token.

If copying or saving fails, retry while the result is still open. Cancelling the file picker does not save a file. After a failed create or management operation, inspect the refreshed list before trying again; a read failure does not establish that no token was created or changed.

Revoking or deleting a token stops its associated agent sessions. Reactivation applies to eligible plan-paused tokens with active capacity available; it keeps their existing secret and expiry. A revoked or deleted token cannot be reactivated. Token validity is limited to two calendar years, not an unlimited lifetime.

## Related guides

[Paired guide](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/agent-tokens.md) · [Agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
