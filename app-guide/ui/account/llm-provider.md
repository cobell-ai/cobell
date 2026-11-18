# Choose the LLM provider: screen reference

## Open this screen

**Desktop:** Profile → LLM Provider → Manage.

**Mobile:** Home profile header or More profile card → Profile → LLM Provider.

## Controls

| Control or area | Behavior |
|---|---|
| Auto / Automatic | Chooses Cobell's automatic provider policy. Active-provider information describes current availability. |
| OpenAI | Chooses the OpenAI-only policy when OpenAI is active. |
| Current / existing provider order | Can display and preserve a saved provider order that differs from Auto or OpenAI-only. The screen does not provide a full fallback-order editor. |
| Active / inactive information | Describes provider availability; viewing a saved order does not establish that each provider can run. |
| Future-provider vote chips | Selects Anthropic, DeepSeek, Google, xAI, Moonshot AI or Z.AI as a future-provider preference. Selecting a chip edits the draft. |
| Save changes / Save | Persists the changed policy and vote. Disabled for an unchanged draft or while saving. |
| Retry | Reloads failed settings. Mobile's bottom action becomes Retry after a failed read. |
| Desktop Cancel | Leaves the dialog without saving the draft. |
| Mobile Back | A changed draft asks whether to discard; Cancel keeps editing. Leaving is blocked while saving. |

## Conditions and recovery

Auto is an automatic policy, not a permanent alias for OpenAI. Desktop explains the OpenAI-only case when OpenAI is the sole active provider; available providers can change. An unavailable OpenAI option cannot be newly selected.

A future-provider vote does not enable that provider or change the active policy until the settings are saved. The saved vote is still a preference, not an execution entitlement. Failed saves display an error; inspect the current draft and use the offered retry before assuming the policy changed.

This policy is separate from external-first/Cobell-first and external-slot selection settings.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/llm-provider.md) · [External credential preference](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/external-credentials.md) · [AI usage](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/ai-usage.md) · [Account index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
