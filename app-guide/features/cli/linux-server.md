# Use the supplied Linux server companion

Run Cobell on a supported Linux machine without a physical desktop session.

## Start here

**Desktop:** Use the matching Linux app/CLI distribution and its server helper from a normal OS-user account.

**Mobile:** A signed-in mobile app can approve the Linux device’s login code.

## Desktop steps

1. Install the matching supplied Linux distribution and CLI helper.
2. Prepare its documented Xvfb, D-Bus and keyring environment; use the existing keyring password if one already exists.
3. Use the bundled install.sh with the absolute app path when setting up the companion.
4. Run cobell login and approve the code from a signed-in app.
5. Use cobell, cobell manage and cobell status.
6. Stop the virtual runtime with cobell server-stop when finished.

## Mobile steps

1. On the Linux server run cobell login.
2. On your phone open Profile → Approve sign-in with a verification code.
3. Enter the code, review the server device and approve it.
4. Use the mobile device to configure server execution permissions and Gear targets as needed.

## CLI steps

Commands: `cobell server`, `cobell login`, `cobell status`, `cobell logout`, `cobell server-stop`. Agent mode: `cobell agent --token-file /absolute/path/to/token`. The bundled user service and manual server start should not be started simultaneously.

## Completion, limits and recovery

Use the same OS account and existing app/keyring identity. server-stop keeps stored normal-login state; logout ends it. Screen tools see the virtual desktop, not a physical monitor or another user’s session. Agent tokens use a protected local file; a forced logout requires explicit sign-in again.

Also find this under: headless Linux, server, virtual desktop, SSH, agent token file.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/linux-server.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

[Sign in using another signed-in device](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md) · [Sign in as a device agent](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-login.md) · [Prepare the Linux server environment](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-setup.md) · [Run the Linux companion as a user service](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-service.md)

Reviewed: 2026-10-03. UI labels use the English app language.
