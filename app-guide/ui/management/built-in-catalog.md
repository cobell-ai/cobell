# Inspect built-in Toolboxes: screen reference

Choose a supplied capability and find the Gear settings that actually control it.

## Open this screen

**Desktop:** Management → Toolbox → B origin filter → select a Toolbox.

**Mobile:** Shortcuts → DingDong → Toolbox → Built-in filter → select a Toolbox.

## Controls

| Control or area | Location and behavior |
|---|---|
| Overview / Feature summary / tool rows | Information about the capability. Tool rows do not execute those actions. Mobile has no private-style Overview/Toolbox schema editing tabs here. |
| Supported OS / types / safety | Displays supported scope and permission boundaries. These labels do not probe device readiness or grant permissions. |
| Desktop Configuration demo | Present for KnowledgeBox Use, Internet Use, Sandbox Browser Use, Screen Use, Mouse Use and Keyboard Use. It starts with example configuration, not the selected Gear's saved values. |
| Demo device/permission/browser choices and Add | Shows the demo notice instead of saving configuration or creating a Browser. Confirm dismisses the notice. Text or timeout fields can retain a local edit; no Gear is changed. |
| Desktop Usage on those six pages | Lists loaded Gear with that built-in capability enabled. Rows are display-only; return to Management → Gear to open one. There is no Usage Retry on these pages. |
| Mobile Gears using this Toolbox | Lists this account's loaded Gear with the capability enabled. Tap a Gear to open its detail; a failed catalog read offers a retry row. Existing rows may remain during loading/error. |
| Mobile Screen Use → Screen sharing card | Opens the actual mobile screen-sharing page. Opening it does not start capture; use Start sharing and system approval there. Mouse/Keyboard availability cards are informational. |
| Mobile Sandbox Browser Use → Set up Cobell Mobile Booster | On supported Android, opens the actual Booster setup page. An unsupported-device card has no setup button. Basic/connected status does not change an already-running Browser's mode. |
| Back | Desktop returns to Management. Mobile returns through its navigation stack, with Management as fallback. It does not undo settings made on a separately opened setup page. |

## Pages without that demo or usage list

- **Cobell Controller:** no configurable options or demo. Desktop explains automatic System Gear attachment; mobile shows capability categories without a Gear-usage list.
- **Notification Sender:** no catalog configuration demo or Gear-usage list on either platform. Its information describes automatic attachment; change delivery settings in actual Gear.
- **App Share:** desktop shows selection and monitoring guidance without a demo or Gear-usage list. Mobile has Gear-usage links. Select apps in actual Gear; the catalog does not register or start an app.

Built-in definitions have no private Rename, Duplicate, image or individual Delete menu. Desktop collection checkboxes do not make them removable; see [collection controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/collections.md).

## Conditions and results

The catalog includes KnowledgeBox Use, Internet Use, Sandbox Browser Use, Screen Use, Mouse Use, Keyboard Use, Cobell Controller, Notification Sender and App Share. There is no final Save on a built-in catalog page. Configure and save the actual Gear separately. Usage lists show saved configuration, not running DingDongs or successful tool execution. Catalog support does not prove this device has the necessary runtime.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/built-in-catalog.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Configure KnowledgeBox Use permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Approve Browsers in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md)

[Select apps in Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/gear.md)

[Mobile screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/screen-sharing.md) · [Android Booster setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/android-booster.md) · [Gear connections](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-attachments.md)

Reviewed: 2026-10-23. UI labels use the English app language.
