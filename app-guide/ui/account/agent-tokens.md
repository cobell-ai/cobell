# Create and manage agent sign-in tokens: screen reference

## Open this screen

**Desktop:** Profile → Agent Sign-in Token.

**Mobile:** Home profile header or More profile card → Profile → Agent Sign-in Token Management.

## List controls

| Control or area | Behavior |
|---|---|
| Refresh / read Retry | Reloads token states and allowance. Mobile also supports pull to refresh and refresh on app resume. |
| Usage and status | Shows active/retained allowance information and token name, created/expiry dates, and Active, Paused by plan, Revoked or Expired status. |
| Generate New Token / Create token | Opens creation when retained capacity permits. |
| Reactivate | Offered for plan-paused tokens. Requires confirmation and available active capacity. Mobile disables it when the active count is full. |
| Revoke | Offered for active or plan-paused tokens. Requires confirmation; Cancel keeps access unchanged. Revocation cannot be undone by Reactivate. |
| Delete | Requires confirmation, permanently invalidates the token and releases its retained slot. Cancel keeps it. |
| Close / Back | Leaves token management. |

## Creation controls

| Control or area | Behavior |
|---|---|
| Token Name | A 1–40-character display label. Spaces and permitted punctuation are allowed; this is not the account nickname rule. Keyboard submit can generate after validation. |
| Expiration | Chooses 30, 90 or 240 days, one or two calendar years, or a custom date. Desktop initially selects 90 days; mobile requires a selection. |
| Desktop expiration picker / mobile radio options | Changes the expiration draft. The form displays the resolved expiry. |
| Custom date | Opens a calendar/date-input view within today and the two-year maximum. |
| Calendar month/year/day | Changes the selected date within the range. |
| Calendar/input mode icon | Switches to localized date entry or back to calendar. Invalid format/out-of-range input must be corrected. |
| Date OK / keyboard Done / Cancel | Confirms a valid date or leaves it unchanged. Custom expiry uses the local end of the selected day, capped by the two-year maximum. |
| Confirm / Create token | Validates name, future expiry and capacity, then generates. Blocks repeat submission while busy. |
| Desktop Cancel / mobile Back | Leaves creation. Mobile asks before discarding a changed name or expiration; Cancel keeps the draft. Leaving is blocked while generating. |

Names reject double quotes, path separators, angle brackets, the vertical bar, and control/invisible formatting characters. Read the field's validation message before retrying.

## One-time result controls

| Control or area | Behavior |
|---|---|
| Secret display / text selection | Shows the newly generated token. Select all/selection Copy can copy text while this result is open. |
| Copy to Clipboard / Copy token | Copies the whole token. The copied indicator confirms the copy operation, not a successful agent login. |
| Download as File / Save as file | Opens the platform file picker to save the token as text. Cancelling the picker leaves it unsaved. |
| Export error | Keeps the result available for another copy/save attempt. |
| Confirm / Done | Closes the one-time result. Save or copy first if the token is needed. Disabled while an export is busy. |

## Conditions and recovery

Only personal sessions manage tokens. The creation limit uses retained tokens, including revoked and expired ones; delete a retained token to free capacity. Active access and retained capacity are different counts. Increasing a plan does not automatically reactivate a plan-paused token.

The result is shown only once. After Confirm/Done closes it, the secret cannot be reopened from the token list. A copied token or saved file remains outside the result view; keep it private. A text-selection Copy can copy only the selected characters, so use the dedicated copy button for the whole token.

If copying or saving fails, retry while the result is still open. Cancelling the file picker does not save a file. After a failed create or management operation, inspect the refreshed list before trying again; a read failure does not establish that no token was created or changed.

Revoking or deleting a token stops its associated agent sessions. Reactivation applies to eligible plan-paused tokens with active capacity available; it keeps their existing secret and expiry. A revoked or deleted token cannot be reactivated. Token validity is limited to two calendar years, not an unlimited lifetime.

## Related guides

[Paired guide](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/agent-tokens.md) · [Agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-login.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
