# Use the supplied Linux server companion: screen reference

Run Cobell on a supported Linux machine without a physical desktop session.

## Open this screen

**Desktop:** Use the matching Linux app/CLI distribution and its server helper from a normal OS-user account.

**Mobile:** A signed-in mobile app can approve the Linux device’s login code.

## Controls

| Control or area | Location and behavior |
|---|---|
| cobell server | Starts the virtual desktop runtime. |
| cobell login | Starts code approval; without a display it can start the virtual runtime automatically. |
| cobell status | Checks session state. |
| cobell logout | Ends the account session. |
| cobell server-stop | Stops app/tools and the virtual runtime. |
| cobell agent --token-file PATH | Starts the agent-oriented server using a protected token file. |
| User service | Uses the distribution’s cobell.service for persistent operation. |

## CLI

Commands: `cobell server`, `cobell login`, `cobell status`, `cobell logout`, `cobell server-stop`. Agent mode: `cobell agent --token-file /absolute/path/to/token`. The bundled user service and manual server start should not be started simultaneously.

## Conditions and results

Use the same OS account and existing app/keyring identity. server-stop keeps stored normal-login state; logout ends it. Screen tools see the virtual desktop, not a physical monitor or another user’s session. Agent tokens use a protected local file; a forced logout requires explicit sign-in again.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-server.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

[Sign in using another signed-in device](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md) · [Sign in as a device agent](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md) · [Prepare the Linux server environment](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-setup.md) · [Run the Linux companion as a user service](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-service.md)

Reviewed: 2026-10-03. UI labels use the English app language.
