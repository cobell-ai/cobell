# Start Browsers and manage runtime downloads

Run a Browser on its owning device and distinguish saved configuration from the live session.

## Start here

**Desktop:** Management → Browser → the owning device's Browser row.

**Mobile:** Shortcuts → Browser → a local Browser on Android or iOS 18.4+ → runtime controls.

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

## iOS steps

1. Open the local Browser detail, choose **Start browser**, then **Open browser**.
2. Use the address bar for public HTTPS sites. Use the tab menu to add, switch or close pages. The Browser's domain rules still apply.
3. Return to Cobell to keep the session running in the foreground, or choose **Stop browser** to end it. Switching apps or locking the device ends the session and keeps the saved Browser profile.

## Change the site account

**Stop browser** ends the session. Sign out within the website first to end its saved sign-in. To keep two site accounts separate, create a second Browser, sign in there, and select it in the DingDong’s Gear. Follow the [Browser Gear steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md).

## Recovery

If the running-browser limit is reached, stop another local Browser or adjust the limit in the Browser list menu.

Losing Wi-Fi/Booster or turning its permission off stops advanced sessions. If cleanup cannot be confirmed, restart Cobell before starting that Browser again. Pending policy/deletion verification can block actions; use the offered service Retry/reload and inspect the current state before repeating work.

If iOS offers **Retry profile reset**, complete the reset before starting the Browser. This clears that Browser's cookies and site data.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/browser-runtime.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md) · [Browser policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md) · [Browser configuration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md)

Reviewed: 2026-11-25. UI labels use the English app language.
