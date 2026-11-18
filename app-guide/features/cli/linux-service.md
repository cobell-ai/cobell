# Run the Linux companion as a user service

Keep the virtual Cobell runtime running after the terminal session ends.

## Start here

**Desktop:** Use the supplied cobell.service with the installed Linux companion.

**Mobile:** Use mobile to approve normal login or manage the registered Linux device.

## Desktop steps

1. Complete Linux server setup and install the supplied user-service file.
2. Reload the user service manager and enable/start cobell.service.
3. Run cobell login and approve the code.
4. Check cobell status and journalctl logs.
5. Ask the machine administrator to enable lingering if operation after OS logout/reboot is required.

## Mobile steps

1. Approve the Linux service login from Profile’s verification-code approval.
2. Use the registered device and Gear settings to authorize intended tasks.
3. Use Linux service controls on the server to stop/start the runtime.

## CLI steps

From the supplied CLI distribution directory:

```sh
install -d -m 700 "$HOME/.config/systemd/user"
install -m 644 cobell.service "$HOME/.config/systemd/user/cobell.service"
systemctl --user daemon-reload
systemctl --user enable --now cobell.service
cobell login
journalctl --user -u cobell.service -f
```

Check with `cobell status`. Stop a managed instance with `systemctl --user stop cobell.service`; `cobell logout` ends the app account session.

## Completion, limits and recovery

Do not simultaneously start a manual cobell server and the user service. A normal saved login can be reused by the service; an agent token forcibly logged out is not automatically reused on restart. For an agent service, configure the supplied service’s command to use cobell agent --token-file with a protected local file.

Also find this under: systemd, background server, linger, service logs, restart agent.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/linux-service.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
