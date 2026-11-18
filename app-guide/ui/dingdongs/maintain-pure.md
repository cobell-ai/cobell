# Rename or delete a Pure DingDong: screen reference

## Open this screen

**Desktop:** Management → Pure → card Menu, or open the bot → Menu. Use collection Edit for several bots.

**Mobile:** Shortcuts → DingDong → owned Pure → Overview. Use Select or long-press in the collection for several bots.

## Controls

| Control or area | Behavior |
|---|---|
| Desktop detail Menu → Info | Shows date information. Do not treat Updated as a modification history. Close returns without changing the Pure. |
| Desktop card/detail Menu → Rename | Opens New name. Save or Enter validates and closes before the request finishes. Cancel/dismiss before submission keeps the name. |
| Mobile Overview → Rename | Opens Display name with the existing name. Save/Done validates; progress disables field/Save/Cancel. Failure keeps draft with inline error; success closes. Outside/Back dismissal is still possible and does not cancel a sent request. |
| Name validation | Use a 1–40-character name with supported letters, numbers and underscores. Follow any name error shown by the form. |
| Desktop card/detail Menu → Delete | Confirm deletion → Delete sends the request. Cancel/dismiss makes no request. Detail returns before completion; card path waits and reports failure. |
| Mobile Overview → Delete | Named confirmation → Delete permanently. Cancel/dismiss makes no request. Successful deletion returns to Shortcuts. |
| Delete profile image | Separate image-only action; does not delete the DingDong identity. |
| Desktop collection Edit | Cards/checkmarks toggle selection instead of opening detail. Delete (count) enabled when selected; **no additional deletion confirmation**. Cancel/Esc clears selection before the batch. |
| Desktop deletion in progress | List interactions and Cancel disabled. Attempts every selected bot; failures stay selected, error shown. Successful deletions are not rolled back as a batch. |
| Mobile Select / long-press | Enters selection. Rows/checkmarks toggle selected bots. Cancel selection or Back clears selection before deletion. |
| Mobile Delete selected | Opens count confirmation; confirm Delete selected runs the batch. Cancel closes confirmation. Selection and Back blocked while deleting; failed rows remain selected while later rows continue. |
| Collection Refresh / failed-read Retry | Reads current list; does not repeat rename/delete. Use after an uncertain result before sending again. |
| Mobile personal chat room-name editor → Check status | For an uncertain rename, reads its saved outcome without sending the name change again. Management Rename may refuse new writes until that pending outcome is resolved. |

## Conditions and results

Owner's Pure only. Mobile preview/agent login disables maintenance. Cobelly's fixed system identity is outside this flow. Rename can be optimistic; a closed desktop editor or immediate name change does not prove persistence. Desktop can optimistically remove a deleted item and restore it on failure; mobile confirms the deletion before removing a Pure from its collection. A failed response can still follow a committed server deletion. Refresh and inspect before retrying.

Deletion has no restore/Undo. It deletes the owned Pure and personal chat. Removing it from one shared room, deleting only its image and deleting Gear are separate actions. Reopen an old editor from the current account after access changes.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/maintain-pure.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Create a Pure DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/create-pure.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [Control new shared-chat invitations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/invite-policy.md) · [Inspect profile and image](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/profile-and-image.md)

Reviewed: 2026-10-24. UI labels use the English app language.
