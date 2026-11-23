# Configure external AI credentials: screen reference

## Open this screen

**Desktop:** Upper-right avatar/name → Profile → External AI Credential Slots → Manage credentials.

**Mobile:** Home profile header or More profile card → Profile → External AI Credentials.

## Account controls

| Control or area | Behavior |
|---|---|
| Prefer external AI credential slots | On: tries available external slots before Cobell AI. Off: tries Cobell AI first and falls back to external credentials when quota blocks the request. Saves directly. |
| Round robin / Take turns | Selects available credentials in sequence. Desktop uses a segmented selector; mobile opens a choice sheet. |
| Priority / Lowest slot number first | Prefers the available credential with the smallest slot number. Saves the choice without a separate overall Save. |
| Desktop Codex OAuth status | Shows whether local credentials are found and valid, with account information when available. |
| Desktop Codex-status refresh | Rereads credential settings and the local Codex status; does not itself register a slot. |
| Desktop Codex Check stored match | Checks which stored slots match the local Codex credential. Enabled when the local source is found and valid. |
| Mobile Find matching slots | Opens a key input that checks the supplied API key against stored slots. Results show matching slot numbers or no matches. |
| Mobile slot entitlements | Opens paid/granted capacity and grant history. |
| Read Retry / mobile Refresh and pull to refresh | Reloads failed credential data. Mobile blocks changes while a failed read remains unresolved. |
| Close / Back | Leaves credential management. |

## Slot controls

External AI slots in Cobell have a monthly usage limit and no 5-hour or 7-day usage limits. Your AI provider may apply its own usage limits.

| Control or area | Behavior |
|---|---|
| Slot header/status/device/expiry | Shows the stored credential's type, status, registration device and validity where available. |
| Monthly usage meter | Shows the percentage of the slot’s allowance remaining and when it resets. |
| Use this slot / enabled switch | Enables or disables a nonempty slot. A source-logged-out slot cannot be enabled with this switch. |
| Desktop API key / mobile Register or Replace with API key | Opens a masked key input. Registration can replace an occupied slot. |
| API-key Register / Save / keyboard submit | Sends a nonempty key to the selected slot. Successful registration clears the input and closes it. |
| Mobile Show key / Hide key | Changes visibility of the current draft, not the stored credential. |
| Desktop Check stored match | A slot-row action opens an API-key match input. The check can return matching slot numbers across the account; it does not register the key. |
| Desktop Codex | Registers the current local Codex credential into that slot. Mobile manages these slots but does not import or register Codex credentials. |
| Expiry / Change expiration | Opens a date picker from today through 365 days ahead. Confirm sets expiry to the local end of the selected day; Cancel makes no change. |
| Mobile expiry mode icon | Switches between calendar and localized date input. Invalid or out-of-range input must be corrected before confirmation. Keyboard Done can submit a valid date. |
| Calendar controls | Selects month/year/day within the offered range. Desktop uses the calendar picker. |
| Auto extend / Extend | Opens a separate draft with an enable switch and a 1–90-day duration slider. Save persists both; Cancel leaves them unchanged. Mobile disables the duration slider while extension is off. |
| Clear slot / delete icon | Requires confirmation before removing the credential and bound slot settings. Cancel keeps them. Clearing does not purchase or remove slot capacity. |
| Mobile key-editor Back | A nonempty draft asks whether to discard it; Cancel keeps editing. The editor blocks leaving while submitting. |

## Slot states

Empty, Registered, Authenticated, Authentication rejected, Provider usage limit reached, Refreshing credentials, Registration device offline, Credential refresh failed and Signed out on the registration device describe different conditions. An authentication/quota status is separate from the slot's enabled switch and token-session allowance.

Subscription or slot-grant expiry deletes the credentials and settings for ended entitlements from Cobell. This is not the retained state created by turning Use this slot off. Buying capacity again does not restore deleted records; register and configure those slots again. Still-valid, separately granted slots keep their credentials. Explain this before expiry; see [slot capacity and expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md).

## Conditions and recovery

Only personal sessions can manage credentials. Enter keys in the credential editor. Stored secrets are not shown again after registration, and a replacement overwrites the selected slot's credential.

Automatic extension requires an online Cobell account and valid source credentials. It does not renew the provider subscription or increase the slot's token limit. Check the displayed expiry and resolve source login or registration problems before trying again.

Follow your preferred AI-source policy and check slot availability. Cobell AI quota may be used when external credentials are unavailable. The provider can impose its own quota; check the displayed reason and reset time.

Failed operations show an error and recheck slot state where possible. Review the refreshed slot before repeating a replacement or deletion. A changed account, removed entitlement or replaced target can retire an open editor; return to management and reopen the intended slot.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/external-credentials.md) · [Slot capacity and quotas](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Cobell AI usage](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/ai-usage.md) · [Provider policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/llm-provider.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
