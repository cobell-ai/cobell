# Read announcements: screen reference

Read published service announcements and distinguish them from DingDong notifications.

## Open this screen

**Desktop:** Click Start, then Announcement in the empty landing view.

**Mobile:** Home → announcement banner → Details. Home's notifications icon or Announcements button opens the inbox instead.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop announcement list | Selects a published announcement for reading in the dialog. |
| Try again (desktop) | Reloads announcements after a load error. |
| Close / Back | Leaves the announcement reader. |
| Mobile banner title / summary | Displays one unread, unexpired announcement. The body itself has no tap action. |
| Details (mobile banner) | Opens the published notice link in an external application. After successful launch, attempts to save this revision as read. |
| Dismiss announcement (mobile banner) | Close icon shown only when the notice allows dismissal. Attempts to save it as read without opening the link. |
| Banner progress | While either action runs, both controls are disabled and Details shows progress. |
| Mobile notification inbox | Includes announcement and DingDong notification entries with read state. |

## Conditions and results

After a successful list read, an empty announcement list means no entries were returned for that view. An absent Home banner alone can also mean notices were read, expired or are still loading.

Read or dismiss the current announcement. Updated notices can appear again. Dismissal applies to this app installation; it does not delete the published notice or guarantee dismissal on another device.

If opening a link or dismissing a notice fails, check the result and retry using the current banner controls after progress finishes. A notice can appear again after a failed dismissal.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/announcements.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/README.md)

Reviewed: 2026-10-24 (mobile Home banner controls/read-state behavior; desktop reader and full inbox guidance retained). UI labels use the English app language.
