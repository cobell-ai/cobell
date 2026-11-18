# Find, pin and organize chats: screen reference

Find an existing room or friend and keep frequently used entries easy to reach.

## Open this screen

**Desktop:** Use the chat panel’s All, DD (DingDong) and Fr (Friend) tabs.

**Mobile:** Use Chat, the second bottom tab; Home also has Friends and DingDongs lists.

## Controls

| Control or area | Location and behavior |
|---|---|
| All / DD / Fr (desktop) | All, DingDong and Friend directories. Hover an abbreviation for its full name. Scroll the header horizontally when needed. |
| Friends / Direct / Group / DingDong List | Subfilters for the selected directory. |
| All search (desktop) | Header magnifying glass toggles the field; Left Ctrl+F opens it. Matches displayed room names without case sensitivity. |
| Search clear / close (desktop All) | Backspace-shaped icon clears text while keeping the field open. Close or Esc hides the field and clears the query. |
| Fr subfilters (desktop) | Friends lists people; Direct and Group list existing rooms. Header tabs scroll horizontally. Friends row opens a profile after checking friendship; it does not immediately create a chat. |
| Fr Refresh / Add Friend | Friends only: Refresh reloads friendships and is disabled while running. Add Friend opens friend management at Inbox. |
| Fr New Chat | Direct → plus opens New Chat. Group → plus opens New Group Chat. See the creation guide. |
| Fr search (desktop) | Ctrl+F or magnifying glass opens the field. Pressing the magnifying glass again, Close or Esc clears and hides search. Clear icon removes text while keeping the field open. Switching Friends/Direct/Group retains the query. |
| DD subfilters (desktop) | List shows owned bots; open a row for its conversation or its avatar for the profile. Direct lists single-DingDong rooms; Group lists owner-only DingDong groups. |
| DD plus / Refresh | List: plus opens Pure creation, Refresh reloads owned bots with progress. Group: plus opens New Chat for a DingDong group. Direct has no creation plus. |
| DD search (desktop) | Left Ctrl+F or magnifying glass opens search. The magnifying glass can hide the field while retaining filtering, as in All. Close/Esc clears it. List matches bot names or type labels; Direct/Group match room names. Subfilter changes retain the query. |
| Room row (desktop All) | Opens the conversation. The current All directory has no list-selection mode. |
| Avatar (desktop) | A human-only direct room with exactly one counterpart opens that person's profile. A resolvable single-DingDong room opens its bot profile; other cases open participants. |
| Pin to top / Unpin from top | Pin control or room context action. |
| Reorder pinned item (desktop) | Drag handle beside an eligible pinned row. In All, it appears when at least two pinned entries are visible. |
| Retry (desktop pin failure notice) | Retries the failed action. Check the resulting pin order before making another change. |
| Settings icon (desktop All) | Opens DingDong settings; hover rotates the gear. |
| Right-click row (desktop All) | Offers Pin to top / Unpin from top, DingDong settings and Chat room settings. The latter opens room settings directly. |
| Could not load chat rooms → Retry (desktop All) | When no rooms are available and initial loading fails, restarts directory initialization. This is separate from an individual room's recovery control. |
| Loading chat rooms... / No chat rooms (desktop All) | Initial loading has progress but no action. A loaded empty or filtered-out list shows No chat rooms; clear search before assuming no rooms exist. |

## Conditions and results

Pinned order is scoped to the corresponding directory. If saving the order fails, use its retry control. A closed or blocked direct chat can remain available as local read-only history.

On desktop All, hiding the search field with the header magnifying glass preserves the query and its filtering. Use the field's clear button, Close or Esc to remove the filter. Changing between All, DD and Fr clears and hides All search. The search does not inspect message text.

In desktop All, settings replace the directory content. Back or Esc returns to the directory; the settings header can switch between DingDong settings and Chat room settings. These settings actions do not open the conversation. See [room settings](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/room-settings.md).

Desktop All places pinned entries before other rooms, which follow latest-message order. Reorder visible pins and check the result. If saving fails, use the current notice's Retry or reopen the list; a dismissed notice alone does not confirm saving.

On desktop, Friends, friend Direct/Group, DingDong List and DingDong Direct/Group each keep separate pin order. Drag handles appear with at least two visible pins. The friend and DingDong room directories have no list-selection mode; their room gear, right-click settings, Back and Esc follow the same settings routes as All.

On desktop, Friends search matches display names, trims surrounding whitespace and ignores case. Friend Direct/Group search matches room names and ignores case. Friends shows loading progress or an error with Retry; the Refresh button also reloads it. Direct/Group can show an empty list while their data is loading or unavailable and have no directory-loading retry control here. A filtered empty result alone does not prove no friendships or rooms exist. Desktop Friend and DingDong lists require a normal signed-in account.

## Mobile Chat controls

| Control or area | Location and behavior |
|---|---|
| All / DingDong / Friends | Main directory filters. Scroll the filter strip horizontally if needed. |
| Search chats / clear | Always-visible field. Filters as you type or submit; clear removes the query. Room lists match displayed room names or message previews, Friends matches names, and DingDong list matches names or type labels. Matching trims surrounding spaces and ignores case. |
| Friends subfilters | Friends lists people; Direct Chat and Group Chat list rooms. A person's row checks friendship before opening their profile. |
| DingDong subfilters | DingDong list lists owned bots; the row opens its own conversation and the avatar opens its profile. Direct Chat lists single-DingDong rooms; Group Chat lists DingDong groups. |
| DingDong → Direct Chat type chips | Filters available chats by DingDong type. Use All to clear the type filter. |
| Friends → Friends → Add Friend | Opens friend management at Send Request. |
| DingDong list → Add DingDong | Opens Pure creation. |
| New Chat | All or Friends → Direct Chat starts friend direct-room creation; Friends → Group Chat starts friend group creation. DingDong → Group Chat starts DingDong group creation. DingDong → Direct Chat has no creation button. |
| Refresh | Friends → Friends and DingDong list only. Reloads the chat directory; disabled with progress while running. A failure shows an error notice. |
| Hidden Chats | Header eye button opens the hidden-room sheet. See the hidden-room guide. |
| Pending chat changes | Header icon with a count of rooms whose exits or local cleanup need attention. Opens a sheet; select an idle row to open its settings. Busy rows show progress. An otherwise empty room list can also offer this control. See room recovery. |
| Room body / avatar | Body opens the conversation. A single-DingDong avatar opens its bot profile. A human-only direct-room avatar opens the sole counterpart's profile; other cases open participants. |
| Swipe right (English/Korean layout) | Reveals Chat room settings, eligible DingDong settings, and Pin to top / Unpin from top. Cobelly has no Chat room settings action here. |
| Swipe left (English/Korean layout) | Reveals Open, Mark as read when unread messages and a read action are available, and eligible Leave chat. Swiping only reveals buttons; tap a button to act. Tap the exposed row or outside it to close the rail. |
| Long-press / more button | Opens a scrollable sheet with the row's available settings, pin, reorder, open, read and leave actions. Dismiss it to cancel. |
| Reorder pinned item | With two or more visible pins, the swap-arrows button offers Move up among pinned items / Move down among pinned items where a neighbor exists. These actions also appear in a room's long-press/more sheet. |
| Friends / DingDong list pin | Separate pin button beside each person or bot. A failed pin-state load replaces it with Retry; that reloads pin state. Pin/reorder operation failures show an error notice. |
| Room pin-save failure → Retry | Retries the failed save. Confirm the displayed pin state and order before changing them again. |
| Failed to load chats → Retry | Reloads the list after a loading error. An empty search or filtered result alone does not mean loading failed. |

Changing mobile filters retains search, including switching All/DingDong/Friends. Clear it before interpreting an empty result. Room-preview matching is not a search of full message history. Normal account sign-in is required for directory actions; preview and agent sessions cannot dispatch them.

All, friend Direct Chat, friend Group Chat, DingDong Direct Chat and DingDong Group Chat keep separate room-pin orders. Friends and DingDong list have their own pins. DingDong Direct's type chips share that directory's pin order. Reorder controls use the pinned entries visible in the current result.

Leave chat opens a confirmation with the room name, Cancel and Leave chat. It is omitted for Cobelly, blocked or unsupported rooms, and group representatives; group leaving requires an active participant. An uncertain result offers Check status, which opens room settings. A pending local cleanup instead offers Retry for cleanup. See [room lifecycle](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/room-lifecycle.md).

Changing the account, search/filter, room state or active view can retire a row menu or pin-failure notice. Reopen the current row's controls rather than relying on an old action. [Hidden rooms](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/hidden-rooms.md) and [room recovery](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/room-recovery.md) cover their delegated sheets.

## Mobile full lists from Home

Home → Friends or DingDongs → See all opens a separate full list, rather than the Chat tab's room filters.

| Control or area | Behavior |
|---|---|
| Search friends / Search | Filters as you type, trimming surrounding spaces and ignoring case. Friends matches names; DingDongs matches names or displayed type labels. Delete the text to clear it; these fields have no separate clear button. |
| Refresh / pull down | Reloads the directory and keeps search. Refresh is disabled with progress while loading/retrying. With retained data it refreshes; otherwise it restarts initial loading. The list can be pulled even when empty. |
| Failed list → Retry | Uses the same reload action. The error can appear above retained results; Retry is disabled while busy. Clear search before interpreting an empty result as no entries. |
| Add Friend / Add DingDong | Header plus opens Send Request or Pure creation respectively. |
| Friend row | Checks friendship before opening that person's profile. |
| DingDong body / avatar | Body opens the bot's conversation, including Cobelly's system chat; avatar opens the bot profile. Each row also shows its type. |
| Pin / reorder | Uses the same friend or bot pins as Home and Chat's corresponding people/bot list. With at least two visible pins, the swap-arrows menu offers available up/down moves. Searching limits the visible set used for reordering. |
| Back | Returns to the previous screen, or Home when no page can be popped. |

These full lists require a current normal account and guard current friendship/bot availability. Pin-state Retry and pin/reorder failure notices follow the separate people/bot controls described above. They do not pin a room in All or a Direct/Group room directory.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/directory.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-24 (desktop directories; mobile Chat and Home full-list controls, pins and list leaving). UI labels use the English app language.
