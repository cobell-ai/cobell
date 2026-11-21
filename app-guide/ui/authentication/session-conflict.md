# Resolve a login conflict or device limit: screen reference

Choose how to proceed when Cobell detects another session or too many registered devices.

## Open this screen

**Desktop:** The relevant recovery dialog appears during sign-in.

**Mobile:** Sign-in opens a session-conflict dialog or a device-limit recovery screen as needed.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Logout Other & Login | Switches the normal session to this device. |
| Desktop Use Multi-Device Login | Uses the offered agent/multi-device alternative. |
| Mobile Switch to this device | Signs out the previous session of the same type. |
| Mobile Sign in as an agent | Connects this device as an agent and keeps the existing normal session active. |
| Session details | Shows the previous device, last activity and, when available, how many more devices you can register. |
| Device-limit selection | Desktop and mobile let you choose one registered device to unregister. |
| Unregister & Login / Retry Same Device | Commit a replacement or retry the locked replacement selection. |
| Cancel | Abandons the new attempt. |

## Conditions and results

Normal sign-in allows one desktop and one mobile session at the same time. Switching replaces the normal session on the same type of device. Agent sign-in has no separate concurrent-session limit. Adding a new device requires room under the plan's registered-device limit.

A device-registration replacement can have completed even if the next login stage fails. Do not choose a different device merely because the result is uncertain. Cancel stops the new attempt; it does not undo a committed device replacement.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/session-conflict.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
