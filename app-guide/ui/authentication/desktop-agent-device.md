# Manage a desktop agent device: screen reference

Inspect the restricted desktop agent interface and its local device settings.

## Open this screen

**Desktop:** Complete [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-login.md). The agent screen replaces the personal workspace.

For the different mobile controls, see [mobile agent devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md).

## Controls

| Control or area | Behavior |
|---|---|
| Agent-Only Login / name / email | Static account information. Email appears when available; the card does not open Profile. |
| Outer vertical scroll | Reaches settings, local history and Logout in a small window. |
| Title bar / window controls | Uses the shared [desktop window controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/window.md), with maximize offered. Window closure is separate from Logout. |
| Device warning / Retry | A failed or stale device-settings read can show an inline warning. Retry refreshes this agent device's settings. Retained or initial switch values alone are not confirmation of the server state. |
| Allow Toolbox on This Device | Saves permission for Toolbox execution on this agent device. |
| Allow Access to KnowledgeBox Files on This Device | Saves permission to read/write this device's KnowledgeBox files. |
| Share My Device Info | Saves outgoing sharing to your other devices. Receiving device information remains separate. |
| Device switch availability | Requires the current agent session and its device record. Confirm the saved setting before relying on it. |
| Toolbox executions | Scrollable local summary of tool, origin, status, time and duration. Rows and origin text are read-only; they do not open execution details or chat/Flow links. |
| History settings gear | Opens the shared [history-settings dialog](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/history-settings.md). |
| History loading / empty / storage error | Shows the current local-history state. This card has no dedicated Retry button. A storage-error message can appear alongside retained session records. |
| Logout | Requests sign-out directly. Use the current [access-recovery controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/access-recovery.md) if cleanup needs attention. |

## Conditions and results

Change one device setting at a time and confirm its saved state. If the result is uncertain, check the current device settings and use the warning's Retry when offered before relying on the value.

These switches do not select Gear targets or supply OS/runtime capabilities. Use your personal session for [device registration and remote session management](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/device-management.md), tokens and Gear.

The desktop agent screen does not contain the mobile dashboard's Camera/Microphone/Photos/Notifications permission rows, Screen Use row or Sandbox browser control row. Agent sessions do not receive ordinary DingDong OS alerts.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/desktop-agent-device.md) · [Authentication index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

Reviewed: 2026-10-24 (desktop agent screen, local history card and their entry controls). UI labels use the English app language.
