# Inspect external credential slots and limits: screen reference

## Open this screen

**Desktop:** Profile → External AI Credential Slots; Payment Management → Grant Slots shows grant history. Change Subscription opens the paid-capacity editor.

**Mobile:** Profile → External AI Credentials → External AI slot entitlements; also linked from Subscription & Payment.

## Controls and fields

| Control or field | Behavior |
|---|---|
| Paid / Grant / Total | Distinguishes purchased and granted capacity. |
| Desktop paid-slot count input / − / + | Edits the number of purchased slots within the displayed bounds; zero is allowed. |
| Desktop per-slot unit input / − / + | Changes a paid slot's token units; each slot requires at least one unit and respects the displayed maximum. |
| Same capacity for all paid slots / Apply to all | Copies a valid unit amount to the paid-slot draft. It does not complete a purchase. |
| Grant panel / lock | Grant capacity is shown separately and cannot be edited with paid-capacity controls. |
| Review Change warnings | Shows affected paid slot numbers, credential summaries and the effective time of a reduction. |
| Grant records | Shows count, quota, start/expiry and active/upcoming/expired status. |
| Load more / read Retry | Loads older grant records or retries the failed read. |
| Mobile Refresh / pull to refresh | Reloads capacity and history; their failures have separate retry controls. |
| Mobile Subscription & Payment | Opens summary and available store product bundles. The entitlement screen itself does not edit capacity. |
| Manage credentials / Back / Close | Opens credential settings or leaves the current view. |

## Conditions and recovery

Invalid numeric input blocks progression until corrected. Paid units increase both short-window and weekly limits; the subscription price is charged monthly. Read the unit size and maximum shown by the current catalog. Inspect the slot session meters for remaining allowance and reset times.

Lowering a token limit with capacity unchanged preserves daily/weekly usage and credentials; usage can already exceed the new limit. Grant history is separate from purchased capacity and can include future or expired grants. Mobile purchase/restoration is supported when the store catalog permits it.

## Capacity removal and expiry

Removing paid capacity or ending a subscription or slot grant removes the affected entitlements when the change takes effect. Their stored credentials and bound settings are deleted from Cobell, rather than retained with the Use this slot switch off. Separately granted slots remain while their own entitlement is valid; their displayed order can change without losing credentials.

Buying capacity again does not restore deleted credentials or settings. Register and configure the slots again. Removing a stored key from Cobell does not revoke the original key at its provider. A credential's expiry date or Auto extend setting does not preserve an ended slot entitlement.

Explain this before expiry and use [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) for the account and device-limit effects.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/credential-capacity.md) · [Change subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) · [Mobile store bundles](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/mobile-subscription.md) · [Manage credentials](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/external-credentials.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-11-12. UI labels use the English app language.
