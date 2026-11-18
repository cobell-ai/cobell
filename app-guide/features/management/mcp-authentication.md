# Set per-device MCP authentication and check connections

Set up and check one execution device at a time for an attached private MCP Toolbox.

## Start here

**Desktop:** Management → Gear → editable Gear → Toolbox section → settings icon beside the attached private Toolbox.

**Mobile:** Shortcuts → DingDong → Gear → your private Gear → Connection → settings icon beside the linked private Toolbox.

## Select devices and save values

1. Select the devices allowed to execute this connection. Desktop supports row/checkbox selection; mobile uses device checkboxes and a separate inventory Retry on load failure. Selection does not install or test the runtime.
2. Enter public Common settings. Use Settings for to override an individual selected device. Deselecting/removing a device also removes its override draft; Save persists this.
3. Enter Authentication on the current physical device. The public scope selector does not choose where secrets are stored. Repeat secret setup in Cobell on each execution device. Show/Hide only changes masking; Reset removes the explicit draft value and is not sign-out.
4. Save and wait. Missing required values or no target can be saved as incomplete. Fill required values and select/save this device before attempting sign-in or a check.

## Sign in or check this device

1. For a supported HTTP server, use Sign in with browser while this device is selected, settings are saved and the form is idle. Complete the server's sign-in and return to Cobell.
2. Cancel stops the current waiting attempt and keeps saved Gear settings and secret-input values. Closing this connection editor during sign-in also cancels its attempt. After timeout/cancellation or a changed account/configuration, start again from the current saved connection.
3. Successful sign-in automatically runs Check this device. Inspect the result; authorization success is not proof that the following check succeeded.
4. Alternatively, use Check this device directly. It connects locally and loads server/tool information. It does not check all selected devices or execute a DingDong task. Perform checks on the other target devices separately.
5. On Android stdio, install Termux, Python 3 and the server runtime; enable allow-external-apps=true in ~/.termux/termux.properties and run termux-reload-settings. Termux setup requests Cobell's RUN_COMMAND permission. It does not install the software. Then check again. On iOS use Streamable HTTP.

## Inspect reports and update a baseline

1. Expand the device's Connection status row and inspect its status/latest-check time, First successful check and Latest check. Advanced settings expands selectable discovery JSON; it does not edit the connection.
2. If settings have changed, old reports are stale. Refresh saved settings and run a new check on that device. If a check failed, retained tool details may be from an earlier successful check.
3. When a current report offers Use current information as baseline, compare its server/tool information first. With no unsaved edits, accept that row's latest discovery if intended.
4. Accept the information only after reviewing the server and tools. Acceptance does not run a new connection check. The displayed check information is not a complete history.

## Refresh, leave and recover

Refresh reads saved settings/local secrets/recorded reports. It does not check the server or update a discovery baseline. A dirty Gear draft prompts before refresh: desktop Keep editing / Leave without saving, mobile Cancel / Discard. Keeping/dismissing retains edits; confirming allows reload. Verify the values afterward, or reopen the connection if the saved state is still unclear.

Back/close during Save or Check does not cancel the sent operation. Dirty Back discards form edits rather than undoing a sent write. After an uncertain save, inspect saved public and local values before retrying. Use Edit toolbox connection only with a clean draft to change the reusable definition.

Also find this under: MCP OAuth, local credentials, device check, changed tools, discovery baseline, Termux permission.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/mcp-authentication.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Create or edit a private MCP Toolbox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/mcp-toolbox.md) · [Enter typed Toolbox values in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/typed-values.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

Reviewed: 2026-10-23. UI labels use the English app language.
