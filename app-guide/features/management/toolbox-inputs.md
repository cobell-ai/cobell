# Define private MCP inputs and bindings

Define inputs and bindings in the private MCP connection; supply actual values per Gear later.

## Start here

**Desktop:** Management → Toolbox → private Toolbox → embedded MCP connection → Advanced settings.

**Mobile:** Private Toolbox → Toolbox schema → MCP connection → Advanced settings. The creation form has the same fields.

## Steps

1. Add or edit objects in Settings definitions (JSON array). Use a unique key and type; optionally label, description, required, secret, flagOnly and a typed default. Keys are 1–100 characters, start with an ASCII letter/underscore and then allow letters/digits/underscore/dot/hyphen.
2. Choose string, integer, double64, boolean, stringArray, intArray, doubleArray, datetime or utcTimestamp. Match the default's JSON type. Explicit null and secret defaults are rejected; flagOnly is valid only with boolean.
3. In the transport's environment/header JSON object, bind a name to @key or a literal. Single @ at the start references the whole input value; @@ preserves a leading literal @. There is no interpolation inside other text.
4. For stdio, use a JSON argument array. An object can pair option with value and conditionally include it using when (a boolean input key). An absent referenced value omits its paired option too; an array input is passed as one JSON argument.
5. For a secret header/environment entry, use Authentication → Add secret input → binding name → the same button again or Enter. This generates a required string secret definition plus its binding. Put the real credential in Gear on each device, not in this shared definition.
6. Save the entire connection, then configure Gear values. Definitions and per-Gear values have separate saves.

## Completion, limits and recovery

These are JSON editors. The current private form has no Add option/Add HTTP Header dialogs or separate input-row Save. Edit JSON to rename/remove a definition or binding, and update any @ references and when conditions together.

The helper rejects duplicate/invalid binding names and the reserved HTTP names Host, Content-Length, Transfer-Encoding, MCP-Session-Id and MCP-Protocol-Version. Malformed current input/binding JSON can also prevent adding a secret.

Save checks JSON, input references and typed defaults; correct any error shown by the form. A failed save keeps the form open. Inspect saved data before repeating an uncertain write. Leaving this definition form does not ask to preserve unsaved changes.

Also find this under: private Toolbox options, headers, secret input, @ binding, MCP input definitions.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/toolbox-inputs.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Create or edit a private MCP Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md) · [Enter typed Toolbox values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [Set per-device MCP authentication and check connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md)

Reviewed: 2026-10-23. UI labels use the English app language.
