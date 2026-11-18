# Sign in as a device agent

Connect an additional device for permitted tools without opening the normal personal interface.

## Start here

**Desktop:** On login select Agent-dedicated Login.

**Mobile:** On login select Sign in as an agent.

## Desktop steps

1. Open Agent-dedicated Login.
2. Choose agent Google/Apple login or enter a valid token and choose Login with Token.
3. Inspect the account and local switches in the [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/desktop-agent-device.md).
4. Use a personal session for registration, tokens and Gear execution targets.

Desktop agent sign-in does not support Auto Login on Windows, macOS or Linux. Fully quitting and reopening the desktop app requires agent sign-in again, whether using Google, Apple or an agent token. The normal sign-in Auto Login preference does not apply.

## Mobile steps

1. Tap Sign in as an agent.
2. Choose an agent social login, or enter the token and tap Sign in with token.
3. Check the agent screen’s connection state.
4. Use the [agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-device.md) for this device's OS permissions, sharing switches and execution summary. Use a personal session for registration, tokens and Gear targets.

Mobile restores valid agent sessions when the app is reopened. It has no Auto Login switch.

## CLI steps

Use `cobell agent --token-file PATH` for the CLI agent server. Use `cobell login --agent-token-file PATH` for explicit token sign-in. Keep the token in the local file rather than command history.

These commands use the supplied token file. The desktop login screen's Auto Login preference does not control them.

## Completion, limits and recovery

An agent session is not an ordinary chatting/account-management session. Its availability depends on your token and device entitlement. Agent devices do not receive ordinary DingDong OS notifications. Never paste a secret token into a public chat.

Also find this under: agent device, CAS token, multi-device, remote tools.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-login.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/README.md)

[Create and manage agent sign-in tokens](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/agent-tokens.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

Reviewed: 2026-11-11 (desktop and mobile session retention). UI labels use the English app language.
