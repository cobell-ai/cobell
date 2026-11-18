# Browse and maintain configuration collections

Browse saved DingDongs, configuration, devices and Browsers.

## Start here

**Desktop:** Top navigation → Management → Pure, Memory, Toolbox, Gear, Device or Browser.

**Mobile:** Third bottom tab Shortcuts → DingDong for the bot/Memory/Toolbox/Gear collections; Device and Browser are separate shortcut cards.

## Desktop steps

1. Open Management and choose the collection.
2. Apply its origin/type/sort controls.
3. Open an item for detail, or Create for a new object.
4. Use Edit/selection mode where offered. Review the selected items before deletion: desktop Memory, Toolbox and Gear bulk Delete start without another confirmation.

## Desktop header, cards and empty views

Management offers Pure, Memory, Toolbox, Gear, Device and Browser. Scroll the header horizontally if needed. Choose a category to browse its collection; use Refresh to reload it.

Cards normally open configuration details. In Edit mode, private Memory, ordinary Gear and Pure cards select/deselect entries. Built-in Memory and the built-in System Gear still open their detail. Toolbox cards toggle selection, including built-ins, but built-ins remain protected from deletion.

In populated desktop Pure, Memory, Toolbox and Gear views, the mouse wheel also scrolls the list when the pointer is over its header. It stops at the list's ends and does not change the current filter or sorting.

An empty Pure, Memory, Toolbox or Gear view can offer Create, which opens a form. Filters can hide existing items. If filter controls are unavailable, switch to another category and return, then review the filters and refresh if needed. Read any loading error before creating another item.

Device's empty view has no Add Device action. Browser also has no Add action when its device list is empty; open Device and use a load-error Retry when offered. With devices present and no saved Browsers, Browser's Add opens Browser creation. See [Device management](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md) and [Browser configuration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md).

## Mobile steps

1. Open Shortcuts and DingDong, Device or Browser.
2. Choose the desired collection and filters.
3. Tap an item for its detail.
4. Use Create or Select → Delete selected as needed.

## Find and inspect Toolboxes

1. Open Toolbox and choose All/B/P on desktop or All origins/Built-in/Private on mobile. Built-in entries appear before private entries on mobile.
2. Sort private entries using the available menu. Desktop offers Latest created, name order and Type; mobile offers newest registration and name order.
3. Open a row for detail. Desktop private detail embeds the MCP form; mobile separates Overview actions from Toolbox schema. A custom desktop detail name can differ from the collection's base Name.
4. Refresh or use the list's error Retry to reload saved definitions. Built-ins can remain visible after a failed private read, and older private rows can remain after a failed refresh. Do not treat either state as a confirmed empty private catalog.
5. For bulk deletion, use desktop Edit or mobile Select/long-press. Desktop starts without another confirmation and stops on failure; mobile confirms a count and continues, keeping failed entries selected. Desktop built-in checkboxes do not make those entries removable.

Use [Toolbox maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-maintenance.md) for copy/name/usage and deletion details. Catalog refresh does not check an MCP connection or equip Gear.

## Find and inspect Gear

1. Open Gear. On desktop, choose Sys to find a private System Gear; All hides ordinary private System Gear. The built-in System Gear stays first. Choose All, System or Pure as needed. Mobile's All types includes System; use its type menu to filter available Gear.
2. Sort the list. Desktop offers Created, name order, Memory count and Toolbox count; mobile offers newest registration and name order. Attachment-count sorting can differ from card totals.
3. Choose one, two or three attachment rows using desktop's numbered-lines menu or mobile's Connection rows control above the list. This changes the summary layout, not attachment selection. The preference saves locally for the account without a separate Save. Mobile preview changes are temporary.
4. Open a desktop card or mobile primary row for the Gear detail. Desktop attachment icons show names on hover; its +N is a summary indicator. Mobile's Connection button or +N instead opens that Gear's Connection screen. It does not expand the list inline or open an individual Memory/Toolbox definition.

## Refresh the intended information

Use Refresh for the current list or Retry beside a failed section. After an uncertain setting change, check the saved value before changing it again.

Failed refresh can leave older rows visible. The desktop built-in System Gear may still be shown when private Gear could not load; it does not prove that no private Gear exists. Attachment summaries can also show fewer icons or unavailable names while definitions are missing from the current catalog. Open the saved Connection screen to inspect them. Refresh does not run a Toolbox connection check.

If a display preference fails to save, wait for the result and check the current value before choosing again. During selection, use Back or Cancel selection to return to browsing. Desktop Cancel/Escape clears an idle Edit selection.

## Completion, limits and recovery

Built-in objects are not ordinary editable private definitions. Configuration browsing does not select a conversation or automatically equip Gear. Refresh failure may leave the previously loaded collection visible.

In the desktop Memory list, the All/B/P/M menu filters origin and type-order sorting groups origins rather than compatible DingDong types. Cancel/Escape clears selection while no deletion is running.

Mobile Memory supports Select or row long-press, row/checkbox toggles and Cancel selection. Review the selected names in the list before Delete selected: its confirmation shows the count/message rather than every name. Successful targets leave selection; failures remain selected while the rest continue. Desktop Memory bulk deletion instead stops on the first failure and can already have deleted earlier items. See [Memory maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md) before repeating a partial deletion.

Also find this under: management tabs, inventory, bulk delete, sorting, configuration.

Desktop Gear bulk deletion also stops at its first failure, while mobile confirms a count and continues past failed targets. Built-in System Gear cannot be selected for deletion. Review saved state after a partial result; see [Gear maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-maintenance.md) for copy/rename/usage and deletion controls.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/collections.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
