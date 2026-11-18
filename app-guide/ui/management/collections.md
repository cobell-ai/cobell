# Browse and maintain configuration collections: screen reference

Browse saved DingDongs, configuration, devices and Browsers.

## Open this screen

**Desktop:** Top navigation → Management → Pure, Memory, Toolbox, Gear, Device or Browser.

**Mobile:** Third bottom tab Shortcuts → DingDong for the bot/Memory/Toolbox/Gear collections; Device and Browser are separate shortcut cards.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop collection tabs | Pure, Memory, Toolbox, Gear, Device and Browser. Scroll horizontally when needed. Choose a category to browse it; use Refresh to reload. |
| Wheel over a populated desktop collection header | In Pure, Memory, Toolbox and Gear, vertical wheel input over the header scrolls that collection's list, stopping at its ends. It does not change a filter or sorting choice. |
| Origin / type / sorting controls | Filters applicable built-in or private entries and compatible types. |
| List row / card background | Normally opens details. In Edit, private Memory, ordinary Gear and Pure toggle selection. Built-in Memory and the built-in System Gear retain detail navigation. Toolbox cards toggle selection even for built-ins; selection does not make built-ins deletable. Nested image/menu controls have their own actions. |
| Create / Add | Starts object creation. |
| Edit / Select | Enables multi-selection where offered. |
| Delete selected | Runs the collection's delete flow. Desktop Memory, Toolbox and Gear bulk deletion start without an additional confirmation; individual detail Delete and mobile bulk Delete selected do ask. |
| Refresh | Reloads the collection. |
| Desktop Add / Edit | Right side of a populated collection header; empty collections offer their named Create button. |
| Mobile Create (+) | Right-aligned above the collection list, below its tabs/filter area. |
| Mobile sort/filter icons | Top app-bar actions; sorting or origin/type selection depends on the collection. |

## Desktop empty views and filter recovery

| View or action | Behavior |
|---|---|
| Named Create action in Pure / Memory / Toolbox / Gear | Opens the corresponding creation form. Opening it does not save an item; follow that form's final submission. |
| Empty Memory / Toolbox after filtering | If filter controls are unavailable, switch to another category and return. Review the filters and refresh if needed. |
| Empty Device | Has no Add Device button. A load-error banner can offer Retry; registration is handled by sign-in. |
| Browser with no devices | Shows an empty Device view with no Browser Add/Refresh controls. Open Device to check registration or use its load-error Retry when offered. |
| Browser with devices but no Browsers | Keeps its header and offers Add to open Browser creation. |

An empty-state Create button can coexist with a failed or incomplete read. Review available load errors and refresh saved state before treating it as an empty account.

## Conditions and results

Built-in objects are not ordinary editable private definitions. Configuration browsing does not select a conversation or automatically equip Gear. Refresh failure may leave the previously loaded collection visible.

## Memory collection details

| Control | Behavior |
|---|---|
| Desktop sort menu | Recent registration, name ascending/descending, type or data size. Type groups origins, then name; size is prompt bytes descending. |
| Desktop All / B / P filter | Choose All, Built-in or Private. This filters origin, not DingDong compatibility. |
| Desktop Edit / private row / checkbox | Selects private Memories for immediate Delete (count). Cancel/Escape clears selection while not deleting. Built-in rows remain detail entries. |
| Desktop empty state | Offers Create Memory. If the current filter leaves no entries, the list/header is replaced by this empty state. |
| Mobile origin filter | App-bar choices All origins, Built-in and Private. |
| Mobile sort | Choose recent registration, name order or prompt size from the available menu. |
| Mobile Select / long-press / row / checkbox | Starts selection or toggles targets. Cancel selection clears it. Delete selected confirms the count/message, continues through failures and retains failed selections. Review names in the list first. |
| Refresh / Retry | Reloads the relevant Memory list. A refresh error can keep existing rows visible; do not treat that stale view as a confirmed empty list. |

For copy, individual/bulk deletion and partial failure, see [Memory maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/memory-edit.md).

## Toolbox collection controls

| Control | Behavior |
|---|---|
| Desktop All / B / P | Filters origin. If a filter has no results, review other origins before assuming the collection is empty. |
| Desktop sort | Latest created, Name (A-Z), Name (Z-A), Type. Type groups origins, then base name; it is not a compatible-DingDong-type filter. Name sorting and cards use the base Name rather than a custom detail name. |
| Desktop Edit / card / checkbox | Selects entries instead of opening them. Only eligible private entries can be deleted; built-in entries cannot be deleted. Cancel/Escape clears an idle selection. |
| Desktop Refresh / banner Retry | Reloads Toolbox definitions. Built-ins are present independently of the private read; an error can retain old private entries or leave only built-ins. This is not an MCP connection check. |
| Mobile origin filter | All origins, Built-in or Private. Built-ins stay first in their fixed catalog order when visible, before the sorted private rows. |
| Mobile sort | Choose newest registration or name order from the available menu. |
| Mobile row / Select / long-press | Opens detail normally, or selects private rows in selection mode. Built-in rows remain information links without delete checkboxes. The origin filter is disabled during selection. |
| Mobile Refresh / error Retry | Reloads the catalog. A retained-list error does not confirm that private definitions are absent. Opening a built-in page or refreshing the catalog does not run its tools. |

Desktop Toolbox bulk Delete starts immediately and stops at its first failure. Mobile confirms a count/message, continues after failures and retains failed selections. For naming, copying, usage and individual deletion, see [Toolbox maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/toolbox-maintenance.md).

## Gear collection controls

| Control | Behavior |
|---|---|
| Desktop All / Sys / Pu type filter | Choose All, System or Pure. All hides ordinary private System Gear; choose Sys to find it. The built-in System Gear stays visible and first. |
| Desktop sort | Choose Created, name order, Memory count or Toolbox count. Attachment-count sorting can differ from card totals. |
| Desktop numbered-lines menu | 1-line display, 2-line display or 3-line display. Changes the allowed attachment-icon rows and card height, not the number of Gear objects. Saves the account's display preference locally without a later Save button. |
| Desktop card / attachment icon / +N | Open a card outside Edit to inspect Gear. Hover an attachment icon for its name. Open the Gear detail to review all connections. |
| Desktop Edit / card / checkbox / Cancel / Escape | Editable cards and checkboxes toggle selection. Cancel or Escape clears selection while not deleting. Built-in System Gear has no selection checkbox and remains a detail entry. |
| Desktop Refresh / error Retry | Reloads saved Gear information. A failed refresh may retain prior cards; the built-in System Gear can remain even if private data could not load. Do not treat that view as a confirmed empty private collection. |
| Mobile type filter | App-bar filter icon → All types or types present in the loaded catalog. All types includes System Gear. There is no separate Gear origin menu. |
| Mobile sort | App-bar sort icon → Newest registration, Name (A-Z) or Name (Z-A). Name sorting ignores letter case. The mobile menu has no attachment-count sort. |
| Mobile Connection rows | Above the list: Connection rows: 1/2/3. Controls each Memory/Toolbox summary's visible rows; capacity also depends on width/text size. Saves locally for the account without a later Save button. Preview changes only its temporary display. |
| Mobile display-setting Retry | Retries loading the Connection rows setting. If a preference save fails, check its current value before changing it again. |
| Mobile primary row | Opens the Gear detail. In selection mode the row/checkbox toggles selection; Back or Cancel selection exits selection while idle. |
| Mobile Connection / +N | Opens this Gear's Connection screen. It does not expand the summary inline. The listed attachment names and pictures are display-only, not direct links to their definitions. Selection mode blocks this navigation. |
| Mobile summary Retry | Refreshes a failed Gear connection summary. If a resource name is unavailable, open Connection to inspect the attachment. |
| Mobile Refresh / retained-list Retry | Refreshes the current list. Read any loading error and use Retry when offered. |

These controls browse saved configuration. They do not equip Gear, reorder its attachment priority or run/check a Toolbox connection.

## Gear deletion details

Desktop Gear Edit → Delete (count) sends sequential requests without another confirmation and stops at the first failure. Mobile Select/long-press → Delete selected confirms a count/message, continues after failures and leaves failed targets selected. Built-in System Gear is excluded. See [Gear maintenance](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/gear-maintenance.md) for individual confirmations, copying and usage checks before deletion.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/collections.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
