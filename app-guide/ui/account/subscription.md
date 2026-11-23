# Review or change a subscription: screen reference

Platform Plan, AI Tier and External AI Slots are independent subscriptions with separate charges and billing dates. Each product is managed on its purchase platform; other products may use different platforms. Changing or ending one product leaves the others unchanged. Organization remains unavailable.

## Open this screen

**Desktop:** Upper-right avatar/name → Profile → Subscription & Payment. The Plan, AI Tier and External AI Credential Slots sections offer Change Subscription or a subscription/upgrade button.

**Mobile:** Home profile header or More profile card → Profile → Subscription & Payment.

## Controls

| Control | Behavior |
|---|---|
| Plan / AI Tier / External AI Credential Slots | Selects account capacity, Cobell AI quota and paid external-slot capacity independently in the desktop change dialog. |
| Payment Info | Desktop expands/collapses billing details for the subscribed section. |
| Refresh / Retry | Reloads the corresponding summary after a failed or stale read. Mobile also supports pull to refresh. |
| Desktop payment-method country | Chooses an offered billing country when a payment route is needed; a picker Cancel leaves the choice unchanged. |
| Desktop Plan / AI Tier cards | Changes the selection and calculates a new quote. |
| Desktop slot count / quota controls | Edits the number of paid slots and the usage units per slot. See the capacity guide. |
| Next / Previous | Moves between selection and Review Change. Invalid input, missing/failed quotes and unresolved paid checkout can disable Next/confirmation. |
| Review Change | Shows itemized current/new charges, any proration, next recurring charge and effective date. Capacity reductions show affected slots. |
| Proceed to payment / Confirm / Cancel subscription | Submits the current quote. Cancellation of the selected product has another confirmation. |
| Cancel / header Close | Leaves the desktop change view when it is not submitting. |
| Payment Management | Opens Payment Method, Scheduled, Grant Slots and History tabs. |
| Mobile summary | Shows current plan/tier/paid slots, status, payment provider, dates and scheduled changes. |
| Mobile subscription panel | Offers catalog refresh, store products, Subscribe, Restore purchases and Manage subscription as available. |
| Mobile AI usage / Payment history / slot entitlements | Opens the corresponding detail view. |
| Cobell-provided access | Shows provided access and its end date. It does not renew or bill automatically. Subscription configuration changes are unavailable while it is active. |

## Change timing

The desktop quote distinguishes an immediate charge from a change at the next billing date. Confirm the displayed amount, currency and timing. An expired quote is recalculated and requires review again.

## Expiry and return to Free

For an active paid subscription, cancelling renewal preserves benefits through the current paid period. Only Platform Plan expiry returns platform limits to Free; other products expire independently. Cobell-provided access ends only for the granted product at its end date. It does not start a paid subscription or restart an earlier paid subscription; a later paid subscription requires a separate purchase.

| Item | Effect at expiry | Recovery |
|---|---|---|
| Device registrations above the Free limit | Excess registrations are removed and their normal/agent sessions end. Registrations within the limit remain. | Sign in again within the available limit. A new subscription does not restore removed registrations or sessions. |
| External AI slots that lose access | Cobell deletes the stored credentials and settings. Paid slots count toward the 5-slot limit first. | Register credentials and configure the slots again after obtaining capacity. |
| Agent sign-in tokens above the active limit | Tokens become plan-paused and their associated agent sessions end. | Use Reactivate for an eligible token when capacity is available. A plan increase alone does not reactivate it. |

Explain removal and recovery requirements before expiry. See [device management](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/device-management.md), [slot capacity](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) and [agent tokens](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/agent-tokens.md).

## Conditions and recovery

Manage an existing subscription on its purchase platform. Desktop shows a platform notice for Apple/Google subscriptions that have not fully ended. Turning off renewal or pausing alone does not make a different platform available.

During payment-failure/grace or paused states, configuration changes can be blocked; read the payment notice and management action. A checkout timeout, browser return or store purchase launch is not proof of a completed subscription change. Resolve the existing attempt before starting another.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md) · [Mobile store subscriptions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/mobile-subscription.md) · [Desktop checkout recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/checkout-recovery.md) · [Payment methods](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/payment-methods.md) · [Slot capacity](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-11-16. UI labels use the English app language.
