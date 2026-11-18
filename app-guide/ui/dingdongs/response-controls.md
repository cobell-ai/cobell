# Request, interrupt, resume or stop a response: screen reference

Control the selected DingDong’s work in the current room or thread.

## Open this screen

**Desktop:** Use the orange circular Bell on a single-DingDong room/thread header, its participant row or beside its message. In a multi-participant room, expand the participant list to choose a DingDong.

**Mobile:** Use the DingDong's Bell on a single-DingDong room/thread header, participant row or beside its message. Use a normal sign-in.

## Controls

| Control or area | Location and behavior |
|---|---|
| Mobile message avatar | Opens that DingDong's profile for this room. The Bell and numeric queue badge are separate controls. |
| Request AI response | Idle Bell requests work for this DingDong in this room/thread. A Bell beside an older message does not limit context to that one message. Enabled state, Bell permission, room access, available AI features and compatible Gear can block a new request. |
| Missing Gear | Use [Gear setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md). Mobile's personal-room Bell can open setup instead of running; after saving and returning, press Bell again. Desktop can report missing configuration/Gear. |
| Interrupt DingDong | Pause icon shown for running work. Sends an interrupt request. Wait for the interrupted state before using Resume or Stop; a spinner is not proof of success. |
| Resume | Play icon shown in interrupted state. Opens a desktop dialog or mobile bottom sheet. |
| Tell DingDong how to continue | **Required nonblank** continuation instructions. Desktop's Resume button does nothing with blank text; mobile disables it. Enter adds a line in these multiline fields; use Resume to submit. |
| Resume submit / Cancel | Submit uses the trimmed text at the time Resume is pressed. Success closes the form; failure keeps the prompt and shows an error. Cancel closes without resuming. Cancel/Resume are disabled while sending, but the text field remains editable on both platforms. Those edits do not change the request already sent. Mobile also blocks page Back during submission. |
| Desktop resume backdrop | Clicking outside the dialog closes it, including while sending. Closing does not cancel a request already sent. |
| Stop | Available in interrupted state. Sends Stop immediately without another confirmation. To stop running work through these controls, interrupt first. |
| DingDong needs your answer | Waiting state opens [questions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/answer-questions.md) or a Shell approval request. This waiting control and its question editor have no Stop action. |
| Scheduled response countdown | Shows remaining seconds and opens desktop's popup or mobile's bottom sheet. Desktop overlays a spinner while a command is in flight and blocks another popup while its menu is open. It is distinct from the queued-work badge. |
| Desktop Restart / mobile Restart countdown | Resets the current delayed response to its full original delay, not remaining time plus another delay. It does not change the saved Auto Reply delay or a recurring schedule. |
| Countdown Cancel | Cancels that delayed response immediately. Dismissing the popup/sheet without choosing an action keeps it scheduled. |
| Status error / Retry | Reads current run status instead of repeating a failed command. Desktop can retry failed status reads for multiple visible DingDongs in the same thread. Mobile's error icon refreshes this target when a failure is shown for an inactive run. |
| Termination message | Displays a reason. A quota-related retry time is information, not a retry button or a guarantee of automatic resumption. |

## Scheduled responses list

| Control or area | Behavior |
|---|---|
| Numeric queue badge | Appears for queued work and is available only to the DingDong owner in a normal account. Opens this DingDong's queue in the current room/thread. Mobile displays 99+ for counts above 99. |
| Mobile badge placement / return | Beside a message, the queue badge sits below the run control; in the header or participant row it sits next to it. Tap the badge to inspect queued work. Returning to the same room/thread refreshes the run status without replaying a command. |
| Desktop countdown surfaces | Header/participant/message countdowns use a separate control without the queue badge. The badge may be absent there while a delay is counting. |
| Queue row | Shows position, local created time, trigger type or prompt preview. Long previews can be truncated. The row has no open-detail, edit or reorder action; use its separate Cancel control. This is already-queued work, not every future occurrence of a recurring routine. |
| Row Cancel / close icon | Cancels one waiting entry immediately without another confirmation. It disappears optimistically and returns if cancellation fails. It does not disable the source notification hook or schedule. |
| Desktop queue Retry / Close / backdrop | Retry reloads a failed queue read; its loading spinner replaces Retry. Reopening also reads the list. Background queue refreshes can retain usable rows. Close or clicking outside leaves pending work intact. A cancellation failure shows a message; retry that row only after checking the current list. |
| Mobile pull-to-refresh / read Retry | Reloads the queue. An initial read failure offers Retry. A failed refresh can retain rows and show a load-failure banner with Retry. When rows exist, the banner is after the last row; scroll down to find it. A failed cancellation restores its row and shows a cancellation banner. |
| Mobile banner Close | Hides the message. It does not repeat or reverse cancellation. Cancellation banners have no read-Retry button; use the restored row to retry cancellation. |
| Mobile Back | Leaves the queue without cancelling its remaining entries or stopping active work. Account/access changes can retire the queue view. |

On mobile, an empty list can be pulled to refresh. If a short populated list cannot be pulled down, go Back and reopen the queue to reload it. Changes to the queued count and successful cancellations also refresh an open list.

## Conditions and results

Busy indicators and short command cooldowns can disable input. Current server status and newer run events can replace a local pending state; a failed command can restore the earlier state. Check the current control before repeating a request. Countdown expiry, including the desktop countdown disappearing, does not prove a response has started; mobile refreshes status when its countdown reaches zero.

If the execution changes while Resume is open, close the form and reopen it from the current execution. Closing the form or navigating away does not cancel an already-sent request.

AI feature availability can block new requests, Resume and countdown restart while status reads or cancellation remain available. These controls operate on the selected DingDong/thread; inspect queued entries separately rather than assuming Stop cleared them all.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/response-controls.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Answer questions from a DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/answer-questions.md)

Reviewed: 2026-10-24. UI labels use the English app language.
