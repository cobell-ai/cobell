# Set Browser site access and permissions: screen reference

Set the Browser-global limits, then narrow them further in individual Gear when needed.

## Open this screen

**Desktop:** Management → Browser → pencil → Next → Browser-global settings.

**Mobile:** Shortcuts → Browser → select → Edit browser → Global browser policy.

## Controls

| Control or area | Behavior |
|---|---|
| Allow all public websites | On: public sites remain subject to blocked rules and other permissions. Off: only allowed hosts can be visited; an empty list blocks web navigation. |
| Allowed sites / allowed hosts | One domain per line. Pasted addresses are normalized to hosts; URL paths do not restrict this list. |
| Host/subdomain choice | Both apps can ask whether a newly entered domain should cover just that host or wildcard subdomains. Review the normalized list before saving. Cancel leaves that choice unresolved. |
| Blocked address rules / Blocked URL patterns | One rule per line; use these for path/specific-address restrictions. They take priority over allowed hosts. |
| File uploads / Downloads | Permit moving files into or out of a Browser session. |
| Clipboard / External app links | Permit clipboard access or opening external protocols/app links. |
| Private network / Website permissions | Permit private-network access or website permission handling where supported. |
| Runtime host expansion | Permits supported additions to the runtime's host scope, subject to the remaining policy limits. |
| Page/DOM mutation / Scripts | Permit the respective advanced page modifications. |
| Security bypass / Content override | Permit the respective advanced security/content changes. |
| PDF export / Live stream / Lifecycle control | Permit the respective advanced export, stream and browser lifecycle operations. |
| Save | Persists global limits. In a Gear editor, save the Gear to persist its narrower policy. |

## Conditions and recovery

Blocked rules win. A Gear override cannot widen the Browser-global policy. Enabling a policy option does not supply missing platform capability or OS permission.

On a local Android Browser, options marked Requires Cobell Mobile Booster connection are disabled while advanced control is unavailable. Basic browsing, reading, clicking and typing work without pairing. A connected Booster must be available when the Browser starts; restart an existing basic session to use it.

On iOS 18.4 or later, the Browser applies domain rules to public HTTPS sites. Downloads follow the Browser and Gear permissions. To upload, keep the Browser visible and choose the files yourself when Cobell opens the picker. Advanced controls such as raw CDP remain unavailable on iOS.

If a settings change is awaiting confirmation, runtime permissions can remain stricter than the saved settings. Use the offered reload/service Retry and recheck before assuming a relaxed permission is active.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md) · [Create/edit a Browser](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md) · [Approve Browsers in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md) · [Android Booster](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md)

Reviewed: 2026-11-21. UI labels use the English app language.
