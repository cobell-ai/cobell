# Create and edit an isolated Browser: screen reference

Save a named Browser on an owning device, then separately select it in a DingDong's Gear.

## Open this screen

**Desktop:** Management → Browser → Add; use the pencil to edit a row.

**Mobile:** Shortcuts → Browser → Create; open a Browser detail → Edit browser.

## Controls

| Control or area | Behavior |
|---|---|
| Device | Chooses the owner during creation; fixed when editing. Mobile offers this Android device and known desktop devices; iOS has no local Browser execution. |
| Browser name / Display name | A trimmed 1–40-character display label; spaces are allowed, invalid characters are rejected. |
| Run in background | Saves whether to run without a visible window. A running Browser needs a restart for a mode change. Desktop also has this switch in the row. |
| Next / Previous | Desktop moves between basic information and Browser-global policy; Next validates the name. |
| Global browser policy | Sets site scope and the upper bound of permissions for all Gear using this Browser. |
| Save / Cancel or Back | Saves configuration, or leaves the draft. Mobile Back checks unsaved changes. Desktop Cancel closes without saving. |
| Reload latest settings | Mobile editor recovery after a failure: asks before discarding the draft and reading current settings. If loading fails, the draft stays. Desktop recovery uses the list Refresh, then reopen Edit. |
| Delete browser | Desktop trash invokes deletion immediately. Mobile detail asks for confirmation; Cancel keeps the Browser. |

## Conditions and recovery

Saved configuration and a running session are separate. Creating or renaming a Browser does not prove runtime readiness, approve it for Gear or move its profile to another device. iOS can configure eligible remote Browsers but cannot run one locally.

If saving reports failure, inspect/reload the list before creating another Browser: a save can succeed while the following refresh fails. On desktop, reopen Edit from the refreshed row after an unresolved edit; there is no in-dialog Reload latest settings button. Deletion removes the Browser configuration; it has no undo control.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md) · [Site access and permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md) · [Approve Browsers in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md) · [Runtime and downloads](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-runtime.md)

Reviewed: 2026-10-23. UI labels use the English app language.
