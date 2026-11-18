# Start Browsers and manage runtime downloads

Run a Browser on its owning device and distinguish saved configuration from the live session.

## Start here

**Desktop:** Management → Browser → the owning device's Browser row.

**Mobile:** Shortcuts → Browser → a local Android Browser → runtime/download cards.

## Desktop steps

If Browser shows only an empty Device message and no Add button, open [Management → Device](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md). Check registration and use Retry on a load error when offered. Browser creation controls appear once the device list is available. With devices present but no saved Browsers, Add opens [Browser configuration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md).

1. Open Management → Browser and find a Browser owned by this device.
2. Choose Start browser and check the runtime state. Remote-owned rows do not have a local start/stop control.
3. Use Stop browser when finished. After changing background mode, stop and start the Browser to apply it.

## Android steps

1. Open the local Browser detail and choose Start browser. Basic browsing needs no Booster; advanced work needs its ready connection at startup.
2. When running, choose Open browser to view it. Use the address field and Go, or Pages to select another existing page. Close stops the Browser; Android Back first uses page history.
3. For printing, enable PDF export and check Booster readiness. Choose Print or save PDF/PDF, wait for preparation, then select the printer or Save as PDF in Android's print dialog. Cancel while preparing if needed.
4. In Downloads, use Save a copy to export a downloaded file, or Delete saved file to remove Cobell's saved copy. Canceling the system picker does not confirm export.
5. Choose Stop browser before restarting to apply changed background/Booster mode.

## Completion, limits and recovery

iOS cannot execute local Browsers. Saved settings, remote runtime reports and a locally running session are distinct. Downloads remain subject to policy; the download card has no Open or transfer-retry button.

If the running-browser limit is reached, stop another local Browser or change the 1–4 limit in Booster settings. Lowering that limit keeps existing sessions open but prevents additional starts.

Losing Wi-Fi/Booster or turning its permission off stops advanced sessions. If cleanup cannot be confirmed, restart Cobell before starting that Browser again. Pending policy/deletion verification can block actions; use the offered service Retry/reload and inspect the current state before repeating work.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/browser-runtime.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md) · [Browser policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md) · [Browser configuration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md)

Reviewed: 2026-10-24. UI labels use the English app language.
