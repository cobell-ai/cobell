# Unconfirmed link actions: screen reference

Recovery controls appear in Shared links or the link editor when a create, edit or revoke action cannot be confirmed. Receiving a link has a separate Check status flow.

| Control or message | Behavior |
|---|---|
| Result not confirmed / review required | Keeps changes disabled while the saved result is unresolved. |
| Back to links | Returns from the editor to its manager for review. |
| Check status / Refresh | Checks the original operation or reloads current links, as offered. |
| I've reviewed the links | Acknowledges the refreshed list when manual review is required. It does not prove that the original operation succeeded. |
| Creation not confirmed | A similar record may belong to another request. Do not infer success from its name or options alone. |
| Receiving Check status | Checks the same friend/join request; Send friend request/Join remains disabled while unresolved. |
| Previous participation no longer active | Reports that an earlier successful participation is no longer active; it does not submit a new join. |

An operation can complete on the service even when the app fails to receive its result. Inspect current records and the reported status before creating a replacement or retrying a change.

[Recovery steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/chat/link-recovery.md) · [Shared links](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/chat/shared-links.md)

Reviewed: 2026-10-23. Labels use the English app language.
