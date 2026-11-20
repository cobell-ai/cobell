# Manage a mobile agent device

Configure this device after agent sign-in, then choose its execution targets from your personal app.

## Start here

**Mobile:** Complete [agent sign-in](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md). The Agent mode dashboard replaces the personal Home and bottom tabs.

## Steps

1. Check the account and connection label. Connecting and Online are device connection states, not proof that a particular tool has completed.
2. Inspect Camera, Microphone, Photos and Notifications. Use Allow when offered, or Settings for permissions that must be changed in app settings. Wait for the row's progress and return to Cobell to recheck it. A failed permission read has its own Retry.
3. Wait for device settings to load. If they fail before any settings are available, use that row's Retry.
4. Choose Allow Toolbox on This Device, Allow Access to KnowledgeBox Files on This Device and Share My Device Info as needed. Changes save immediately and disable the three switches while pending. Check current values and any save error; a failed change can restore the old values.
5. For a screen-sharing session, open Screen Use and use its destination controls. For supported browser execution, open Sandbox browser control and finish the offered Booster setup.
6. Scroll the embedded Toolbox executions summary to inspect local activity. Its rows do not open details. History settings opens the agent's settings; Retry in a storage-error notice retries history access.
7. Use Logout to request sign-out. This has no extra confirmation; ordinary Back does not leave the dashboard. Resolve any offered sign-out recovery before starting another session.

## Hosting static apps

DingDong can select a KnowledgeBox folder, register it and enable a chat share after the owner grants access in Gear. Check **Hosting on this device** for the current status. Turning off KnowledgeBox file access or leaving the foreground stops file serving. With the saved share still enabled, serving can resume once file access is confirmed and Cobell is in the foreground. See the [App Management tool workflow](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/gear.md).

## Limits

Local permissions and device switches do not select this device in a DingDong's Gear or make unavailable tools work. Use the normal personal interface to manage Gear targets, device registration and sign-in tokens.

Agent sessions do not receive ordinary DingDong OS alerts, even though this dashboard contains an OS Notifications permission row. Receiving device information also remains separate from the outgoing Share My Device Info switch.

A failed settings read/save alone does not establish the final server state. Inspect the current device settings before submitting another change.

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md) · [Authentication index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/README.md)

[Device management](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md) · [Screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/screen-sharing.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md)

Reviewed: 2026-11-19. UI labels use the English app language.
