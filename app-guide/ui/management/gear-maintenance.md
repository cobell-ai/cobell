# Rename, duplicate or delete Gear: screen reference

Rename or copy a Gear configuration, inspect its chat usage and delete private Gear.

## Open this screen

**Desktop:** Management → Gear → a Gear. Name controls and Menu are in the detail header; Usage Status is below its attachments.

**Mobile:** Shortcuts → DingDong → Gear → a Gear → Overview.

Use a normal signed-in account for changes. The built-in System Gear has no Rename or Delete action. Mobile can duplicate it; the current desktop built-in Duplicate action fails rather than producing a private copy. Create a new System Gear manually on desktop instead.

## Desktop controls

| Control or area | Location and behavior |
|---|---|
| Name pencil | Opens the header Name field. Trimmed name must be nonblank, pass display-name validation and fit 40 characters. |
| Save / Cancel | Save sends the rename and exits edit mode on success. Cancel restores the displayed name. A failed save retains the editing state. |
| Header Back with name edits | Offers Keep editing, Leave without saving or Save and leave. A failed or invalid save keeps the detail open. This applies to the header Back action. |
| Menu → Duplicate | Immediately requests a separate private Gear using the current Gear settings and a name ending in `(copy)`; no copy-name dialog or confirmation. It does not save text still in the header Name field or automatically open/equip the copy. |
| Menu → Delete | Opens a confirmation naming the Gear. Cancel keeps it; Delete sends removal and normally returns to Management on success. |
| Usage Status | Groups owned DingDongs using this Gear by DingDong and shows chat names/IDs. These desktop chat labels are display text, not navigation controls. |
| Usage Retry | Appears on a usage-load error and reloads usage. An error is not proof that no DingDong uses the Gear. |
| Collection Edit → selected rows → Delete (count) | Starts deletion without an additional confirmation. Required built-in System Gear is excluded. Requests run in sequence and stop at the first failure; earlier deletions may already have succeeded. |

## Mobile controls

| Control or area | Location and behavior |
|---|---|
| Overview → Rename | Opens a separate Gear rename screen from the current saved source. Retry on its initial load error reloads that source. |
| Display name / Save | Required trimmed display name, at most 40 characters. The keyboard submit action also saves. Save is disabled without changes, during work or while verification is required. Verified success returns to the detail. |
| Rename Back | Confirms leaving changed or unverified input. Saving/checking blocks departure. Discarding this screen does not undo a rename request already sent or clear an unresolved result. |
| Check saved result | Replaces Save after an unverified rename; the name field is locked. Reads the saved result without resending the rename. A matching result returns to detail. A differing result shows the current saved name and retains the typed text for review. Failed checks remain retryable. |
| Overview's Check saved result | Replaces Rename while that Gear has a pending rename result. Reopens its verification screen. Duplicate and Delete stay disabled until this is resolved. |
| Overview → Duplicate | Immediately copies the saved Gear with a localized copy suffix, shortening the source name to fit 40 characters. Normally shows success and refreshes the collection; it stays on the source detail. |
| Unverified-copy notice → Open | The copy was already created but its saved settings could not be verified. Opens that existing copy; it is not a request to create another. |
| Overview → Delete | Confirmation identifies the Gear by name. Successful deletion leaves the detail; failure can restore the item in the view. |
| DingDongs using this Gear | Grouped usage rows. Tap a chat row to open that chat. Retry reloads a failed usage read. |
| Collection Select / long-press / Delete selected | Selects private Gear. The confirmation shows a count/message, not every name. Successful targets leave the selection; failed targets stay selected and the remaining requests continue. |

## What a copy contains

The copy has a new Gear identity and its own configuration. Its attachment references still point to the same Memory and Toolbox definitions; those definitions are not cloned. Reusable definition edits can therefore affect both Gears. Memory values, attachment choices and non-secret MCP device/value settings are copied as part of the Gear configuration.

Local MCP secrets, MCP browser authorization and recorded connection reports are not copied into the new Gear. Open the copy's connection settings, supply credentials on each execution device and check the connection before use. A copy does not replace an equipped Gear automatically.

## Usage scope

Usage shows related DingDong chats and may not include every use. It is not a list of all Flow nodes or of Gears using a Memory/Toolbox. Review Flow assignments separately before deletion.

## Conditions and results

Deleting a Gear does not delete its reusable Memory or Toolbox definitions, and does not choose a replacement configuration for chats or Flow nodes. Inspect usage and reassign affected setups as needed. Removing a single attachment is a separate operation.

An optimistic disappearance or generic error does not establish the final server result. Refresh the collection and inspect the original/copy before retrying rename, Duplicate or Delete. In particular, a failed desktop copy readback can follow successful creation; mobile's unverified-copy notice explicitly identifies the created copy.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-maintenance.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Gear connections and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [Create Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
