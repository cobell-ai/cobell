# Use another Android app’s notifications as a trigger

## Configure the rule

1. Create a Mobile notification hook with AI response or Flow as the target.
2. Set an app filter and optional title/content filters.
3. For AI response, choose the room/responder, prompt and room/new-thread destination. For Flow, select the target Flows.
4. Save and enable the rule.

## Enable Android observation

On the observing Android device, open Flow → Hooks and scheduler → Mobile notification hooks. Read Notification access on this device and open notification access settings if access is denied. Grant access to Cobell in Android, return to the app and check the status again. Use Retry for a failed access read.

## Completion and recovery

An iPhone cannot supply other-app notification observations. This rule has no normal-session trigger-mode selector. Check Android observation access and event filters separately from Cobell's OS-notification delivery preference.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/android-hook.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
