# Use another Android app’s notifications as a trigger: screen reference

Configure a Mobile notification hook and grant observation access on the Android device.

## Open this screen

**Desktop:** Routine → Mobile notification hook, or DingDong Settings → Mobile Notification Hook → Add.

**Mobile:** Shortcuts → Routine → Create → Mobile notification hook. Flow → Hooks and scheduler → Mobile notification hooks also manages these rules and Android observation access.

## Controls

| Control or area | Behavior |
|---|---|
| App Filter | Optional Android app/package filter. |
| Title / content filters | Optional contains-match text filters; blank accepts any applicable text. |
| AI-response target / Prompt | Chooses a room/responder and its instructions. |
| Response context | For AI response, room main or a new top-level thread. |
| Target Flows | For Flow rules, selects one or more saved Flows. |
| Notification access on this device | Mobile Flow-hook settings show Android observation permission or unsupported status. |
| Open notification access settings | Opens Android’s notification access settings when Cobell needs access. To withdraw it while granted, open Android’s notification access settings directly. |
| Retry | Rechecks failed access or rule data. |
| Save / Enabled / Edit / Delete | Saves and maintains the rule. |

## Conditions and results

Android notification hooks do not have the Always/Desktop/Mobile trigger-mode selector used by DingDong hooks and Schedulers. Observation requires an Android device with notification access. Creating a rule does not grant that access.

iOS can manage server rules for another Android device but cannot observe its own other-app notifications. Permission to observe notifications is separate from permission to display Cobell OS notifications.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/android-hook.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/README.md)

Reviewed: 2026-11-25. UI labels use the English app language.
