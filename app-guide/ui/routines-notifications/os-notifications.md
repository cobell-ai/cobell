# Enable Cobell OS notifications: screen reference

Allow a personal device to display DingDong alerts.

## Open this screen

**Desktop:** Avatar/name near the upper-right → Profile → OS notifications.

**Mobile:** Fifth bottom tab More → OS notifications, or Profile → OS notifications.

## Controls

| Control or area | Behavior |
|---|---|
| OS notifications switch | Saves this device's Cobell delivery preference. |
| Permission notice | Explains blocked, missing or unavailable operating-system notification access. |
| Allow notifications | Mobile requests notification permission when it has not yet been decided. |
| Open system settings | Opens the OS notification settings when permission needs to be changed there. |
| Retry | Retries failed settings/runtime loading where offered. |

## Conditions and results

OS delivery depends on the DingDong's Gear target platform, the device's Cobell delivery preference and OS permission. This setting belongs to normal personal sign-in; agent sessions are excluded. Return from system settings and recheck permission state.

Permission to display Cobell alerts does not grant Android access to read other apps' notifications. That observation access is configured separately for Mobile notification hooks. Saving a preference can fail; inspect the error before treating delivery as enabled.

## Mobile states and recovery controls

| State or action | Behavior |
|---|---|
| Initial loading / saving | Progress is shown; switch and available recovery/permission buttons are disabled. |
| Enable the switch | Enables this device's notification preference. Complete any system permission prompt and check the displayed permission status. |
| Notification settings could not be loaded. → Retry | Reloads the saved preference. A retained switch value is disabled while the load has an error. |
| The notification change could not be confirmed. Try again. | Inline save error. The previous preference can be restored; inspect the current switch before retrying the change. |
| Allow notifications | Appears when the switch is on and permission is undecided. Requests permission. |
| Open system settings | Appears when the switch is on but permission is denied or could not be checked with an available notification runtime. Return to Cobell to recheck permission. |
| Retry under the permission notice | Retries notification setup after a permission or availability error. Follow the current notice and check the result. |
| System settings could not be opened. Try again. | Inline failure under the permission notice after its action failed. |
| Switch off / permission already allowed | No permission-action notice is shown. The switch controls Cobell's delivery preference, not the OS permission itself. |

The mobile card is available to normal signed-in accounts and is hidden in preview. Check permission status after returning from system settings. A saved notification preference does not by itself confirm OS permission or notification delivery.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/os-notifications.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-24 (mobile switch, permission and distinct recovery controls; desktop guidance retained). UI labels use the English app language.
