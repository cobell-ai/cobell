# Check AI usage and quota: screen reference

## Open this screen

**Desktop:** Profile → AI Tier and session usage bars.

**Mobile:** Profile → AI usage; also linked from Subscription & Payment.

## Controls and fields

| Control or field | Behavior |
|---|---|
| AI Tier | Shows the account's Cobell AI tier. Mobile Tier 0 can show that quota is not included. |
| Session bars/cards | Shows the percentage used and reset time for the short and weekly sessions. Desktop labels the short window as 5 hours; mobile derives its label from the reported duration. |
| Mobile summary percentage | Shows the more constrained session's used percentage. |
| Refresh / Retry | Reloads usage; a failed quota/subscription read or pending reset has its own retry notice. Mobile also offers pull to refresh. |
| Desktop Payment Info | Expands/collapses AI-tier payment details. |
| Change Subscription / Upgrade Tier | Opens desktop billing selection; the mobile subscription row opens its summary/store panel. |
| LLM Provider / External AI Credentials | Opens provider policy or separate credential settings. |
| Mobile Back | Returns to Profile. |

## Conditions and recovery

Usage requires a personal session. A failed or stale read does not confirm zero usage or remaining allowance. Mobile shows high/near-limit/limit-reached notices; the compact percentage uses the more constrained of the two sessions.

Cobell AI-tier quota, external-slot token limits and the external provider's own limits are separate. Review the source used for a request before interpreting one meter as total AI availability.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/ai-usage.md) · [Subscription](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md) · [External credentials](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/external-credentials.md) · [External slot capacity](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/credential-capacity.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
