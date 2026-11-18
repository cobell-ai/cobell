# Choose who receives a message: screen reference

Set explicit recipients or exclusions before sending.

## Open this screen

**Desktop:** Use Recipient filter near the composer; open the recipient badge on a sent message to inspect it.

**Mobile:** Use the composer Recipient filter action, including More when compact. Tap a message's recipient badge to inspect its stored audience.

## Controls

| Control or area | Location and behavior |
|---|---|
| Only to | Selects explicit recipients. |
| Except | Selects excluded people. |
| Only me | Restricts the message to yourself. |
| Recent | Reuses a recent selection. |
| Apply (count) | Applies the chosen filter to the composer. |
| Use available recipients only | Removes stale/unavailable selections. |
| Switch to Only to / Switch to specific recipients | Replaces an exclusion policy with explicit recipients. |
| Sent-message recipient badge | Opens the stored explicit recipients or exclusions. Its count includes unavailable people. Me means the current account is the only explicit recipient. |
| Exclusion badge | Desktop shows Excluded: (count). Mobile shows an exclusion icon and count. This counts excluded people, not everyone allowed to receive the message. |
| Desktop sent-message recipient list | Specified recipients or Excluded users dialog. Scroll to read names and avatars; blocked users' photos are omitted. Profile unavailable (count) groups stored people who cannot currently be matched to a participant. Confirm closes the dialog. |
| Mobile sent-message recipient list | Scrollable sheet with names and an unavailable count. Excluded users also shows the warning about future participants. Close leaves the sheet. |

The sent-message lists are read-only. Their rows do not open profiles or change the audience. Missing people remain included in the badge count; they are not silently dropped from the stored rule. An empty list shows an empty-state message.

## Conditions and results

Messages with recipient filters are excluded from AI context. An exclusion policy can allow people invited later to see the message; use explicit recipients if that is not intended. Sent-message badges show the stored audience rule. They do not confirm delivery or reading, and an exclusion list does not reconstruct everyone who received an older message.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/recipient-filter.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

[Exclude messages from AI context](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/hide-from-ai.md)

Reviewed: 2026-10-03. UI labels use the English app language.

Sent-message badge/list details checked: 2026-10-24.
