# Sign in as a device agent: screen reference

Connect an additional device for permitted tools without opening the normal personal interface.

## Open this screen

**Desktop:** On login select Agent-dedicated Login.

**Mobile:** On login select Sign in as an agent.

## Controls

| Control or area | Location and behavior |
|---|---|
| Agent Google / Apple buttons | Starts provider sign-in with agent mode selected. |
| Desktop Auto Login | Not offered for agent sign-in. The normal sign-in preference does not apply. |
| Token input | Enter a Cobell Agent sign-in token. |
| Login with Token / Sign in with token / Enter | Submits the token after local format validation. |
| Mobile Show token / Hide token | Controls only input visibility. |
| Back to Normal Login / Personal sign-in | Returns to normal account sign-in. |
| Mobile Agent mode | Opens the [agent device dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md): connection, OS permissions, sharing switches and local execution summary. |
| Desktop Agent-Only Login | Opens the restricted [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/desktop-agent-device.md): device switches and read-only local execution summary. |

## CLI

Use `cobell agent --token-file PATH` for the CLI agent server. Use `cobell login --agent-token-file PATH` for explicit token sign-in. Keep the token in the local file rather than command history.

These commands use the supplied token file. The desktop login screen's Auto Login preference does not control them.

## Conditions and results

Desktop agent sign-in does not support Auto Login on Windows, macOS or Linux. After fully quitting and reopening the app, sign in as an agent again with Google, Apple or an agent token. Closing or hiding a window while Cobell keeps running is different from fully quitting.

Mobile restores valid agent sessions when reopened and has no Auto Login switch. Explicit Logout ends the session.

Agent sign-in has no separate concurrent-session limit. The plan's registered-device limit applies across normal and agent sign-ins. Token sign-in requires an active, unexpired token.

Use normal sign-in for ordinary chats and account management. Agent devices do not receive ordinary DingDong OS notifications. Never paste a secret token into a public chat.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

[Create and manage agent sign-in tokens](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/agent-tokens.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

Reviewed: 2026-11-11 (desktop and mobile session retention). UI labels use the English app language.
