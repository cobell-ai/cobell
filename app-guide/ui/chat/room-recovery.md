# Recover an unavailable chat: screen reference

Check room access or finish a pending update to this device's room record.

## Where it appears

**Desktop:** An affected shared room's list row, chat/thread content or Chat Room Settings. The list uses a refresh icon outside Edit; the content/settings view shows the status and Check again.

**Mobile:** An affected room's list row, chat/thread notice or room settings. The list uses a Retry icon; the notice and settings offer Retry after verification fails.

## Desktop controls

| Control or status | Behavior |
|---|---|
| Room unavailable | Access could not be established. Check again verifies current room state. |
| Saved record needs updating | Finishes pending persistence on this device, including a known closure when applicable. |
| Finish removing this room from this device | Retries pending local cleanup. The room and its downloaded data can disappear from this device when cleanup succeeds. |
| Check again / row refresh icon | Checks the current room's availability or finishes pending recovery. Does not resend messages or start a new Leave/Close request. |
| Checking… | The check is busy; its button is disabled. |
| Recovery is not complete | The attempt did not finish recovery. Review the remaining status before trying again. Compact list icons do not display this explanatory text; open the room/settings to inspect it. |
| Recovery notice scroll | Long status text scrolls within the notice; its action remains below it. |
| This room is no longer on this device | Informational, with no recovery button. Compact list controls are hidden for this state. |

## Mobile controls

| Control or status | Behavior |
|---|---|
| Checking chat room | The room is temporarily read only while its status is verified. The list icon can show progress. |
| Could not verify chat room → Retry | Checks current room availability or pending recovery. Requires the current normal account; preview and agent sessions cannot use this action. |
| Retry while checking | Disabled until verification finishes or fails. Repeated taps do not start another simultaneous check. |
| Recovery notice scroll | Scroll long notice text while keeping space for saved messages. |
| Room settings after confirmed local removal | Can return to the Chat directory. A recovery check does not promise the room will reopen. |

## Mobile Pending chat changes

In Chat, the header's pending-actions icon appears while room exits or their local cleanup need attention. Its badge counts affected rooms. If the room list is otherwise empty, an expanded Pending chat changes button can also appear.

| Control or status | Behavior |
|---|---|
| Pending chat changes | Opens a scrollable sheet of affected rooms. Only available to the current normal account; preview and agent sessions cannot open it. |
| Leaving this chat… | The leave request is busy; the row shows progress and cannot be selected. |
| Checking whether you left… | Verification is busy; the row cannot be selected. |
| Removing local chat data… | Local cleanup is busy; the row cannot be selected. |
| Leaving this room hasn't been confirmed yet. | Select the idle row to open that room's settings and inspect the existing operation. |
| The server change completed, but local cleanup still needs to be retried. | Select the idle row to open room settings for cleanup. |
| Close / dismiss sheet | Returns to Chat without selecting a room. |

Selecting a row opens its room settings without submitting another Leave. Read the current status and use the offered check before repeating an action. After account or room changes, reopen the current controls. This list is separate from hidden-room visibility checks.

## Results and limits

An active room can become usable again. A confirmed closure or ended membership can leave read-only history or remove the room locally, depending on its state. A failed read alone does not establish deletion. Disappearance of the recovery notice does not prove that the room reopened.

Retrying recovery does not resend a message, join a room or start a fresh Leave/Close action. It may finish local changes required by an already established result. An uncertain action's own Check status control is a separate entry point; inspect that operation before issuing it again.

A normal signed-in account is required; mobile preview also disables dispatch. After an account/access change or leaving the screen, reopen the current room before checking. Leaving the screen does not undo work already dispatched. The desktop shared-room controls do not apply to the single personal DingDong chat.

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/room-recovery.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

[Find chats](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/directory.md) · [Hide, leave, close or clear a chat](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/room-lifecycle.md) · [Restore a hidden chat](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/hidden-rooms.md)

Reviewed: 2026-10-24. UI labels use the English app language.
