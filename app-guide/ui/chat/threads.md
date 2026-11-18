# Create, navigate and close threads: screen reference

Keep a side conversation in a nested thread.

## Open this screen

**Desktop:** Enable Create thread in the composer; click a thread-root bubble to open it.

**Mobile:** Enable Thread near the composer; tap the thread-root bubble to open it.

## Controls

| Control or area | Location and behavior |
|---|---|
| Create thread / Thread | Makes the sent content start a child thread. |
| Thread root / bubble | Opens the nested conversation. Mobile opens it only after the root's send is confirmed; pending and failed cards do not open. |
| Back / thread path | Returns to an enclosing conversation. |
| Close thread / Close thread (convert message) | On an eligible message inside a thread: replaces the root with that content and permanently closes the thread. Only the thread creator can do this. Mobile also offers it on an eligible root bubble. |
| Root menu → Delete thread | Deletes the selected thread with confirmation. |
| Mobile thread card previews | Shows the author/avatar, root text, positive reply count and latest nonempty reply preview. These are parts of the card, not separate profile or reply-list controls. |
| Mobile AI cannot see this thread | Read-only text on the card. It is not a hide/show toggle. |
| Mobile pending / failed thread card | Pending shows a spinner immediately. Failed cards offer the applicable [failed-send retry and local delete controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/send-reply.md). |
| Mobile Thread actions | Opens Close thread when the root itself is an eligible replacement, and Delete thread. Available for a current confirmed open root owned by your account when room sending is allowed; absent in read-only views. |
| Mobile Close thread confirmation | Read the warning and read-only replacement preview. Cancel or dismiss keeps the thread unchanged; Close thread confirms the current selection. |
| Mobile Delete thread confirmation | Scrollable warning with Cancel and Delete thread. There is no text-entry requirement. Cancel or dismiss leaves without deleting. |

## Conditions and results

Threads can nest five levels deep, excluding the main chat. Closure requires eligible confirmed content in the same thread; recipient-filtered content cannot replace the root. Closed threads cannot receive more messages. Thread creation and Hidden composer mode are mutually exclusive. CLI uses its separately documented terminal workflow.

Review the current thread and confirmation target before applying a change. If the action fails, inspect the thread before trying again. The failed-card Delete message control discards a local failed send and is separate from confirmed-thread Delete thread.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/threads.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/README.md)

[Exclude messages from AI context](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/hide-from-ai.md) · [Edit a message collaboratively](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/collaborative-edit.md)

Reviewed: 2026-10-03. UI labels use the English app language.

Mobile thread card and close/delete confirmation controls checked: 2026-10-24.
