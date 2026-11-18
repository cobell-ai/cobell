# Answer questions from a DingDong: screen reference

Complete the question set so the waiting DingDong can continue.

## Open this screen

**Desktop:** Click DingDong needs your answer, or use the question controls in the message.

**Mobile:** Tap DingDong needs your answer or the question-answer control.

## Controls

| Control or area | Location and behavior |
|---|---|
| Previous / Next | Moves within this editor while retaining its question drafts. Submitted messages can still offer read-only navigation. |
| Desktop suggestion choice | Selects one answer, then advances to the next question or the review. It does not submit the set. |
| Desktop dialog Type an answer → Use typed answer | Typing alone keeps a separate draft. Use typed answer selects it and advances; check Selected answer before review. |
| Desktop bubble custom input / checkmark / Enter / X | The checkmark or Enter selects nonempty custom text and advances to the next question or review. X hides the input while retaining its text and the selected answer in this bubble. Reopen to continue editing. Selecting a suggestion also keeps the separate custom draft. |
| Mobile waiting-question page | A suggestion selects the current answer without advancing. Use Next or Review answers. Enter directly... switches to a text field and clears an existing suggestion. Text is read into the answer draft directly; the multiline keyboard action adds a line. |
| Mobile Recent local context | Shows short excerpts already available on this device. It is read-only and is not a complete view of the DingDong's server-side context. |
| Mobile question bubble | A suggestion advances to the next question or review. Enter directly... opens custom input, whose edits update the answer draft. Use Review answers when ready. |
| Mobile page opened from the upload destination chooser | Uses the question bubble's controls: suggestions advance, missing answers use an inline Send anyway warning, and successful submission leaves the page open with the answered questions. Use page Back when finished. |
| Review answers / desktop bubble send-shaped icon / Edit | Opens review without sending. Each question's Edit returns to it; the bottom Edit returns to answering. No first suggestion is selected automatically. |
| Add images / Add files | Opens a picker for this question and uploads selected items before final answer submission. Requested kinds are highlighted, but both controls are available. Wait for progress to finish. |
| Attachment preview / filename / Remove attachment | Shows added images and file names/sizes. Desktop image previews open a viewer; click its image or backdrop, Close, or Escape to leave. Mobile question previews and file names/sizes on both platforms are read-only. Remove drops an item from this answer draft, without deleting the local file. Submitted attachments have no Remove control. |
| Continue without failed items | Clears the upload-failure state while keeping successfully added items. It does not retry the failed uploads. Reselect failed items to upload them. |
| Confirm & send | Submits the reviewed set and attachments. Upload in progress or an unresolved upload failure blocks submission. The desktop dialog and mobile waiting-question page close on success; the inline bubble and mobile upload-destination page show answered questions. |
| Send anyway | Explicitly accepts questions without text or attachments. Desktop and the mobile waiting-question page use a confirmation dialog; cancelling it returns without sending. The mobile bubble and upload-destination page first show an inline warning and change their submit button to Send anyway. Edit or question navigation clears that warning, so a later incomplete submission asks again. |
| Cancel / page Back | Leaves without submitting or stopping the waiting run. Closing can lose text drafts; there is no saved-draft or discard-confirmation flow. Answer/review drafts in separate views are not synchronized. |

The desktop dialog also closes when its backdrop is clicked. Closing does not cancel a submission already in progress. The mobile waiting-question page blocks Back during submission.

## Attachment and answer limits

- The whole question set shares a limit of **20 images and 10 files**, not that many per question.
- Each image is limited to **20 MiB** and each file to **100 MiB**. Count overflow is a failed selection rather than silently selecting a subset.
- Keep each text answer within **1,000 characters**. If a length error appears, shorten the answer and submit again.
- An attachment-only answer is valid. Review's text can be blank or say No answer; inspect its attachment list. A question with neither text nor attachments is sent as unanswered after confirmation.

## Composer upload destination

If a normal chat upload shows Where should these attachments go?, choose the intended DingDong and question. This opens that question's editor; add the items there and use Review answers → Confirm & send. Send to chat without answering continues as an ordinary chat upload and does not answer the waiting question. Dismissing the destination chooser cancels that upload action.

On mobile, this chooser is a scrollable bottom sheet. Each target shows the DingDong and question number/text. It lists current unanswered questions requesting the selected image/file kind; requests with answers or attachments already recorded are omitted. Changed or busy requests can disappear. Choosing a question opens its editor before a file is selected, so use Add images or Add files there.

## Conditions and results

A failed submission keeps the current editor's answers for retry. Check upload failures, text length and the current run before retrying. A busy command can briefly disable controls; the mobile bubble replaces its question controls with a sending label during submission. Account, room access or question/run changes can retire the view or reset its drafts; reopen the current request rather than sending a stale answer. Submitted question messages can still let you browse the questions without editing or resending. This editor and the waiting-question control have no Stop action. See [response controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/response-controls.md) for actions available in other run states.

The waiting control can instead open a [Shell approval](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/shell-approval.md) request. That uses its separate approval controls, rather than this question editor.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/answer-questions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

Reviewed: 2026-10-24. UI labels use the English app language.
