# Rename, duplicate or delete a private Toolbox

Maintain the saved connection definition. Its use in Gear and each device's authentication are configured separately.

## Start here

**Desktop:** Management → Toolbox → private Toolbox → header pencil or Menu.

**Mobile:** Shortcuts → DingDong → Toolbox → private Toolbox → Overview. Open Toolbox schema for its saved MCP connection form.

## Change a name

1. On desktop, use the header pencil. Uncheck Use the MCP server name as-is, enter a nonblank Custom name of up to 40 characters, then Save. Enter also submits. Cancel leaves the saved name unchanged.
2. To remove that override, check Use the MCP server name as-is and Save. This restores the saved base name without checking the MCP server.
3. Desktop's collection still displays and sorts the base Name; the custom display name appears in detail. Mobile's catalog uses a custom name when one exists.
4. On mobile, Overview → Rename currently fails to save. To edit the base name, open Toolbox schema → Name and Save. This preserves an existing custom-name override; use desktop's pencil to change or remove that override.

The MCP form edits the reusable definition. Its changes can affect every Gear that attaches this Toolbox. It has no unsaved-discard confirmation; save before leaving. See [MCP connection editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md).

## Make a separate copy

1. Use desktop Menu → Duplicate or mobile Overview → Duplicate. It starts immediately without a naming or confirmation dialog and normally leaves the original detail open.
2. Return to the collection and find the new private Toolbox. Mobile copies the saved base name and truncates the copy name to 40 characters, which can remove its suffix. Desktop appends the suffix to the displayed name as an override; shorten a long Custom name first if that exceeds 40 characters.
3. Review the copied definition and supported types. Its image, Gear connections and per-Gear settings are not copied.
4. Attach the copy to the intended Gear, choose devices and values, and enter local credentials or authorize it separately. The original's OAuth state and connection reports are not copied.
5. After an error or lost response, inspect the collection before duplicating again. The new entry may already exist.

Duplicate uses stored definition data, not unsaved text in an open MCP form, and does not switch existing Gear to the copy.

## Find references before deleting

On mobile, Overview → Gear in use lists matching Gear connections in this account's catalog. Tap a Gear to inspect it. Retry reloads connection information if the usage read fails. These are configuration references, not currently running DingDongs.

The desktop private MCP detail currently has no Usage section. Inspect candidate Gear's connections manually. Built-in Toolbox pages use separate information and usage layouts.

## Delete one or several definitions

1. For one item, use desktop Menu → Delete or mobile Overview → Delete. Read the name in the confirmation and confirm, or Cancel to keep it.
2. For desktop bulk deletion, filter P, choose Edit and select the private rows. Delete (count) starts without another confirmation and stops at the first failure. Built-in rows can be selected but will not be removed. Cancel/Escape clears an idle selection.
3. For mobile bulk deletion, use Select or long-press, select rows, then Delete selected. Its confirmation shows a count/message. Processing continues after failures, leaving failed items selected.
4. Refresh after a partial or uncertain result before retrying. Successful deletions are not rolled back because a later item failed.
5. Open affected Gear → [connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) to remove or replace unavailable references. Deleting Toolbox does not delete Gear or Memory.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/toolbox-maintenance.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Browse collections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [Toolbox images](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/object-images.md)

Reviewed: 2026-10-23. UI labels use the English app language.
