# Exclude messages from AI context: screen reference

Keep a message visible to people while controlling whether DingDong can read it.

## Open this screen

**Desktop:** Use the composer Hide mode, or a message’s More/right-click → Hide or Unhide.

**Mobile:** Use composer Hidden, or message More → Hide from AI / Show to AI.

## Controls

| Control or area | Location and behavior |
|---|---|
| Hide / Hidden composer toggle | Marks new content for AI exclusion. |
| Hide / Hide from AI | Excludes an eligible existing message. |
| Unhide (desktop) / Show to AI (mobile) | Restores AI inclusion when permitted. |
| AI cannot see this message (mobile) | Tap the message indicator to open the exclusion explanation. |
| Show to AI / Cannot show to AI (mobile explanation) | Offers restoration for an eligible sent message in a writable room; otherwise the button is disabled. Close dismisses the explanation. |
| Cannot use together | Asks you to disable thread-creation mode or hiding before enabling the other. |

## Conditions and results

Hiding from AI does not remove the message from participants. Recipient-filtered and some special messages cannot be included in AI context. Composer hiding and thread creation cannot be enabled together.

On mobile, the indicator also appears for messages that are always excluded: recipient-filtered messages, P2P file offers, DingDong notifications and bot termination messages. Their explanation says the type cannot be shown to AI. Show to AI is disabled, and their More menu has no hide/show action. The indicator does not mean that someone manually enabled Hidden.

For ordinary hidden messages, Show to AI requires a confirmed sent message, a writable view, room send permission and support for message changes. Read-only, pending and failed messages cannot be restored through this control.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/hide-from-ai.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-24 (mobile message indicators and hide/show controls). UI labels use the English app language.
