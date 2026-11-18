# Connect Cobell Mobile Booster on Android: screen reference

Allow advanced Browser control on this Android device, pair it, then establish a wireless debugging connection.

## Open this screen

**Mobile:** More → Cobell Mobile Booster, or open a local Browser detail → Cobell Mobile Booster / Set up Cobell Mobile Booster. On supported Android, the Sandbox Browser Use built-in catalog page also offers Set up Cobell Mobile Booster.

**Desktop:** Pair on the target Android phone; desktop can configure eligible Browsers in Gear.

## Controls

| Control or area | Behavior |
|---|---|
| Allow Cobell Mobile Booster on this device | Separate permission, saved immediately. Off disconnects ADB and stops advanced sessions; saved pairing keys remain. |
| Maximum running browsers | Slider 1–4, initially 2. Lowering the limit prevents new starts; already-running Browsers stay open. |
| Prepare pairing and open Settings | Requires enabled Booster, Android 11+, Wi-Fi, signed-in account and notification access; prepares the notification and opens Developer options. |
| Pairing notification input | With Android's pairing window open, enter its pairing port and six-digit code separated by a space. If preparation expires, start pairing again with fresh details. |
| Find and connect automatically | Searches for this device's connection address after pairing. Pairing also attempts discovery/connection automatically. |
| IP address and connection port / Connect | Manual fallback using the main Wireless debugging screen, e.g. `192.168.0.2:37123`; this is not the pairing port. |
| Open notification settings / Open Wi-Fi settings | Appear for the respective prerequisite failure. Return and prepare pairing again. |
| Cancel / Disconnect | Cancels pending work or ends the current connection. |
| Delete this app's connection key | Confirmation disconnects and deletes this account's key on this device. Android's trusted-device entry is not removed. |

## Conditions and recovery

Basic Android WebView browsing, reading, clicking and typing work without Booster. Pairing and connection are separate; a successful pairing notification does not by itself prove connection. iOS has neither local Browser execution nor Booster pairing.

For an expired/failed pairing attempt, open a new Android pairing-code window and prepare again with its current port/code. For discovery/connection failure, check Wi-Fi, Wireless debugging and the current connection port. A notification/key-storage error has its own message; do not delete the key merely to retry a read.

Advanced sessions stop when Wi-Fi/connection is lost or Booster permission is turned off. Mobile screen sharing is a separate system-approved session and needs no Booster. Mouse/keyboard control of the phone remains unavailable.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md) · [Runtime, browser window and downloads](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-runtime.md) · [Mobile screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/screen-sharing.md)

Reviewed: 2026-10-23. UI labels use the English app language.
