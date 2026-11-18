# Control new shared-chat invitations: screen reference

Allow or prevent your Pure DingDong from joining new chats with other people.

## Open this screen

**Desktop:** DingDong Settings → Allow invites to friend chats. A locked management profile also has a lock icon that opens the policy dialog.

**Mobile:** Shortcuts → DingDong → your Pure DingDong → Chats → Allow invites to friend chats. This switch is on the management Chats tab, not the room's DingDong Settings screen.

## Controls

| Control or area | Location and behavior |
|---|---|
| Allow invites to friend chats | Changes the owned bot's future shared-chat invitation policy immediately; no Save or confirmation follows. |
| Desktop policy switch | In settings or the lock dialog. Disabled while the same bot's policy is updating; Cobelly's policy is immutable. |
| Desktop lock icon | Appears on a management profile when invites are off. Opens Invites to chats with other people are off with the policy explanation and switch. |
| Desktop Close | Closes the policy dialog. Its button is disabled while updating. This dialog has no Retry button. |
| Mobile policy switch | On the owned bot's active management Chats tab. Disabled during loading/saving or while no policy is available. A false-looking disabled switch during loading is not a confirmed off policy. |
| Mobile Retry | Appears when there is no usable policy after a failed read. Reloads the policy; it does not repeat an update. An explicitly rejected update can retain the prior value with a save error and no Retry button. |

## Conditions and results

This policy belongs to the DingDong, across rooms. It changes future invitations into chats with other people; it does not remove existing memberships. Mobile permits owner-only multi-DingDong joins with the policy off. The current desktop room invitation picker also locks those candidates with the policy off. Bell permission and automatic replies have separate room settings. Cobelly cannot be invited into another chat regardless of this policy.

The switch can show the requested value before saving finishes. Desktop can restore the prior value after rejection and refreshes the bot list after an uncertain response. Mobile restores an explicitly rejected value; for an uncertain write it withholds the policy and reads it again. If that read also fails, use Retry and inspect the result before toggling again. Closing or navigating away does not undo a write already sent.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Invite your DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-to-room.md) · [Change room behavior](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/behavior.md)

Reviewed: 2026-10-23. UI labels use the English app language.
