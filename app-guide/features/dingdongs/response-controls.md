# Request, interrupt, resume or stop a response

Control the selected DingDong’s work in the current room or thread.

## Start here

**Desktop:** Use the orange circular Bell on a single-DingDong room/thread header, its participant row or beside its message. Expand the participant list to choose a DingDong in a shared room.

**Mobile:** Use the DingDong's Bell on a single-DingDong room/thread header, participant row or beside its message. Use a normal sign-in.

## Desktop steps

1. Open the intended room and thread.
2. Check the target DingDong and click its idle Bell. A Bell beside an old message still targets the DingDong in that message's thread, not just that one message. If configuration/Gear is missing, complete [Gear setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) before requesting again.
3. While running, choose Interrupt DingDong and wait for interrupted controls.
4. Choose Resume, enter nonblank continuation instructions and submit, or choose Stop to end that interrupted run. Stop has no additional confirmation. A blank desktop resume prompt does nothing.
5. For a delayed response, open its countdown to Cancel or Restart. For queued work, open the numeric badge when available; the owner can cancel individual waiting entries.

## Mobile steps

1. Open the target room/thread and choose the DingDong.
2. Tap Request AI response. If the personal-room Bell opens Gear setup, save and return, then press Bell again; saving that setup does not itself run the request.
3. While running, use Interrupt DingDong. In interrupted state, use Resume with required nonblank guidance or Stop. Mobile disables Resume for a blank prompt. Enter adds a line; tap Resume to submit. A successful resume closes its sheet; failure keeps the prompt for correction/retry.
4. Open a countdown to Cancel or Restart countdown. Dismissing its sheet without choosing an action keeps the delayed response.
5. As owner, open the numeric Scheduled responses badge to inspect or cancel queued entries. Beside a message, this badge is below the run control. Tap the avatar to open the DingDong's profile. Pull to refresh when the queue list is visible; a failed read offers Retry.

## Distinguish delayed and queued work

Restart resets a delayed response to its full original delay. It does not add another delay to the remaining time or change the saved Auto Reply setting. Countdown Cancel acts immediately on that delayed response.

The numeric badge opens already-queued requests for this DingDong in the current room/thread. It is owner-only, not a calendar of all future routine occurrences. Desktop header/participant/message countdowns do not include that badge while counting; use it when available. Queue rows display order, creation time and a trigger or prompt preview; there is no edit/reorder action.

Cancel a row to remove that one waiting entry. There is no extra confirmation. It disappears during the request and is restored on failure; cancellation does not disable the source routine. Desktop Close/mobile Back keeps other pending entries. Reopen/Retry a failed desktop read, or refresh/retry a mobile read. Mobile's cancellation-failure banner can be closed; use the restored row to retry cancellation.

When mobile rows remain after a failure, scroll past the last row to find its banner. A read-failure banner offers Retry; a cancellation-failure banner offers Close. If a short list cannot be pulled down to refresh, use Back and reopen the queue. An empty list can be pulled to refresh. Long prompt previews can be truncated, and rows do not open a separate detail view.

## Waiting questions are a different state

The question-mark Bell opens [questions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/answer-questions.md) or Shell approval. Neither the waiting-question control nor the question editor offers Stop. Cancel/Back there leaves the run waiting; it does not interrupt or stop it.

## Completion, limits and recovery

Bell permission, enabled state, room access, compatible Gear and current AI availability can block a request. A spinner or command cooldown can temporarily disable input. Check current status after an error before repeating the action. Status Retry reads current state; it does not resend the failed command. Even when a countdown reaches zero or the desktop countdown disappears, wait for the server's run-state update.

Cancel closes the resume form without resuming. Do not depend on a text draft after closing. If the execution changes while Resume is open, close the form and reopen it from the current execution. Closing the form or navigating away does not cancel an already-sent request.

While sending, Resume and Cancel are disabled on both platforms and the prompt remains editable. The request uses the trimmed text from when Resume was pressed; later edits do not change that request. Enter adds a line in the multiline prompt; use Resume to submit. Mobile also blocks Back during submission. Clicking outside the desktop dialog still closes it, without cancelling the request already sent.

A quota termination can show a retry time. That label is neither a retry button nor automatic resumption. Inspect the reason and usage/reset information. Stop targets the current interrupted work; inspect the queued list separately.

Also find this under: Bell button, ask AI, interrupt, pause, resume, stop, queued response.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/response-controls.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

[Equip a DingDong with Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Answer questions from a DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/answer-questions.md)

Reviewed: 2026-10-24. UI labels use the English app language.
