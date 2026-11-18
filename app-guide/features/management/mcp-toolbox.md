# Create or edit a private MCP Toolbox

Register a private MCP connection before setting its execution devices and actual values.

## Start here

**Desktop:** Management → Toolbox → Add (or Create Toolbox in an empty collection). Existing private Toolbox detail embeds the MCP connection form.

**Mobile:** Shortcuts → DingDong → Toolbox → Create (+). For an existing private item, open Toolbox schema to edit MCP connection.

## Create or edit the connection

1. Enter a nonempty Name of at most 40 characters. The form requires this name; it does not obtain a name from a server check.
2. Choose Transport. For stdio, enter Executable separately from Arguments (JSON array), and optionally Working directory. For HTTP, enter Full endpoint URL.
3. If a credential is needed, open Authentication → Add secret input, enter the environment/header name, then press the same button again or Enter. This adds definitions/bindings to the draft, not an actual credential.
4. In Advanced settings, edit the environment/header JSON object and Settings definitions (JSON array) as needed. @key refers to a whole input value; @@ escapes a leading literal @.
5. Save and wait. Fix the shown failure before trying again. Desktop creation closes; mobile creation returns. Existing editors remain open, with mobile reloading saved data.
6. Attach the saved Toolbox to Gear. Choose execution devices, enter common/device values and local credentials, save and Check this device there.

## Completion, limits and recovery

Transport starts as stdio. Switching retains the open draft's other transport fields, but saving includes only the selected transport and shared input definitions. This form has no supported-type/device selector and uses Save for creation as well as editing.

Use the MCP server's complete HTTP(S) endpoint. Credentials belong in defined secret inputs and each device's Gear authentication fields. Include the required prefix, such as Bearer, in the actual Authorization value. Follow any URL error shown by the form.

The definition form has no unsaved-discard confirmation. Save before leaving. Closing/Back after a sent request does not cancel it; refresh the collection or saved definition before repeating an uncertain create/update.

stdio execution is unavailable on iOS. Android needs its supported Termux/runtime setup. Saving this definition neither installs the runtime nor verifies a connection.

Also find this under: MCP, private tools, stdio, Streamable HTTP, JSON connection settings.

## Related guides

[Rename, duplicate or delete a private Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-maintenance.md)

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/mcp-toolbox.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Define private MCP inputs and bindings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [Edit Gear attachments and values](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
