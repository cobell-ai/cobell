# Buy, restore or manage a mobile subscription: screen reference

Platform Plan, AI Tier and External AI Slots are independent subscriptions with separate charges and billing dates. Each product is managed on its purchase platform; other products may use different platforms. Changing or ending one product leaves the others unchanged. Organization remains unavailable.

## Open this screen

**Desktop:** Apple/Google subscriptions show a purchase-platform notice. Use the corresponding mobile/store account for management.

**Mobile:** Profile → Subscription & Payment → Mobile subscription.

## Controls

| Control or state | Behavior |
|---|---|
| Refresh | Reloads store availability and the account's product catalog. The page also refreshes when the app resumes. |
| Plan / AI Tier | Filters the store configurations offered for the account. This is a product selection, not the desktop's arbitrary quota editor. |
| Product slot summary | Shows the selected product's included paid external-slot count and token capacity; some products include no paid slots. |
| Price / Subscribe | Opens Cobell's confirmation for an available product with a known store price. |
| Confirmation Subscribe / Cancel | Reviews plan, tier, slots and monthly price; Subscribe continues to the native store purchase flow, Cancel returns without launching it. |
| Terms / Privacy | Opens the legal reader when products are offered. |
| Restore purchases | Restores store purchases for the signed-in account; also retries retained verification failures. Enabled only when the store is configured and no operation is busy. |
| Manage subscription | Opens store subscription management when offered. Use the store's management flow for renewal/cancellation. |
| Waiting for purchase confirmation | Verification is pending; another purchase is disabled. |
| Subscription updated | The transaction was confirmed and the account summary refreshed. |
| Back | Leaves the subscription page. |

## Conditions and recovery

Android and iOS use their respective stores. Controls depend on the configured catalog, platform, signed-in account and current subscription. When the store is not ready, the panel can show “Mobile purchases are not available yet”; refresh after store availability changes.

An unavailable product or blank price cannot be purchased. A purchase owned by another Cobell account must be restored with that Cobell account. Use the original purchase platform until that product’s old subscription has fully ended. Store cancellation and backend confirmation are separate from closing this screen.

If the result cannot be confirmed, use Refresh or Restore purchases as offered. Do not repeat a purchase of the same product while its existing purchase is pending.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/mobile-subscription.md) · [Subscription overview](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) · [Payment history](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/payment-history.md) · [Slot capacity](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-11-16. UI labels use the English app language.
