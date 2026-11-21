# Set Browser site access and permissions

Set the Browser-global limits, then narrow them further in individual Gear when needed.

## Start here

**Desktop:** Management → Browser → pencil → Next → Browser-global settings.

**Mobile:** Shortcuts → Browser → select → Edit browser → Global browser policy.

## Steps

1. Open the Browser editor and its global policy.
2. Choose public-site access, or turn it off and enter the required hosts one per line.
3. Resolve any host/subdomain prompt. For example, a pasted `https://example.com/help` becomes a domain rule; it does not restrict access to `/help`.
4. Add blocked address rules for addresses that must remain inaccessible.
5. Set each file, clipboard, network and advanced permission according to the task, then Save.
6. In the DingDong's Gear, approve this Browser and optionally apply a stricter policy. Verify runtime capability on the owning device before execution.

## Completion, limits and recovery

Blocked rules win. A Gear override cannot widen the Browser-global policy. Enabling a policy option does not supply missing platform capability or OS permission.

On a local Android Browser, options marked Requires Cobell Mobile Booster connection are disabled while advanced control is unavailable. Basic browsing, reading, clicking and typing work without pairing. A connected Booster must be available when the Browser starts; restart an existing basic session to use it.

On iOS 18.4 or later, set domain rules for public HTTPS sites. File transfer and other advanced controls are unavailable.

If a settings change is awaiting confirmation, runtime permissions can remain stricter than the saved settings. Use the offered reload/service Retry and recheck before assuming a relaxed permission is active.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/browser-policy.md) · [Create/edit a Browser](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md) · [Approve Browsers in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md)

Reviewed: 2026-11-21. UI labels use the English app language.
