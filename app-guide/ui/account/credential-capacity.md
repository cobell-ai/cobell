# Inspect external credential slots and limits: screen reference

## Open this screen

**Desktop:** Profile → External AI Credential Slots; Payment Management → Grant Slots shows grant history. Change Subscription opens the paid-capacity editor.

**Mobile:** Profile → External AI Credentials → External AI slot entitlements; also linked from Subscription & Payment.

## Controls and fields

| Control or field | Behavior |
|---|---|
| Paid / Grant / Total | Distinguishes purchased and granted capacity. |
| Desktop paid-slot count input / − / + | Edits the number of purchased slots within the displayed bounds; zero is allowed. |
| Desktop per-slot unit input / − / + | Sets a paid slot's monthly usage multiplier, up to 100×. |
| Same capacity for all paid slots / Apply to all | Copies the multiplier to all paid slots in the draft. |
| Grant panel / lock | Grant capacity is shown separately and cannot be edited with paid-capacity controls. |
| Review Change warnings | Shows affected paid slot numbers, credential summaries and the effective time of a reduction. |
| Grant records | Shows the number of granted slots, start and expiry dates, and active, upcoming or expired status. |
| Load more / read Retry | Loads older grant records or retries the failed read. |
| Mobile Refresh / pull to refresh | Reloads capacity and history; their failures have separate retry controls. |
| Mobile Subscription & Payment | Opens summary and available store product bundles. The entitlement screen itself does not edit capacity. |
| Manage credentials / Back / Close | Opens credential settings or leaves the current view. |

## Conditions and recovery

External AI slots in Cobell have a monthly usage limit and no 5-hour or 7-day usage limits. Each slot’s usage meter shows the percentage remaining and when it resets.

Use up to 5 slots per account, with a different OpenAI API key or ChatGPT account in each slot.

Changes to paid slot count or usage multipliers take effect at the next paid billing period. Grant history can include future or expired grants. The mobile store catalog shows available configurations.

## Capacity removal and expiry

When a slot entitlement ends, Cobell deletes its credentials and bound settings. During renewal verification, usage is paused and the registered credential is kept. Paid slots count toward the 5-slot limit first. If a purchase displaces a granted slot, Cobell also deletes that slot’s credential and settings. Granted slots within the limit keep their credentials when their displayed numbers change.

If a purchase displaces a free slot, its unused allowance can be added to the new paid slot, up to a combined X100. A plus sign beside the paid multiplier, such as X3+, indicates the extra allowance. The combined allowance expires at the end of the paid billing period.

Buying capacity again does not restore deleted credentials or settings. Register and configure the slots again. Removing a stored key from Cobell does not revoke the original key at its provider. A credential's expiry date or Auto extend setting does not preserve an ended slot entitlement.

Explain this before expiry and use [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) for the account and device-limit effects.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/credential-capacity.md) · [Change subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) · [Mobile store bundles](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/mobile-subscription.md) · [Manage credentials](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/external-credentials.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
