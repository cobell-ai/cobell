# Sign in using another signed-in device: screen reference

Approve a new device from a Cobell app that is already signed in.

## Open this screen

**Desktop:** On the new device use Sign in with a verification code; on the approving device use Profile → Approve sign-in with a verification code.

**Mobile:** Use the same two entry points: login verification-code action, and Profile’s approval row.

## Controls

| Control or area | Location and behavior |
|---|---|
| Verification code on new device | Shows the temporary code and waiting state. |
| Verification code on approving device | Enter the code, then Check device. |
| Device summary | Review the requested device before approving. |
| Approve login / Deny | Accept or refuse that request. |
| Retry | Reloads failed approval data where offered; retrying does not approve the device. |
| Requesting-device Cancel | Ends that pending sign-in attempt. |
| Approving-device Cancel / Close | Desktop closes the approval view without deciding. Mobile Cancel after inspection clears the preview for code entry; Back leaves the screen. |

## Conditions and results

The code has 10 letters/numbers displayed as two groups of five, such as ABCDE-23456. Copy the displayed code, including letters; the approval input normalizes its separator and case. Normal login permits one desktop and one mobile session; approving another device of the same type signs out the previous normal session. Expired codes require a new attempt on the requesting device. Approve only the login you initiated.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

[Resolve a login conflict or device limit](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/session-conflict.md)

Reviewed: 2026-10-23. UI labels use the English app language.
