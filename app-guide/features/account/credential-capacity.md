# Inspect external credential slots and limits

## Start here

**Desktop:** Profile → External AI Credential Slots; Payment Management → Grant Slots shows grant history. Change Subscription opens the paid-capacity editor.

**Mobile:** Profile → External AI Credentials → External AI slot entitlements; also linked from Subscription & Payment.

## Inspect or change capacity

1. Read paid, grant and total counts in Profile or the entitlement screen.
2. Check each entitlement's quota and the grant records' start/expiry dates. Load more or retry failed reads as needed.
3. On desktop, open Change Subscription to adjust paid-slot count and per-slot units. Use Apply to all only to copy a draft amount.
4. Continue to Review Change and inspect its price, affected slots and effective date before submitting.
5. On mobile, use Subscription & Payment for the configurations offered by the store. The entitlement view is informational.
6. Return to Manage credentials to confirm the slots available after the change.

## Conditions and recovery

Invalid numeric input blocks progression until corrected. Paid units increase both short-window and weekly limits; the subscription price is charged monthly. Read the unit size and maximum shown by the current catalog. Inspect the slot session meters for remaining allowance and reset times.

Lowering a token limit with capacity unchanged preserves daily/weekly usage and credentials; usage can already exceed the new limit. Grant history is separate from purchased capacity and can include future or expired grants. Mobile purchase/restoration is supported when the store catalog permits it.

## Capacity removal and expiry

Removing paid capacity or ending a subscription or slot grant deletes credentials and bound settings for the affected entitlements when the change takes effect. They are not retained as disabled slots. Credentials for still-valid grants remain even if their displayed order moves.

New payment or capacity does not restore deleted credentials and settings. Explain this before expiry: the user must register the API key or desktop Codex credential and configure the slot again. Deleting a stored key from Cobell does not revoke the original key at its provider. The credential's own expiry and auto-extension settings do not extend a subscription or slot entitlement.

See [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md) for the account's return to Free and device-limit effects.

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Change subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md) · [Mobile store bundles](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/mobile-subscription.md) · [Manage credentials](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/external-credentials.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
