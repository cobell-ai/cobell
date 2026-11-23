# Configure external AI credentials

## Start here

**Desktop:** Upper-right avatar/name → Profile → External AI Credential Slots → Manage credentials.

**Mobile:** Home profile header or More profile card → Profile → External AI Credentials.

Use a different OpenAI API key or ChatGPT account in each slot. Cobell rejects credentials already registered in another slot on your account.

## Register or replace an API key

1. Open credential management and confirm that the account has slot capacity. Retry a failed read first.
2. Choose API key on desktop or Register/Replace with API key on mobile for the intended slot.
3. Enter the key. Mobile Show/Hide changes only draft visibility; neither platform reveals a stored secret.
4. Choose Register/Save or submit from the keyboard. Wait for the input to clear and the slot list to update.
5. Review enabled state, expiry and session meters. Registration enables the slot and sets an initial 14-day validity; auto-extension settings carry over from that slot.

## Register the desktop's Codex credential

1. On the computer where Codex is signed in, open Manage credentials and check the Codex OAuth status.
2. Refresh the status if needed. A missing or invalid source must be resolved before registration.
3. Choose Codex on the intended slot. This can replace its existing credential.
4. Check the stored slot status. Keep the registration device available when the credential needs refreshing.
5. Mobile can review and manage the registered slot; registration and source refresh use the desktop.

## Find a stored match

Use the API-key match input to list slots matching a supplied key. On desktop, the Codex-status match action checks the local Codex credential. These checks do not register or replace credentials. Review the reported slot numbers rather than assuming the row that opened the input is the only result.

## Choose use order and validity

Set external-first or Cobell-first preference, then Round robin/Take turns or Priority/Lowest slot number first. Enable the desired slots. For expiry, choose a date and confirm; for automatic extension, open Extend, set the switch and 1–90-day duration, then Save. Cancel leaves each draft unchanged.

## Clear a credential

Choose Clear slot/delete, read the affected slot, then confirm. This removes its stored credential and settings. To abandon a mobile key draft, go Back and discard it; Cancel keeps editing.

## Conditions and recovery

Only personal sessions can manage credentials. Enter keys in the credential editor. Stored secrets are not shown again after registration, and a replacement overwrites the selected slot's credential.

Automatic extension requires an online Cobell account and valid source credentials. It does not renew the provider subscription or increase the slot's token limit. Check the displayed expiry and resolve source login or registration problems before trying again.

Follow your preferred AI-source policy and check slot availability. Cobell AI quota may be used when external credentials are unavailable. The provider can impose its own quota; check the displayed reason and reset time.

Failed operations show an error and recheck slot state where possible. Review the refreshed slot before repeating a replacement or deletion. A changed account, removed entitlement or replaced target can retire an open editor; return to management and reopen the intended slot.

## When a subscription or slot grant ends

Credentials and bound settings for ended slot entitlements are deleted from Cobell. They are not kept disabled for later recovery. Still-valid, separately granted slots retain their credentials, even if the displayed slot number changes.

Buying capacity again requires registering and configuring the credentials again. A stored key's removal from Cobell does not revoke the original key at its provider. Disabling a slot or using credential auto-extension does not preserve an ended entitlement. Explain the deletion before expiry; see [slot capacity and expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/credential-capacity.md).

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/external-credentials.md) · [Slot capacity and quotas](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/credential-capacity.md) · [Cobell AI usage](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/ai-usage.md) · [Provider policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/llm-provider.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
