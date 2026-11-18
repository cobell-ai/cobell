# Start Browsers and manage runtime downloads: screen reference

Run a Browser on its owning device and distinguish saved configuration from the live session.

## Open this screen

**Desktop:** Management → Browser → the owning device's Browser row.

**Mobile:** Shortcuts → Browser → a local Android Browser → runtime/download cards.

## Controls

| Control or area | Behavior |
|---|---|
| Desktop Browser empty Device message | With no devices in the loaded catalog, Browser Add/Refresh controls are absent. Open Management → Device to check registration or use a load-error Retry when offered. |
| Desktop Add with devices present | Opens Browser creation, including from a view with no saved Browsers. It does not start a Browser session. |
| Running / Stopped / Stale / Error | Reports runtime state separately from saved settings. Starting, opening, stopping and printing also show progress on mobile. |
| Desktop Start browser / Stop browser | Appears only for Browsers owned by this desktop; remote rows show reported state. |
| Mobile Start browser / Open browser / Stop browser | Starts the local Android session, opens its running window, or stops it. Stop can remain available during startup/verification; conflicting actions are disabled. |
| Basic / Booster capability | Indicates whether advanced controls are available. A connected Booster does not upgrade an already-running basic session. |
| Print or save PDF | Conditional Android action: needs a running Browser, ready connection, PDF permission and confirmed settings. Opens the system print flow; preparing can be canceled. |
| Browser window address / Go | On Android, enter an HTTP(S) address; a host without a scheme uses HTTPS. Browser policy still applies. |
| Browser window Pages | Selects an existing page from the page list; the button shows the selected page/count. |
| Browser window PDF / close / Android Back | PDF starts the checked print flow. Close stops the Browser. Android Back navigates back if possible, otherwise closes it. |
| Downloads | Local Android files show name and size. Save a copy opens the system export flow; Delete saved file removes the app's saved download directly. |
| Download Retry | Reloads a failed download-list read. It does not retry a failed transfer; request the download again after fixing permission/connection. |
| Refresh / Reload browser settings / service Retry | Rechecks saved/runtime state or recovers a reported service issue. |

## Conditions and recovery

iOS cannot execute local Browsers. Saved settings, remote runtime reports and a locally running session are distinct. Downloads remain subject to policy; the download card has no Open or transfer-retry button.

If the running-browser limit is reached, stop another local Browser or change the 1–4 limit in Booster settings. Lowering that limit keeps existing sessions open but prevents additional starts.

Losing Wi-Fi/Booster or turning its permission off stops advanced sessions. If cleanup cannot be confirmed, restart Cobell before starting that Browser again. Pending policy/deletion verification can block actions; use the offered service Retry/reload and inspect the current state before repeating work.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-runtime.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md) · [Browser policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md) · [Browser configuration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md)

Reviewed: 2026-10-24. UI labels use the English app language.
