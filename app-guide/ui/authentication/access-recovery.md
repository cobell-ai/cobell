# Recover account access and finish sign-out: screen reference

Use the recovery state shown by the app before starting another session.

## Open this screen

**Desktop:** Social sign-in can show pending account deletion/restoration. Credential cleanup can also appear after sign-out.

**Mobile:** The app shows account-deletion recovery, credential cleanup or sign-out finalization when required.

## Controls

| Control or area | Behavior |
|---|---|
| Requested date / recovery deadline | Shows deletion timing where available. |
| Cancel deletion and sign in | Requests restoration while cancellation is still allowed. |
| Continue recovery | Mobile resumes/checks a restoration already in progress. Desktop can continue the shown restoration automatically. |
| Close / Back to login | Leaves recovery without issuing a new deletion cancellation. It does not undo restoration already requested. |
| Recovery period expired | No deletion-cancellation or account sign-in action is offered. |
| Try cleanup again | Retries removal of the previous saved credential. |
| Try again | Mobile retries failed sign-out finalization. |

## Conditions and results

Account deletion has a 30-day recovery period; use the displayed deadline and current recovery status. Restoration can take more than one step. Wait for access to be restored rather than treating the cancellation button as completed sign-in.

Credential cleanup and session finalization can block new sign-in. Keep the app open while progressing and use the offered retry after failure. Closing a recovery screen does not establish that credentials were removed or account access restored.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/access-recovery.md) · [Area index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
