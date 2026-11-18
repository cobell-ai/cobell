# Rename or delete a Pure DingDong

Manage an owned identity from its collection or detail. Removing a bot from one shared room uses that room's participant controls.

## Check the displayed dates

On desktop, open Management → Pure → the bot → Menu → Info to view its dates. Do not treat Updated as a modification history. Close returns without changing the Pure.

## Rename

**Desktop:** Management → Pure → the card's Menu → Rename, or open the bot → Menu → Rename. Enter New name and Save, or press Enter. The dialog closes before the save finishes; Cancel or dismissing it beforehand keeps the existing name.

**Mobile:** Shortcuts → DingDong → owned Pure → Overview → Rename. Edit Display name and Save or keyboard Done. Validation is shown on submission. Saving disables the field, Save and Cancel; success closes the editor. Failure retains the draft and shows an inline error. The dialog can still be dismissed by Back/outside; this does not undo a request already sent.

Use a 1–40-character name with supported letters, numbers and underscores. Check the name field's error message if it is not accepted.

The displayed name may change optimistically and return to its previous value on failure. Check it after saving settles or refresh the collection; closing the desktop editor is not proof of success. Mobile can keep an uncertain name update pending and refuse another rename. If needed, open the personal chat's room-name editor and use Check status to read the saved result before trying a new value.

## Delete one DingDong

1. Desktop: card Menu → Delete, or open the bot → Menu → Delete. Read Confirm deletion and choose Delete. Cancel or dismissing the confirmation makes no request.
2. Mobile: Overview → Delete, read the named confirmation, then Delete permanently. Cancel or dismissing it makes no request.
3. Check the collection afterward. Desktop's detail route can return to management before deletion finishes; the card flow waits for its result. Mobile returns to Shortcuts after success. A failed request can retain or restore the item.

Deletion has no restore/Undo control. It deletes the owned Pure and personal chat. Deleting only its profile image is a separate menu action and keeps the bot. Deleting a Pure is also different from deleting Gear or removing its membership from one shared room.

## Delete several from the collection

- **Desktop:** Management → Pure → Edit. Select cards or checkboxes, then Delete (count). This starts deletion **without an additional confirmation**. Cancel or Esc leaves selection before deletion; Cancel and list interactions are disabled during the batch. Each selected bot is attempted; failures remain selected and show an error. Successful deletions stay deleted if another fails.
- **Mobile:** In the DingDong collection choose Select, or long-press a row. Tap rows/checkboxes to select, then Delete selected. Review the count and confirm Delete selected. Cancel dismisses the confirmation without deleting. Cancel selection or Back before deletion clears selection. While the batch runs, selection/deletion controls and Back are blocked. Failed items remain selected for review/retry while other items continue.

After a connection error, refresh before retrying a retained item. The backend can have committed a deletion before the response failed. Refresh/Retry on a list error reads the collection; it does not repeat the delete request.

## Ownership and related settings

These actions require your own Pure and a normal signed-in account. Mobile preview and agent login do not offer identity maintenance. Cobelly's system identity is not created, renamed or deleted through these controls. Reopen from the current account if ownership/access changes or an old dialog closes.

To change instructions or tools, edit/equip Gear. To keep the identity while preventing new invitations, change its invitation policy. To remove it only from a shared room, use that room's participant-removal action.

Also find this under: rename bot, delete Pure, permanent deletion, bulk delete, failed selection, Check status.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/maintain-pure.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

[Create a Pure DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/create-pure.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Control new shared-chat invitations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-policy.md) · [Inspect profile and image](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/profile-and-image.md)

Reviewed: 2026-10-24. UI labels use the English app language.
