# Change DingDong behavior in a room

Set how an owned DingDong responds in one room: mode, intelligence, intermediate messages, Bell access and automatic replies.

## Start here

**Desktop:** Right-click the room row → DingDong Settings; select the intended owned DingDong at the top.

**Mobile:** Chat → room settings → DingDong Settings. The top dropdown appears when several of your DingDongs are present.

## Choose response behavior

1. Open the intended room and select your DingDong. Complete [Gear setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) if it appears first.
2. Turn Active on in a desktop shared or multi-DingDong room, or Enabled on in mobile, to use the controls below it. Desktop individual rooms have no Active switch; mobile displays one there too.
3. Choose Questioner to discuss open choices during work, or Decider to let it select an approach and ask essential questions. Desktop Pure uses segments, Cobelly uses a popup, and mobile uses a dropdown. These choices save directly.
4. Drag Intelligence Level from 1–7 and release to save it. The moving label is a preview until release.
5. Choose whether to emit intermediate thinking messages: Show inner thoughts → Off/On on desktop; Show thinking and working messages → Show/Hide on mobile. Existing chat messages remain.

Cobelly's Start/Home mode control uses the same saved setting. Wait for saving to finish before the next request. Desktop Mode unavailable → Retry reloads a failed mode read; it does not let you select a new mode until the read succeeds.

## Goal Mode

Goal Mode is off by default. Enable it in DingDong Settings to clarify and pursue a goal on runs started with the Bell in this chat. Running or paused runs keep their original setting. Resuming a failed run uses the setting at the time you resume it.

## Set other people's Bell access

1. In a one-to-one chat with another person, use Other Party or Bell permission → Allowed/Not Allowed.
2. In a group, choose no other participants, everyone, selected people or everyone except selected people. The selected policy saves immediately. The owner keeps Bell permission while the bot is enabled.
3. For a selected-people policy, open Allowed Users/Allowed people or Excluded Users/Excluded people. Check the intended human participants; the owner and bots are not offered.
4. Desktop: Confirm applies the list and Cancel abandons it. Mobile: Save applies it and Back abandons it. Checkbox changes alone are drafts.
5. Check the applied policy and list. An empty allowed list permits no other people; an empty excluded list excludes none. Switching policy does not clear either saved list.

These controls do not share a personal DingDong room with other people. Its access remains owner-only.

## Example: share a personal food expert with selected friends

Assume a Pure DingDong has access to a food map and visit notes collected from ten years of the owner's own restaurant visits. Prepare exported map data in its KnowledgeBox or configure an appropriate tool for the map service; there is no implied automatic integration with every map provider.

1. Invite that DingDong into the friends' group chat and check the Gear assigned in that room.
2. Set Bell access to selected people. Select Leo in the allowed list and Confirm/Save it, leaving Maya unselected.
3. Leo can ask for a quiet dinner spot and ring the Bell. Maya's room membership alone does not let her call the DingDong. The owner retains access.
4. An ordinary shared answer remains readable by the room's participants, including Maya. Bell permission does not make the response private or transfer ownership of the bot, its resources or tools.

The invitation, Bell access and Gear/resource access are separate settings. Use the same selected-people policy when allowing particular colleagues to request work through an owned DingDong.

## Configure automatic replies

1. Turn Auto Reply on: Off/On on desktop, Not Allowed/Allowed on mobile. The remaining controls appear below it.
2. Choose which messages count. In shared chats, My messages only limits counting to yours; the other choice also includes eligible messages from humans with Bell permission. Personal rooms, including personal DingDong groups, require owner-only counting.
3. Choose a reply interval from the available 1–7 message settings. Desktop uses a dropdown; mobile uses a slider and saves on release. This is a message interval, not a timer or guaranteed response schedule.
4. To wait before an automatic reply, check Reply Delay or Wait before replying. It starts at 5 seconds. Set 5–30 seconds with the slider and release to save. Unchecking saves 0; re-enabling starts at 5 again.
5. Send an eligible message in the intended conversation or thread and check the result. AI-hidden messages do not trigger automatic replies. Mentioning the bot can request an immediate response separately from the automatic delay.

In personal DingDong rooms and groups, keep Reply only to my messages selected. Desktop can hide this setting when it is required; mobile can show it as locked.

Turning Auto Reply off hides interval and delay without clearing them. Schedules and notification hooks have separate [routine controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md).

## Completion, limits and recovery

Most controls save immediately; there is no final page-wide Save. A slider saves on release, and a people list saves on Confirm/Save. Leaving does not undo a request already sent. Check an uncertain saved value before repeating the change.

If a change fails or its result is uncertain, reopen the current settings or use Retry to read saved values before changing them again. Reopen the people picker after account, room or access changes.

Response settings affect the selected DingDong in this room. The separate [new-chat invitation policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md) controls future invitations across chats.

Also find this under: auto reply, intelligence level, mode, permissions, active bot.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/behavior.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

[Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Schedule an automatic DingDong response](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/scheduler.md)

Reviewed: 2026-10-24 (Bell permission and food-map sharing example). UI labels use the English app language.
