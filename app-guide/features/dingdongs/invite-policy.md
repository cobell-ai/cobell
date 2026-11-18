# Control new shared-chat invitations

Allow or prevent your Pure DingDong from joining new chats with other people.

## Start here

**Desktop:** Open DingDong Settings → Allow invites to friend chats, or use the lock icon on a locked management profile.

**Mobile:** Shortcuts → DingDong → your Pure DingDong → Chats → Allow invites to friend chats. The room's DingDong Settings screen does not contain this switch.

## Desktop steps

1. Open the owned DingDong's settings. If its management profile shows a lock, that icon also opens the policy dialog.
2. Change Allow invites to friend chats. It saves immediately and is disabled while updating; there is no extra confirmation.
3. Wait for the result. A rejected update can restore the old value; an uncertain result refreshes the bot list. The dialog has no Retry button.
4. Close the dialog when its Close button becomes available, then return to the invitation flow if this policy previously blocked it.

## Mobile steps

1. Open Shortcuts → DingDong → the bot detail.
2. Open Chats and wait for the policy above the chat list. If it failed to load, use Retry. A disabled switch during loading does not confirm that invites are off.
3. Change Allow invites to friend chats. This starts saving immediately. Wait for saving or any follow-up read to finish.
4. If an uncertain write is followed by a failed read, use Retry to read its result before changing the switch again. A rejected write can leave the old value with an error and no Retry button.
5. Return to the chat invitation screen after confirming the desired policy.

## Completion, limits and recovery

This is a bot-wide invitation policy. It affects future invitations into chats with other people and keeps existing memberships. Mobile still allows owner-only multi-DingDong joins when it is off. The current desktop room invitation picker also locks those candidates when it is off; enable the policy before using that picker. Cobelly's policy cannot be changed to allow invitations.

Bell access and Auto Reply remain separate [room behavior settings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/behavior.md). Leaving a screen does not undo a policy update already sent; inspect the current saved value before repeating an uncertain change.

Also find this under: shared invite policy, locked DingDong, future chats.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/invite-policy.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

[Invite from a room](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-to-room.md) · [Join several chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/join-chats.md)

Reviewed: 2026-10-23. UI labels use the English app language.
