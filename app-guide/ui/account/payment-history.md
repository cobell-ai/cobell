# Read payment history: screen reference

## Open this screen

**Desktop:** Profile → Payment Management → History.

**Mobile:** Profile → Subscription & Payment → Payment history.

## Controls and fields

| Control or field | Behavior |
|---|---|
| Transaction rows | Shows date/time, provider, displayed amount/currency and pending/completed/failed/refunded status. Rows do not open an expandable invoice. |
| Failure text | Describes a failed payment where available. |
| Load more | Requests older records. |
| Retry after initial/refresh failure | Retries the history read. |
| Retry after loading-more failure | Retries the older-page read. |
| Mobile Refresh / pull to refresh | Reloads the history. Desktop has read/append retry controls rather than a regular Refresh button inside this list. |
| Close / Back | Returns from history. |

## Conditions and recovery

History is a record view. It does not start a payment, request a refund or change the subscription. A failed read is not an empty history; a failed refresh can retain previously loaded entries. Store amounts use the available store amount/currency; an unknown amount is shown as unavailable rather than a fabricated zero.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/payment-history.md) · [Desktop checkout recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/checkout-recovery.md) · [Mobile purchase restoration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/mobile-subscription.md) · [Subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
