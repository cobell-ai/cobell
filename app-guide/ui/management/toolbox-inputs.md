# Define private MCP inputs and bindings: screen reference

Define reusable private connection inputs in JSON. Enter their actual values in Gear afterward.

## Open this screen

**Desktop:** Management → Toolbox → private Toolbox → embedded MCP connection → Advanced settings.

**Mobile:** Private Toolbox → Toolbox schema → MCP connection → Advanced settings. The creation form has the same fields.

## Fields and actions

| Control or area | Location and behavior |
|---|---|
| Settings definitions (JSON array) | One object per input: key/type, optional label/description/required/secret/flagOnly/default. Unknown definition fields are rejected. |
| Input key | Unique, 1–100 characters. Starts with an ASCII letter or underscore; remaining characters may also include digits, dots and hyphens. |
| Type / default | Types: string, integer, double64, boolean, stringArray, intArray, doubleArray, datetime, utcTimestamp. Defaults must have the matching JSON type; explicit null defaults are invalid. Secret inputs cannot have defaults. flagOnly requires boolean. |
| Environment variables / HTTP headers | JSON object mapping binding names to strings. Use an ordinary literal or @key; every referenced key must be defined. HTTP headers are only saved for HTTP, environment entries for stdio. |
| @key / @@ | A leading single @ references the whole value of an input. @@ escapes one leading @. Text inside another string is not interpolated; an entire URL can be an input reference. |
| Arguments (JSON array) | Strings or objects with value, optional option and when. when names a defined boolean input. A missing referenced value omits that argument and its paired option; arrays remain one JSON argument rather than expanding into several arguments. |
| Add secret input | Under Authentication, enter a header or environment name and confirm with the button or Enter. Review the generated input and binding. If a name is rejected, follow the field error and choose another name. |
| Save | Saves the whole connection draft, including definitions/bindings. To edit/remove an input or binding, edit the JSON; this private editor has no separate Add option/Add HTTP Header dialog. |

## Secret binding example

For HTTP, Add secret input with the name Authorization creates a required secret string input and references it from the HTTP headers object. Enter the actual value, including the server's required prefix such as Bearer, in this device's Gear Authentication section after saving and attaching the Toolbox.

## Limits and recovery

The Add secret input helper accepts environment names beginning with a letter/underscore followed by letters/digits/underscores. HTTP names must be valid header tokens. Host, Content-Length, Transfer-Encoding, MCP-Session-Id and MCP-Protocol-Version are reserved and rejected.

A default's JSON type matters: 0, false and arrays are values, not quoted text. Correct JSON, references, types or conflicts using the form's errors. Saving definitions does not check the server connection. Inspect saved data before repeating an uncertain write; leaving this definition form does not ask to preserve unsaved changes.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-inputs.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Create or edit a private MCP Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md) · [Enter typed Toolbox values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
