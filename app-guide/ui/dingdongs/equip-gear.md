# Equip a DingDong with Gear: screen reference

Choose the Gear used by one of your DingDongs in the current room. Preparing missing Gear and changing an existing assignment use different controls.

## Open this screen

**Desktop:** Right-click the room row → DingDong Settings. Select your DingDong in a shared room, then click the current name or Select beside Gear in use. A personal chat or settings view with missing Gear shows the setup panel instead.

**Mobile:** Open room settings → DingDong Settings → select your DingDong. A configured DingDong has a Gear dropdown. Missing setup shows Select Gear; an unconfigured personal chat offers Select Gear or Create Gear.

## Existing assignment

| Control | Behavior |
|---|---|
| Desktop Gear in use | Opens Select Gear with matching DingDong types. Names and types identify each row. |
| Desktop row | Selects one candidate locally. The current assignment is selected initially, or the first available entry if it is absent. |
| Desktop Cancel / Select | Cancel closes without assigning. Select closes the dialog and starts saving in the parent settings view; there is no further Save button. This dialog has no Create Gear or Refresh action. |
| Mobile Gear dropdown | Selecting a different Gear starts saving immediately. There is no separate Save or confirmation for this dropdown. Turn Enabled on before changing it. |
| Active / Enabled | In shared rooms, a disabled DingDong's settings below this switch cannot be changed. |

## Missing Gear setup

| Control or state | Behavior |
|---|---|
| Available Gear / radio list | Offers matching types; mobile lists private Gear owned by the signed-in user. An available current assignment is preferred, otherwise the first entry. A selected row alone does not equip it. |
| Create Gear | Desktop opens the creation dialog; mobile opens a separate creation screen. Returning reloads setup. Choose the intended compatible Gear afterward; creation does not automatically equip it. |
| Save / Saving… | Saves the selected Gear for this room. Save requires a choice and is disabled during the request; Create Gear is also disabled while saving. Mobile also disables the candidate rows. |
| Gear saved / return | Desktop shows a saved notice and refreshes setup. The mobile setup screen returns after an acknowledged save. A ready personal chat can then show its conversation. |
| No available Gear | Create Gear with the same DingDong type. Mobile also offers Retry. A Pure Gear will not appear for a System DingDong. |
| Could not load / Retry | Reload the failed setup check. Desktop's Gear-list failure also refreshes the catalog; it does not offer creation as a substitute for a failed read. |
| Close / Back | Leaving before Save discards that choice. Leaving after a request starts does not undo a possible server update. |

## Cobelly and invitation setup

Desktop's System DingDong selector includes matching System Gear and the supplied System DingDong Gear. Mobile shows Built-in default Gear in a disabled dropdown for Cobelly; it cannot select a private System Gear here.

When the mobile setup screen opens from an invitation, Save only returns the Gear choice to that invitation. Finish Invite to join the room and assign Gear. Back does not commit a new choice. If joining succeeds but equipping fails, the membership remains; open this room's DingDong Settings to complete setup.

## Conditions and results

The selected DingDong must be yours. Assignment targets this DingDong in this room; it does not change all its rooms or Flow-node settings. Editing the reusable Gear's attachments is a separate operation.

Existing settings may display a new choice before saving finishes. A failure can restore confirmed settings; mobile also reloads them after a transport error. Its error-card Retry reloads settings rather than repeating the assignment request. Check the displayed assignment before choosing again.

The setup screen stays open after a failed save, but a refreshed list can change the offered selection. Reload or reopen the current room if the result is uncertain. Signing out or losing access makes an old screen unusable. Gear is ready confirms an assignment, not device permissions, browser sign-in or successful tool execution.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Create Gear from Memories and Toolboxes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [Invite your DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/invite-to-room.md)

Reviewed: 2026-10-23. UI labels use the English app language.
