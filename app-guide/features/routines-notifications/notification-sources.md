# Choose DingDong notification sources

## Select a source

1. Open Add notification source in a DingDong-notification hook.
2. Choose a type:
   - Chat: select a DingDong, then all other chat rooms or specific rooms.
   - Flow: select a Flow, all or selected nodes, and optionally an assigned DingDong filter.
   - All activity: select the DingDong whose chat and assigned Flow-node notifications should match.
3. Add the selector. Repeat for other sources if needed.
4. Remove unwanted selectors with Delete source.
5. Save the whole hook.

## Completion and recovery

Any matching source can trigger the hook, subject to its text filters and execution condition. With All nodes off, select at least one node. No filter accepts any assigned DingDong within the chosen Flow/node scope.

If catalogs or nodes fail to load, leave the selector, reload the corresponding source data and reopen it. If an assigned DingDong is no longer available, select another or No filter. For the current response DingDong in its current room, choose Current-room responder in the hook editor instead of Other sources.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/notification-sources.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
