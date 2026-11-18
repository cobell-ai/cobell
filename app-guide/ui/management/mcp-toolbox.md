# Create or edit a private MCP Toolbox: screen reference

Register the reusable connection, then configure execution devices and actual values in Gear.

## Open this screen

**Desktop:** Management → Toolbox → Add (or Create Toolbox in an empty collection). Existing private Toolbox detail embeds the MCP connection form.

**Mobile:** Shortcuts → DingDong → Toolbox → Create (+). For an existing private item, open Toolbox schema to edit MCP connection.

## Controls

| Control or area | Location and behavior |
|---|---|
| Name | Required trimmed name of at most 40 characters. It is not filled from a server connection check. Display-label restrictions also apply when saving. |
| Transport | stdio by default, or Streamable HTTP. Switching keeps the open fields' text; Save includes only the chosen transport's fields and the shared input definitions. |
| Executable | Required for stdio. A program on an execution device, not an entire shell command with arguments. |
| Arguments (JSON array) | stdio arguments as JSON strings, or objects with value and optional option/when. Empty array is valid. This is not a space-separated shell command. |
| Working directory | Optional stdio directory. |
| Full endpoint URL | Required for HTTP. Enter the MCP server's complete HTTP(S) endpoint. Put credentials in Authentication and follow any URL error shown by the form. |
| Authentication → Add secret input | Enter a header or environment variable name and press Add secret input again or Enter. Adds a required string secret input and its binding to the draft. Review them before saving; this does not enter a credential. |
| Advanced settings | Editable Environment variables (JSON object) for stdio, HTTP headers (JSON object) for HTTP, plus Settings definitions (JSON array) for both. These are JSON text fields, not separate Add option/header dialogs. |
| Save | Validates fields/JSON/bindings and waits. Fields and Save are disabled while saving. Parse, contract, rejected-save and transport errors use the form's failure notice; no successful connection is implied. |
| Refresh on load failure | Mobile existing-definition read offers Refresh. This is a reload action, not a connection check. |
| Close / Back | The definition form has no dirty-discard confirmation. Leaving discards the unsaved form. Dismissing while a request is already sent does not cancel it; inspect the saved item before repeating a create. |

## Results and constraints

Desktop creation closes its dialog after success; an inline existing editor stays open. Mobile creation returns to the prior screen; an existing editor stays and reloads saved definition data. Normal signed-in ownership is required; preview/agent sessions do not provide these private edits.

The current connection form has no supported-type or execution-device selector. Attach the saved Toolbox to Gear, then choose devices and values there. stdio cannot execute on iOS; use Streamable HTTP. Android stdio uses the Termux/runtime setup described in the connection guide. Saving a definition does not check or start its server.

## Related guides

[Rename, duplicate or delete a private Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-maintenance.md)

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Define private MCP inputs and bindings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
