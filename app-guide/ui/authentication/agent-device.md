# Manage a mobile agent device: screen reference

Inspect the device after agent sign-in and choose what it may supply or execute.

## Open this screen

**Mobile:** Finish agent sign-in. Agent mode replaces the ordinary personal interface; this dashboard has no normal Back control.

Desktop agent controls differ. See [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-login.md) and [device management](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/device-management.md).

## Controls

| Control or area | Behavior |
|---|---|
| Account / connection | Shows the agent account and this device's Offline, Connecting or Online state. It does not open the personal profile. |
| Logout | Signs out immediately without an extra confirmation. Use child screens' return controls to navigate back to the dashboard. |
| Hosting on this device | Read-only list of apps hosted here with at least one enabled chat share. Check whether an app is serving, connecting, paused or unavailable. Use normal sign-in for the viewer and app management screens. |
| Toolbox executions | Scrollable local summary of tool, origin, time, duration and status. These summary rows do not open execution details. |
| History settings | Opens the agent's history settings. A local history-storage error can offer its own Retry. See [execution history](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/execution-history.md). |
| Camera / Microphone / Photos / Notifications | Each OS permission row shows its current state. Granted rows have a check; an undecided/denied permission offers Allow when requests are supported. Otherwise Settings opens app settings. |
| Permission loading / Retry | A row shows progress while reading. A failed read offers Retry for that capability. |
| Allow / Settings progress | Disables that row's action until it finishes. A failure shows a permission error notice, then the row is read again. Permissions are also rechecked when Cobell resumes. |
| Device settings loading / Retry | Before settings are available, shows progress or a failed-data row with Retry. This Retry refreshes device settings, not the OS permissions. |
| Allow Toolbox on This Device | Saves whether this agent device allows Toolbox execution. |
| Allow Access to KnowledgeBox Files on This Device | Saves whether KnowledgeBox files on this device may be read or written. |
| Share My Device Info | Saves outgoing information sharing with your other devices. Receiving shared information remains separate. |
| Device switch saving / error | The three switches are disabled while a change is pending or settings are unavailable. A failed save can restore the previous values and show Could not update device settings. Inspect the current values before repeating a change. |
| Screen Use | Opens the mobile screen-sharing controls; it does not start sharing by itself. See [screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/screen-sharing.md). |
| Sandbox browser control | Shows disabled, setup-required, connecting, connected, interrupted or unsupported state. Opens agent browser/Booster setup when available; an unsupported row is disabled. See [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/android-booster.md). |

## Conditions and results

This device's switches and OS permissions are separate from the DingDong's Gear targets and available tools. A permission check alone does not establish that a tool can execute.

The Notifications permission row does not enable ordinary DingDong OS delivery in an agent session. Agent sessions remain excluded from that delivery. Use a normal personal session to manage tokens, registration and Gear targets.

Device settings use the current agent session. A failed read or save does not prove the server kept its previous value; inspect the current state before resubmitting. For sign-out cleanup or recovery, use the current [access-recovery controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/access-recovery.md).

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-device.md) · [Authentication index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

Reviewed: 2026-11-19. UI labels use the English app language.
