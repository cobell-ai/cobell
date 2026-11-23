# Configure Internet Use

Let a DingDong retrieve permitted public web or REST resources from selected devices.

## Start here

**Desktop:** Management → Gear → your editable Gear → Internet Use settings icon. Add Internet Use first if it is not attached.

**Mobile:** Shortcuts → DingDong → Gear → your private Gear → Connection → Built-in Toolbox → Internet Use.

## Desktop steps

1. Open Internet Use settings in the Gear you want to edit.
2. Select execution devices using their rows or checkboxes.
3. Choose URL access control. For Only some allowed or Only some excluded, enter one pattern, then use the plus button or Enter. Added patterns appear as chips; use a chip's × to remove it from the draft.
4. Add each pattern before Save. Text still in the entry field is not included.
5. Save submits the update and closes before acknowledgment. A closed dialog does not prove persistence; reload Gear if the result is uncertain. Cancel/header close discards an unsent draft.

## Mobile steps

1. Open Internet Use in the Gear's Connection. Set Enabled for this Gear as needed and choose execution devices.
2. Select URL access rules. The list/input appears for Only some allowed or Only some excluded.
3. Enter one URL pattern, such as `https://example.com/*`, then tap Add URL pattern (plus) or submit with the keyboard. Check that the pattern appears in the list before saving. Text still in the entry field is not included by Save.
4. Use the × beside a listed pattern to remove it from the draft. After changing the access mode, review the patterns before saving.
5. Choose Save after reviewing the actual list. It waits for the write and saved-settings check before leaving.
6. Back asks before discarding changed settings; saving blocks departure. After a failed write, Check saved settings reads without writing again and retains differing edits for review. Retry reloads an initial read failure.

## URL rules and empty lists

| Mode | Request access |
|---|---|
| All allowed | No URL-pattern restriction. |
| Only some allowed | Requests must match a listed pattern. |
| Only some excluded | Requests matching the listed patterns are blocked. |

An empty allow list does not block all URLs. To restrict access, add at least one pattern and save, then reopen the settings to check the applied access mode.

## Completion, limits and recovery

URL-rule controls do not verify request execution. Current request execution requires public HTTPS URLs; All allowed does not remove transport/network restrictions. Select a connected execution device and equip the Gear to the intended DingDong. A saved configuration is not a successful request.

Internet Use can read public web pages and request reads, updates, or deletions on public HTTPS APIs that permit the operation. It does not support supplying API keys, login tokens, or cookies. Use [Sandbox Browser Use](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md) for actions on a browser page, such as clicking buttons on a signed-in site. See [System Gear limits](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md) for the required Internet Use card.

Also find this under: web lookup, REST, URL rules, allowed websites, Internet Use.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/internet-permissions.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
