# Talk to Cobelly from Start or Home: screen reference

Ask the account's System DingDong for help or a task.

## Open this screen

**Desktop:** Upper-left Start. Its empty landing view has a central prompt; an active Start conversation has a bottom input. Other main pages provide a top-bar Cobelly input.

**Mobile:** First bottom tab Home → System DingDong prompt card.

## Controls

| Control or area | Behavior |
|---|---|
| Prompt / Enter / Send/Bell | Submits text to Cobelly. Desktop Start continues its active thread; mobile opens the accepted request's Cobelly thread. |
| Mode selector | Chooses Questioner or Decider and saves that Cobelly behavior setting. Mobile Cancel leaves the mode selection unchanged. |
| Mode Retry | Retries failed mode data where offered. A failed save/read must be checked before assuming the mode changed. |
| Desktop compact cobell icon | When the top input is too narrow, opens an expanded input dialog. Close leaves the expanded view. |
| Desktop attachment menu | Displays Attach file and Attach image, but these Start/top-input actions currently have no implemented attachment behavior. |
| Desktop Start message Copy | Copies the displayed text. |
| Desktop Start Conceal / Reveal | Changes whether the message is hidden from AI context. |
| Desktop Start Reply / Edit / Delete | Visible controls currently have no connected action in this Start preview. Delete appears for own messages. |
| Announcement / Library | Desktop empty landing opens announcements or Library. Mobile Announcements opens the notification inbox; Library opens templates. |
| Home profile / notifications icon | Mobile opens Profile or the inbox, with an unread badge when applicable. |
| Home Friends / DingDongs strips | Mobile opens an entry, adds a friend/DingDong or uses See all. Failed directory reads offer Retry. |

## Conditions and results

Cobelly cannot be created, deleted or invited into another room and has no KnowledgeBox of its own. Device and Toolbox permissions still apply. The desktop Start preview differs from the full chat view; its visible unimplemented controls should not be treated as successful edits or deletions.

A message can be saved while its AI request fails. Read the failure notice and inspect the resulting thread before sending another copy. Library link opening is separate from publishing a prompt.

## Mobile Home details

| Control or state | Behavior |
|---|---|
| Profile name/avatar | Opens Profile. Shows Profile as a fallback when the current account's profile is not available. |
| Notifications | Opens the inbox; a positive unread count appears in the badge and tooltip. Announcements in the prompt card opens this same inbox. |
| Agent mode | Opens a scrollable Questioner/Decider dialog. The current option has a check. Tapping a different option closes the dialog and immediately attempts to save it; there is no separate Apply. Cancel or dismissal leaves it unchanged. |
| Mode loading / saving | Selector is disabled with progress. A failed initial mode read without a usable configuration shows an error and a separate Retry. A failed save or read after save shows a notice; check the resulting mode. |
| Prompt / keyboard Send / bell | One-line input. Blank or whitespace-only text cannot be sent. Submission disables the input, Send, Announcements and Library until it finishes. |
| Accepted prompt | Clears the unchanged draft, dismisses the keyboard and opens that request's Cobelly thread. If its AI request was rejected, a failure notice can appear while that saved thread still opens. |
| Send failure | Shows a failure notice and retains the draft. Check the resulting thread before repeating the request. |
| Friends strip | Scroll horizontally. A person's item checks friendship before opening their profile. Add Friend opens Send Request. |
| DingDongs strip | Scroll horizontally. Open a bot's conversation, including Cobelly's system chat. Add DingDong opens Pure creation. |
| See all | Opens the full Friends or DingDongs screen. The Home strips have no pin/reorder buttons; their entries use the corresponding directory's order. |
| Directory loading / Retry | Shows progress above retained strips. Failed reads offer Retry; it is disabled while loading/retrying. Retry refreshes retained data or restarts initial loading. Empty labels appear only after a settled successful read. |

Profile, inbox and Home directory actions require a current normal account and available targets. Reopen controls after account or access changes. Leaving Home does not cancel a request already sent; inspect the resulting thread before sending a duplicate.

The Home banner's Details opens an external notice, while the prompt card's Announcements opens the inbox. See [announcement controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/announcements.md). See all opens the separate [full friend/bot lists](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/directory.md), with their own search and pull-to-refresh.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/start.md) · [Area index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/README.md)

Reviewed: 2026-10-24 (mobile Home header, directories, prompt and mode controls; desktop guidance retained). UI labels use the English app language.
