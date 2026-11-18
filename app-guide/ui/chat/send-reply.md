# Send messages, mentions and replies: screen reference

Write a normal message or reply to a particular message.

## Open this screen

**Desktop:** Open the room from the chat panel and use its bottom composer.

**Mobile:** Open the room from Chat and use the bottom composer.

## Controls

| Control or area | Location and behavior |
|---|---|
| Message input | Enter the draft. |
| Send | Sends to the current room/thread. |
| Mention suggestions | Choose the intended person or DingDong from matched suggestions. |
| Message More / right-click → Reply | Adds a reply preview to the composer. |
| Reply preview Close | Cancels the reply target without sending. |
| Pending message indicator | Shows sending progress. Wait for the result; the indicator itself has no action. |
| Failed message Resend / Try again | Desktop Resend or mobile Try again starts another send attempt when the message and room allow it. The row returns to pending. |
| Failed message Delete / Delete message | Removes the failed local entry without a confirmation dialog. This does not delete or retract a copy that reached the service. |
| Reply chain | Filters related messages on desktop. |

## Conditions and results

Closed rooms and closed threads do not allow new messages. A failed message can remain visible even when it cannot be retried. Messages sent on your behalf by Cobelly carry a corresponding marker.

## Failed-send controls

Desktop Resend is hidden when sending to the room is unavailable, or the failure reports a missing room, closed room or uncertain delivery. Delete can remain available to remove the failed local entry.

Mobile failed-send controls apply to your unconfirmed messages, including a failed thread root. Use Try again when offered; unavailable, closed or read-only rooms can restrict it. P2P file offers do not use message retry. Delete message discards the local failed entry and can cancel a failed P2P offer's local transfer.

During a mobile retry, wait for the result before retrying or deleting that row. If the app reports a send failure or retry does not proceed, reopen the room and check the current message and sending status.

These controls are separate from deleting a confirmed message through its More menu. Removing a failed entry is local cleanup, not a remote deletion or delivery check. A pending spinner does not confirm that another person received or read the message.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/send-reply.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.

Failed-send controls and pending indicators checked: 2026-10-24.
