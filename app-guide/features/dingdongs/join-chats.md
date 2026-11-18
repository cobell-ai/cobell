# Join several chats with one DingDong

Choose existing chats from an owned bot's management detail. This is separate from selecting several bots inside one room.

## Desktop steps

1. Open Management → Pure → the bot → Chat → Join in the Chats list header. Join is outside edit mode.
2. Select available friend direct or group chats using their rows or checkboxes. Hidden, closed and already-joined rooms are omitted. For a personal multi-DingDong group, invite from that room instead.
3. Choose Join (count), then complete the Gear setup shown for the selected rooms. Cancel stops the remaining work; changes already saved remain saved.
4. Check the result for each room. Some joins may succeed while others fail or remain unconfirmed. Successful joins stay completed; inspect current participants before retrying unfinished rooms.
5. Check participants after an uncertain result before choosing Join again. Once all pending rooms succeed, the dialog closes. Cancel leaves the dialog when it is not busy; it does not undo earlier successful joins or Gear saves.

The dialog has no search or invitation-status-check control. The DingDong's invitation policy must be on.

The header Close button is disabled while submitting. Esc can still dismiss the active join or setup dialog. Dismissal does not undo a request already sent; inspect membership and saved Gear before resuming.

## Mobile steps

1. Open Shortcuts → DingDong → your Pure → Chats → Join chats.
2. Check available room rows. The screen uses the current visible chat directory, including eligible owner-only multi-DingDong rooms. Existing joins remain checked and unavailable. Closed rooms, group guest restrictions or incomplete room information have explanatory labels.
3. Shared-chat targets wait for the invitation policy to load and require it to be on. Owner-only multi-DingDong rooms do not require that policy. Retry on a failed policy read reloads it.
4. Choose Join selected chats (count). Complete Gear setup when prompted. Back without choosing stops the remaining work.
5. Review each room's join and Gear result. If the bot joined but Gear setup is incomplete, finish it in the room's DingDong Settings.
6. Review the joined and failed counts. Earlier successful joins remain completed. Check each unfinished room's current participants and Gear before submitting again.

Back with selected rooms asks whether to discard the selection. It is disabled while saving. Discarding a selection does not undo successful joins. If the Gear editor was canceled after earlier rooms joined, those joins remain.

## Limits and recovery

Only the current normal account can join its own supported bots; preview mode and agent sign-in do not authorize this flow. Cobelly is excluded. A selectable row does not guarantee the server will accept the invitation: policy, blocking and membership can change.

After a network error, a room can have accepted the invitation even if the screen reports failure. Reopen participants and inspect Gear before retrying. The joined count records progress in the current screen; it is not a promise that every attempted room has finished setup.

## Related guides

[Browse the bot's chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/browse-chats.md)

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/join-chats.md) · [Invite bots from one room](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-to-room.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Invitation policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
