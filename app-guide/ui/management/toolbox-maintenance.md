# Rename, duplicate or delete a private Toolbox: screen reference

Maintain a saved MCP connection definition. Gear attachments, per-Gear values and device credentials are separate.

## Open this screen

**Desktop:** Management → Toolbox → a private entry. The header has a pencil and Menu; its body embeds the MCP connection editor.

**Mobile:** Shortcuts → DingDong → Toolbox → a private entry → Overview. Toolbox schema opens the MCP connection editor.

## Names and editing

| Control | Behavior |
|---|---|
| Desktop pencil / Custom name | Opens the display-name dialog. Uncheck Use the MCP server name as-is to enter a nonblank custom name, then Save. The server accepts up to 40 characters. Cancel abandons the dialog draft. |
| Use the MCP server name as-is | Clears the custom-name draft and, on Save, removes the override. This uses the saved base name; it does not contact the MCP server for a fresh name. |
| Desktop Save / Enter | Saves the custom-name choice and closes on success. Save/Cancel are disabled while saving. Failure stays in the dialog and can restore the earlier saved value. |
| Desktop collection name | Displays and sorts the base Name, while detail can display Custom name. A custom-name edit can therefore leave the desktop collection label unchanged. |
| Mobile Overview → Rename | Renaming is currently unavailable through this mobile action. Close the form and check the saved name. |
| Toolbox schema → Name → Save | Supported mobile route for editing the base name. It preserves an existing custom-name override, so the catalog may still show that override. Use desktop's pencil to change or remove the override. |
| MCP connection form | Edits the reusable definition, rather than just its display override. Save before leaving; its unsaved draft is not included by Duplicate. See [connection editing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md). |

## Duplicate

| Control or result | Behavior |
|---|---|
| Desktop Menu → Duplicate | Immediately creates a private Toolbox from the stored definition and supported types. Uses the displayed name plus the copy suffix as Custom name. The original detail stays open. |
| Mobile Overview → Duplicate | Reads the saved definition, then creates a new private Toolbox and reloads the catalog. It uses the base name with a copy suffix, truncated to 40 characters. The original detail stays open. |
| Copy name | A long mobile name can lose its copy suffix after truncation. On desktop, a displayed name plus suffix over 40 characters is rejected; shorten its Custom name first or create a separately named connection. |
| Copy contents | The MCP definition and supported types are copied. Its image, Gear attachments, per-Gear values, local credentials, OAuth authorization and check reports are not copied. Attach and configure the copy separately. |
| Failure or uncertain response | Inspect the collection before pressing Duplicate again; a lost response or failed read can leave an already-created copy. |

Changing the original definition can affect every Gear that references it. Duplicating creates another identity and does not replace those references.

## Usage and removal

| Control | Behavior |
|---|---|
| Mobile Overview → Gear in use | Reads matching Gear connections in this account's catalog. Tap a Gear row to open its detail. This is not a list of running DingDongs. |
| Usage Retry | Reloads Gear connection information for the usage read. It does not check the MCP server. |
| Desktop private detail | To find references, open candidate Gears and inspect their connections. There is no Usage section in this private editor. |
| Individual Delete | Desktop Menu → Delete or mobile Overview → Delete opens a name-specific confirmation. Confirm deletes the private definition; Cancel keeps it. Successful deletion returns to management when the original page still owns navigation. |
| Desktop collection Edit → Delete (count) | Starts sequential deletion without another confirmation and stops on the first failure. Earlier items may already be gone. Cancel/Escape clears selection while idle. Built-in rows can also be checked here, but deleting them is a no-op; use the P filter to target private entries. |
| Mobile Select / long-press → Delete selected | Confirms a count/message, then continues after individual failures. Successful entries leave selection; failed entries remain selected. Review names before confirming. Built-ins are information links, not delete targets. |

Deleting a Toolbox keeps Gear and Memory definitions. Existing Gear can retain an unavailable Toolbox reference; remove or replace it in [Gear connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md). A failed or uncertain deletion needs a refreshed collection before retrying.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-maintenance.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Browse collections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) · [MCP authentication and checks](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [Toolbox images](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/object-images.md)

Reviewed: 2026-10-23. UI labels use the English app language.
