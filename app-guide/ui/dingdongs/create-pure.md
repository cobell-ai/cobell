# Create a Pure DingDong: screen reference

## Open this screen

**Desktop:** Management → Pure → Add, or Create New Pure in an empty collection.

**Mobile:** Shortcuts → DingDong → DingDong collection → Create. Home/Friends DingDong directories also offer Pure creation.

## Controls

| Control or area | Behavior |
|---|---|
| Desktop Create Pure / mobile Create Pure page | Collects Name to create the owned identity and its personal chat. Complete Gear setup afterward. |
| Name | 40-character input limit; trimmed identity validation described below. Desktop autofocus and delayed inline error; mobile validates on submission. |
| Desktop Create / Enter | Starts creation with a valid name. Wait for the result before submitting again. Create shows progress and is disabled while sending. |
| Desktop Cancel | Closes without creating before submission; disabled while sending. No draft-discard confirmation. |
| Desktop close icon / dialog dismissal | Can still close while the request is pending. This does not cancel creation on the server. |
| Mobile Create / keyboard Done | Validates, then starts creation. Shows Creating and disables editing/repeated submission during the request. |
| Mobile Back → Discard changes? | For a nonblank name: Cancel keeps the draft, Discard leaves. Whitespace-only input leaves without that confirmation. Back is blocked while Creating. |
| Creation failure | Desktop failure message with retained name; mobile inline failure below the form with retained name. Review the current collection before repeating an uncertain request. |
| Successful desktop creation | Closes creation, opens Set up DingDong Gear. Closing setup keeps the bot. |
| Successful mobile creation | Replaces creation with the bot's management detail. Overview → Choose Gear opens setup. |
| Gear setup | Choose compatible Pure Gear and Save; Create Gear creates a configuration to select afterward. See the separate setup guide. |

## Validation and results

Use a 1–40-character name with supported letters, numbers and underscores. Check the name field's error message if it is not accepted.

Both collections can show a temporary item while creating. On failure, that local item can disappear even if the server created the bot before its response was lost. Refresh the collection and inspect the personal chat before repeating Create. Creating and Gear assignment are separate requests; a created identity does not mean it has a response configuration.

Cobelly is supplied by the account. An old form should be closed and reopened after an account change.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/create-pure.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [Rename or delete a Pure DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/maintain-pure.md)

Reviewed: 2026-10-23. UI labels use the English app language.
