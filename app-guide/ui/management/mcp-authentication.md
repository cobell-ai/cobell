# Set per-device MCP authentication and check connections: screen reference

Select execution devices, save local credentials and inspect each device's MCP connection report.

## Open this screen

**Desktop:** Management → Gear → editable Gear → Toolbox section → settings icon beside the attached private Toolbox.

**Mobile:** Shortcuts → DingDong → Gear → your private Gear → Connection → settings icon beside the linked private Toolbox.

## Device and value controls

| Control or area | Location and behavior |
|---|---|
| Desktop Tool execution/target devices | Row or checkbox selects registered devices. OS/login badges are information; selection does not install/start the server. This form has no device-priority drag control. |
| Mobile Devices that can use this Toolbox | Checkboxes choose devices. Loading/error UI belongs to the device inventory; its Retry refreshes that list, separately from MCP Refresh. |
| Missing selected device ID → close icon | Removes the unavailable device from the draft and removes its per-device override values. Toggling a known device off also removes its overrides. Save is required to persist selection changes. |
| Common settings → Settings for | Selects shared public values or one selected device's overrides. Changing this selector does not switch the physical device receiving Authentication values. |
| Authentication | Secret input values for the device running this Cobell app, for this Gear/Toolbox connection. Normal saved-connection editors can display them even when this device is not selected; select and save this device before sign-in/check. |
| Show value / Hide value / Reset value | Changes masking or removes the explicit local-secret/public-value draft entry. Reset is not a sign-out control. Save persists the edited values. |
| Save | Validates supplied types and saves public settings plus local secrets. A missing required value or no selected execution device can be saved as incomplete. A completed save does not verify execution. |
| Edit toolbox connection | Enabled while idle with no unsaved Gear edits. Opens the reusable definition editor, then refreshes Gear data on return. This is a definition edit, not a per-device credential entry. |

Authentication stays local even if Settings for shows another device. Enter and save credentials separately while running Cobell on each intended execution device. Supply Authorization prefixes such as Bearer as part of the actual value when required by the server.

## Sign-in and connection controls

| Control or area | Location and behavior |
|---|---|
| Sign in with browser | Offered for Streamable HTTP. Requires this device selected in saved settings, no unsaved edits and an idle form. Resolves required settings before authorization; opens the server's supported browser sign-in. |
| Waiting notice / Cancel | Cancel stops the current sign-in attempt. It does not act as sign-out or remove saved Gear settings/secret-input values. Closing the connection editor during sign-in also cancels that attempt; a browser response alone is not verified readiness. |
| Sign-in completion | Successful authorization automatically runs Check this device. Review the resulting connection status; the check can still fail after sign-in succeeds. |
| Check this device | Connects from the current device, loads server information/instructions and available tools, and records a report. It does not run a check on every selected device or perform a DingDong task. Same saved-device/clean/idle gate as sign-in; unavailable iOS stdio disables it. |
| Refresh | Reloads saved MCP settings, local secrets and recorded checks. It does not connect to the MCP server or accept changed tool information. With a dirty Gear draft it asks to discard: desktop Keep editing / Leave without saving; mobile Cancel / Discard. Keeping/dismissing retains the draft; confirming allows reload. Verify the values before checking. |
| Android stdio → Termux setup | Requests Cobell's RUN_COMMAND permission. It does not install Termux, Python or the MCP server. Complete the shown setup, then Check this device. |
| Progress / disabled fields | Other edits/actions are blocked while an action is running; sign-in Cancel remains available. Back/close does not cancel a sent Save or Check. Dirty Back uses the same keep/discard choices as Refresh. It discards form edits, not a sent write. |

If sign-in expires or is canceled, start a fresh sign-in from the current saved connection. Reopen authentication after changing accounts or connection settings.

## Read reports and accept changed information

| Control or area | Location and behavior |
|---|---|
| Connection status → device row | Expand to inspect that device's report. The row shows its latest-check time in local date/time. A report from another device is not a fresh check from this device. |
| Ready / authentication or runtime notice / stale result | Review the current status, check time and any authentication or runtime notice. After changing settings, check the connection on the target device again. |
| First successful check / Latest check | Shows server and tool information from connection checks. Review the status and time; displayed information can be from an earlier check and is not a complete history. |
| Advanced settings inside a discovery | Expands selectable discovery JSON. This is inspection, not a definition/settings editor, and has no dedicated Copy/Save action. |
| Use current information as baseline | Review changed server and tool information, save Gear edits, then accept the information for the selected device. This does not run another connection check. |
| Baseline after acceptance | The accepted server and tool information is used for future comparisons. Review later changes before accepting them. |

## Recovery and platform limits

stdio cannot execute on iOS; use Streamable HTTP. Android stdio needs Termux, Python 3 and the server runtime, allow-external-apps=true in ~/.termux/termux.properties, termux-reload-settings and Cobell RUN_COMMAND permission. Termux setup requests only permission; Check this device verifies startup.

Save errors do not prove that both public and local values are current. Refresh/reopen saved settings after an uncertain write before repeating it. A changed/stale discovery should be inspected before accepting its new baseline. Missing permissions/runtime, expired authorization and revised settings require their own correction; Refresh alone does not repair them.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-authentication.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Create or edit a private MCP Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md) · [Enter typed Toolbox values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

Reviewed: 2026-10-23. UI labels use the English app language.
