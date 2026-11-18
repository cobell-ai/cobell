# Sign in with Google or Apple

## Sign in

1. Open the normal sign-in screen. Use Language first if needed.
2. On Windows/Linux, choose whether Auto Login should retain this normal session between app starts. macOS and mobile retain normal sessions without this switch.
3. Choose Google or Apple and complete provider authorization for the intended account.
4. If registration is requested, enter a nickname and accept the required agreements.
5. Resolve any displayed session conflict or device-limit recovery, then wait for the personal main interface.

## Session retention

Windows/Linux Auto Login applies only to normal sign-in. With it off, fully quitting and reopening the app requires normal sign-in again. macOS and mobile retain normal sessions without an opt-out switch. Use explicit Logout/Sign out to end a session.

Desktop [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md) does not support Auto Login, including on macOS. Fully quitting the desktop app requires agent sign-in again. Mobile also restores valid agent sessions when reopened.

## Retry or cancel

During desktop browser authorization, Reopen browser opens the pending attempt again. The mobile waiting view offers provider retry and Cancel sign-in. Cancellation is available while waiting, not while final processing is already underway.

After timeout or cancellation, start sign-in again. Use the app's resulting state to confirm success. For device approval, use [verification-code sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md). For an additional tool device, use [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md).

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/sign-in.md) · [Area index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/README.md)

Reviewed: 2026-11-11 (normal and agent session retention). UI labels use the English app language.
