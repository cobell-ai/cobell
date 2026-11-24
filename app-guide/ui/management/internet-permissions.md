# Configure Internet Use: screen reference

Let a DingDong retrieve permitted public web or REST resources from selected devices.

## Open this screen

**Desktop:** Management → Gear → your editable Gear → Internet Use settings icon. Add the Toolbox first if needed.

**Mobile:** Shortcuts → DingDong → Gear → your private Gear → Connection → Built-in Toolbox → Internet Use.

## Controls

| Control or area | Location and behavior |
|---|---|
| Enabled for this Gear (mobile) | Changes the capability's draft enabled state. It does not run a request. |
| Execution devices | Desktop rows/checkboxes toggle known devices. Mobile checkboxes include retained unknown selections: uncheck one to remove it, but it cannot be newly selected until it is in the loaded device catalog. |
| URL access control (desktop) / URL access rules (mobile) | All allowed applies no URL-pattern restriction. Only some allowed permits requests matching listed patterns; Only some excluded blocks matching requests. Review the patterns after changing modes. |
| URL pattern input | Enter one pattern. Text still in the input field is not included by Save. |
| Plus / keyboard submission | Adds the entered URL pattern to the list. Desktop uses the plus button or Enter; mobile offers Add URL pattern or keyboard submission. Check that the pattern appears in the list before saving. |
| Pattern chip × (desktop) / Remove URL pattern × (mobile) | Immediately removes that pattern from the editor draft without confirmation; Save is needed to apply it to Gear. |
| Advanced settings | Expands or collapses the request header switches. Starts collapsed. |
| Block Authorization, Block Cookie, Block X-Api-Key, Block X-Auth-Token | Each switch starts on. Turn a switch off to allow that header for this Gear. Save applies the change. |
| Desktop Save / Cancel / header close | Save sends an asynchronous Gear update and closes before acknowledgment. Cancel/close discards an unsent draft. Reload saved Gear before repeating an uncertain write. |
| Mobile Save / Back | Save waits for the write and saved-settings check before leaving. Back with changed settings asks to keep editing or discard; saving blocks departure. |
| Mobile Retry / Check saved settings | Retry reloads an initial read failure. Check saved settings reads after a failed write without resending it and retains differing edits. Review before saving/discarding. |

## Conditions and results

An empty allow list does not block all URLs. To restrict access, add at least one pattern and save, then reopen the settings to check the applied access mode.

System Gear's required Internet Use card has no configuration action. Requests require public HTTPS URLs in all three access modes. Device selection, Gear assignment and successful request execution remain separate.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/internet-permissions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

Reviewed: 2026-11-25. UI labels use the English app language.
