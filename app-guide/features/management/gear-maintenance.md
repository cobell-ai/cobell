# Rename, duplicate or delete Gear

Maintain a Gear's name and configuration without cloning its reusable Memory or Toolbox definitions.

## Start here

**Desktop:** Management → Gear → the Gear detail header/Menu and Usage Status.

**Mobile:** Shortcuts → DingDong → Gear → the Gear → Overview.

## Rename on desktop

1. Use the pencil beside the name. Enter a nonblank display name of at most 40 characters.
2. Choose Save. Cancel restores the name without sending an update.
3. If leaving through the header Back button with changes, choose Keep editing, Leave without saving or Save and leave. Invalid values or a failed save keep you in the detail.

## Rename and verify on mobile

1. Open Overview → Rename. This opens a separate screen. If its saved source cannot load, use Retry.
2. Edit Display name, at most 40 characters, and Save or submit from the keyboard. A verified success returns to detail.
3. If the result is unverified, the field locks and the button becomes Check saved result. Use it before another write. It only reads the saved state; it does not send the rename again.
4. A matching result returns to detail. If settings differ, review the reported current name and your retained typed text before deciding whether to save again. Failed checks remain available for retry.

Back with edited or unverified input asks whether to discard the screen. Saving/checking blocks departure. Leaving does not undo a request or clear an unresolved result. On Overview, Check saved result reopens this screen while verification is pending; Duplicate and Delete remain disabled until it is resolved.

## Make a separate Gear configuration

On desktop, use Menu → Duplicate. On mobile, use Overview → Duplicate. The action starts immediately without a copy-name dialog or confirmation. It adds a localized copy suffix; mobile shortens the source name to stay within 40 characters. Desktop does not save text still being edited in the name field. Both platforms normally leave you on the original detail; find the copy in the refreshed Gear collection.

The new Gear has its own identity, attachment choices and values. It still references the original Memory and Toolbox definitions. Editing one of those reusable definitions is different from editing the copy's Gear values.

Non-secret MCP settings can be copied, but local credentials, MCP browser authorization and connection reports are not. Open the copy's Toolbox settings on each execution device, authenticate and check it before use. Equip the copy separately; duplication does not replace existing assignments.

If mobile reports that the copy was created but settings are unverified, use Open to inspect that copy. Do not assume that connections are missing or press Duplicate again to repair them. After a generic failure on either platform, inspect the collection before repeating the request: creation may have succeeded before its readback failed.

Built-in System Gear cannot be renamed, deleted or have its configuration changed. Mobile supports making a private copy of it. The current desktop built-in Duplicate action fails; use [Create Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) with System type for a separate editable configuration. See [System Gear attachment limits](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) for required components and the desktop/mobile Gear selection difference.

## Inspect usage before deleting

Desktop Usage Status and mobile DingDongs using this Gear show owned DingDong/chat configurations matching this Gear. On desktop the chat names/IDs are display text. On mobile, tap a chat row to open it. Use Retry after a usage-load error; do not interpret a failed read as no usage.

This list may not show every use of the Gear. Inspect Flow node assignments separately and choose replacements before deleting it.

## Delete one Gear or several

- **One Gear:** Desktop Menu → Delete or mobile Overview → Delete opens a confirmation naming the target. Confirm to remove it. The detail normally returns to Management or its prior route after success.
- **Desktop collection:** Edit → select eligible Gear → Delete (count) starts immediately without another confirmation. Review the selection first. Processing stops at the first failed request, so earlier items may already be deleted.
- **Mobile collection:** Use Select or long-press, review the selected names, then Delete selected. Its confirmation shows the count/message rather than all names. It continues after failures; successful targets leave selection and failed ones remain selected.

The built-in System Gear is excluded. Deleting the Gear keeps the original Memory/Toolbox definitions. It does not automatically assign a replacement Gear to chats or Flow nodes.

## Completion, limits and recovery

Use a normal signed-in account for changes. After an uncertain deletion, refresh and inspect saved state before retrying: a temporarily removed row or a restored row after an error is not final confirmation. Removing an attachment from a Gear is separate from deleting the Gear itself.

Also find this under: copy Gear, rename configuration, remove Gear, usage.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/gear-maintenance.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Gear connections and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) · [Create Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-create.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
