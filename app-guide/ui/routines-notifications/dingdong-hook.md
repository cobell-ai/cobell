# Respond to a DingDong notification: screen reference

Request an AI response when a Notification Sender event matches the selected source and filters.

## Open this screen

**Desktop:** Routine → Create → DingDong notification → AI response, or DingDong Settings → DingDong Notification Hook → Add.

**Mobile:** Shortcuts → Routine → Create → AI response/DingDong notification.

## Controls

| Control or area | Behavior |
|---|---|
| Chat room / Response DingDong | Selects the responding target. |
| Current-room responder / Other sources | Chooses notifications from this responder in this room or an explicit list of other sources. |
| Add notification source / Delete source | For Other sources, adds Chat, Flow or All activity selectors or removes a selector. |
| Title / content filters | Optional contains filters; blank matches any applicable title/content. |
| Prompt | Instructions for the automatic response. |
| Response context | Current-responder sources allow the notification's original thread, a child thread, room main or a new top-level thread. Other sources allow room main or a new top-level thread. |
| Trigger mode / Run location | Always, connected normal desktop or connected normal mobile. |
| Save / Cancel | Saves the rule or abandons editing. |
| Enabled / Edit / Delete | Pauses, resumes, changes or removes a saved rule. |

## Conditions and results

Other sources requires at least one source selector. Switching from current-responder to Other sources replaces an incompatible origin-thread destination with room main. Source DingDong and responding DingDong are separate choices.

These notifications come from Cobell's Notification Sender. Other Android apps' alerts use Mobile notification hooks instead.

[Choose notification sources](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/notification-sources.md).

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/dingdong-hook.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
