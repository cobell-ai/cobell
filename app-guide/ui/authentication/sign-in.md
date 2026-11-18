# Sign in with Google or Apple: screen reference

Open a normal personal Cobell session with a social account.

## Open this screen

**Desktop:** Cobell login window.

**Mobile:** Cobell login screen → normal personal sign-in.

## Controls

| Control or area | Behavior |
|---|---|
| Login with Google / Apple; Continue with Google / Apple | Starts normal provider authorization. |
| Auto Login | Windows/Linux normal sign-in only. Retains the normal session between app starts; with it off, sign in again after fully quitting the app. Both the checkbox and its label toggle the preference. |
| Language | Changes interface language before sign-in. |
| Terms / Privacy | Opens the legal reader. |
| Sign in with a verification code | Starts approval from another already signed-in device. |
| Agent-dedicated Login / Sign in as an agent | Opens agent-mode social/token sign-in. |
| Reopen browser | Desktop waiting screen reopens the pending authorization in a browser. |
| Try again / provider retry | Mobile waiting screen retries the pending provider authorization. |
| Cancel sign-in / Back | Cancels pending authorization while waiting. Finishing sign-in can temporarily disable cancellation. |

## Conditions and results

macOS and mobile retain normal sessions and do not offer the Auto Login opt-out. Explicit logout ends the session. Closing or hiding a window while Cobell keeps running is different from fully quitting.

Desktop [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-login.md) has no Auto Login switch and does not use the normal sign-in preference on Windows, macOS or Linux. Fully quitting and reopening the desktop app requires agent sign-in again. Mobile restores valid normal and agent sessions when reopened.

Provider authorization, account registration, session conflicts and device recovery can be successive stages. Wait for the main personal interface. Returning from a browser alone does not prove sign-in succeeded. Timed-out or cancelled attempts require another sign-in attempt.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/sign-in.md) · [Area index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

Reviewed: 2026-11-11 (normal and agent session retention). UI labels use the English app language.
