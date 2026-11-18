# Log out of this device: screen reference

End the current account session and finish local cleanup.

## Open this screen

**Desktop:** Click your avatar/name near the upper-right → Profile → Logout.

**Mobile:** Fifth bottom tab More → profile card → Logout.

## Controls

| Control or area | Location and behavior |
|---|---|
| Logout | Starts sign-out. |
| Cancel / Confirm | Desktop confirmation actions. |
| Mobile confirmation | Confirms that this device should sign out. |
| Finishing sign out | Waits for previous-session cleanup. |
| Try again / Try cleanup again | Retries failed finalization or credential cleanup. |

## CLI

`cobell logout` controls an existing session without opening the normal window. Closing the TUI with `/quit` is a separate action.

## Conditions and results

Logout differs from closing the app and from remotely unregistering a device. If finalization is uncertain, finish its recovery flow rather than assuming credentials have been removed.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/logout.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
