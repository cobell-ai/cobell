# Inspect external credential slots and limits

## Start here

**Desktop:** Profile → External AI Credential Slots; Payment Management → Grant Slots shows grant history. Change Subscription opens the paid-capacity editor.

**Mobile:** Profile → External AI Credentials → External AI slot entitlements; also linked from Subscription & Payment.

## Inspect or change capacity

1. Read paid, grant and total counts in Profile or the entitlement screen.
2. Check purchased capacity and the grant records' start and expiry dates. Load more or retry failed reads as needed.
3. On desktop, open Change Subscription to adjust the number of paid slots and the usage multiplier per slot. Use Apply to all to copy a multiplier to all paid slots.
4. Continue to Review Change and inspect its price, affected slots and effective date before submitting.
5. On mobile, use Subscription & Payment for the configurations offered by the store. The entitlement view is informational.
6. Return to Manage credentials to confirm the slots available after the change.

## Conditions and recovery

External AI slots in Cobell have a monthly usage limit and no 5-hour or 7-day usage limits. Each slot’s usage meter shows the percentage remaining and when it resets.

Use up to 5 slots per account, with a different OpenAI API key or ChatGPT account in each slot. Desktop offers up to 100× the monthly usage limit per slot.

Changes to paid slot count or usage multipliers take effect at the next paid billing period. For example, one X3 slot can become three X1 slots at the next payment. For App Store subscriptions, turn off auto-renewal and buy the new configuration after the current period ends.

## Capacity removal and expiry

When a slot loses access, Cobell deletes its credentials and bound settings. Paid slots count toward the 5-slot limit first. If a purchase displaces a granted slot, Cobell also deletes that slot’s credential and settings. Granted slots within the limit keep their credentials when their displayed numbers change.

New payment or capacity does not restore deleted credentials and settings. Explain this before expiry: the user must register the API key or desktop Codex credential and configure the slot again. Deleting a stored key from Cobell does not revoke the original key at its provider. The credential's own expiry and auto-extension settings do not extend a subscription or slot entitlement.

See [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md) for the account's return to Free and device-limit effects.

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Change subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md) · [Mobile store bundles](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/mobile-subscription.md) · [Manage credentials](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/external-credentials.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
