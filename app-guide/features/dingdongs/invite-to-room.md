# Invite your DingDong into a chat

Choose owned DingDongs and Gear for an existing room. Use the separate management flow to [join several chats with one bot](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/join-chats.md).

## Start here

**Desktop:** Chat Room Settings or DingDong Settings → Invite DingDong.

**Mobile:** Room settings → Invite DingDong opens DingDong Settings. Use its Invite DingDong control, including the empty-state action, to open Invite my DingDongs.

## Desktop steps

1. Select one or more eligible Pure DingDongs. Already participating bots are omitted; locked bots cannot be selected.
2. Choose Next or Next (count). For each selected bot, review the Gear dropdown. A compatible first entry can already be selected; do not assume it is the bot's personal-chat Gear.
3. Choose matching Gear for every bot. No Gear disables Invite; this dialog has no inline Gear creation control. Create compatible Gear through management, then return.
4. Back returns to bot selection and keeps usable Gear choices. Cancel on the selection step or the header Close abandons the local draft.
5. Choose Invite. The footer controls are disabled while submitting. The header Close can still close the dialog; closing does not undo an invitation already sent.
6. Check the room's participants and each bot's Gear. An acknowledged invitation closes the dialog, including when some Gear settings need attention. Open that room's DingDong Settings to finish setup.

The current desktop picker requires Allow invites to friend chats to be on even for a multi-DingDong owner-only room. Do not apply the mobile exception below to this picker.

## Mobile steps

1. In Invite my DingDongs, tap one or more available Pure rows to select or deselect them. Already participating bots are omitted. Wait for the catalog and applicable invitation policies to load.
2. Choose Review Gears. Each bot has its own matching owned Gear choices. A current usable assignment or first available entry can be selected automatically; review it.
3. Tap a Gear row to change that bot's draft. Retry reloads its Gear check. If no compatible Gear is available, Select Gear opens the setup editor, where you can create/select Gear. Save returns an explicit choice to this invitation; it does not equip the room yet. Back from the editor does not choose a new Gear.
4. Back in Review Gears returns to bot selection. Finish Invite only after every selected bot has a valid Gear. Catalog/policy errors have their own Retry, which reloads information rather than repeating an invitation.
5. Choose Invite and check each selected bot's result. If the bot joined but Gear setup is incomplete, finish it in that room's DingDong Settings.

Mobile applies this bot-wide invitation policy to chats with other people. Owner-only multi-DingDong groups remain eligible when the policy is off. Cobelly is not eligible on either platform.

## Limits and uncertain results

Use a normal account and your own bots. Group guests cannot add DingDongs. The people-invitation manager policy is separate from permission to invite your own bots. A bot owner's block of someone in the room or their new-chat policy can reject an invitation. Single personal bot chats are not invitation targets.

Neither invitation surface has a dedicated Check invitation status button. After a lost response or generic failure, reopen the current participant list and inspect Gear before submitting again. A temporary row or a closing dialog alone does not prove completed membership and Gear setup. Closing or switching accounts after sending does not roll back server changes; reopen from the current account.

The invitation selects room membership and Gear. It does not send a chat message or request an AI response. [Bell permissions and Auto Reply](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/behavior.md) are separate room settings.

## Related guides

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/invite-to-room.md) · [Join several chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/join-chats.md) · [Invitation policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Remove from one room](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/remove-from-room.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
