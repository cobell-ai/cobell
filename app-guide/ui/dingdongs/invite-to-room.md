# Invite your DingDong into a chat: screen reference

Select owned bots, review Gear, then invite them into one existing room.

## Open this screen

**Desktop:** Chat Room Settings or DingDong Settings → Invite DingDong.

**Mobile:** Room settings → Invite DingDong → DingDong Settings → Invite DingDong. The empty settings screen also has an invitation action.

## Desktop controls

| Control or area | Behavior |
|---|---|
| Pure row | Toggles selection. Existing participants are omitted; policy-locked bots cannot be selected. |
| Next / Next (count) | Opens Gear review for the current selected bots. Disabled without an eligible selection. |
| Gear dropdown | Chooses matching Gear per bot. A first compatible entry can be preselected. No inline creation control. |
| No Gear | Prevents Invite until all bots have matching Gear. Create it through management. |
| Back | Returns from Gear review to selection; usable draft Gear choices remain. |
| Cancel | On selection step, closes without submitting the draft. |
| Header Close | Closes the dialog, including during submission. A sent invitation is not undone. |
| Invite / Saving | Requests the selected invitations and Gear setup. Footer actions are disabled while submitting. Check each result before retrying. |
| Result notice | Success closes the dialog; rejected/unconfirmed results leave it open when still current. Gear-incomplete notice means membership succeeded and room setup needs review. |

## Mobile controls

| Control or area | Behavior |
|---|---|
| Pure candidate row | Selects/deselects the owned bot. Existing participants are omitted. Policy locks prevent selection in shared chats. |
| Catalog/policy Retry | Reloads the failed read; does not send an invitation. |
| Review Gears | Moves to the selected bots' Gear review. |
| Gear row | Selects that bot's draft matching owned Gear. |
| Per-bot Retry | Reloads the Gear check/list. Review the resulting selection. |
| Select Gear | Offered when no Gear choices are available. Opens setup; Save returns the editor's explicit selection to the draft, while Back does not choose a new one. |
| Review Back | Returns to bot selection. |
| Invite | Requires loaded data and a valid Gear for each selected bot. Busy state disables draft actions. |
| Close / route Back | Leaving a draft does not submit it. After a request starts, inspect membership and Gear even if you leave the sheet. |
| Gear failure notice | The DingDong joined. Finish Gear in that room's DingDong Settings. |

## Conditions and recovery

Group guests cannot add bots. Cobelly and single personal bot chats are excluded. People-invitation manager restrictions are a separate policy. The bot's block list and new-chat policy can reject an invitation.

Desktop's current picker also locks an owner-only multi-DingDong candidate when its invitation policy is off. Mobile bypasses that policy for owner-only multi-DingDong rooms. Existing memberships are not removed by changing the policy.

There is no dedicated invitation-status check button here. Inspect the current room's participants and Gear after an uncertain response before repeating Invite. A temporary participant row does not prove completion.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-to-room.md) · [Management Join controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/join-chats.md) · [Invitation policy](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/invite-policy.md) · [Gear setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
