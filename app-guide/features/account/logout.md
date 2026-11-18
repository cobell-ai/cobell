# Log out of this device

End the current account session and finish local cleanup.

## Start here

**Desktop:** Click your avatar/name near the upper-right → Profile → Logout.

**Mobile:** Fifth bottom tab More → profile card → Logout.

## Desktop steps

1. Open Profile → Logout.
2. Confirm the logout.
3. Wait for the login screen before using another account.

## Mobile steps

1. Open More → profile card → Logout.
2. Confirm the sign-out.
3. Wait for Finishing sign out; if cleanup fails, use the recovery action.
4. Start another sign-in only after the login screen becomes available.

## CLI steps

`cobell logout` controls an existing session without opening the normal window. Closing the TUI with `/quit` is a separate action.

## Completion, limits and recovery

Logout differs from closing the app and from remotely unregistering a device. If finalization is uncertain, finish its recovery flow rather than assuming credentials have been removed.

Also find this under: sign out, switch account, cleanup.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/logout.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
