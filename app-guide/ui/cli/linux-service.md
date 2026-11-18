# Run the Linux companion as a user service: screen reference

Keep the virtual Cobell runtime running after the terminal session ends.

## Open this screen

**Desktop:** Use the supplied cobell.service with the installed Linux companion.

**Mobile:** Use mobile to approve normal login or manage the registered Linux device.

## Controls

| Control or area | Location and behavior |
|---|---|
| systemctl --user enable --now | Starts the supplied service and enables subsequent starts. |
| cobell login / status | Approves or checks the running service’s account session. |
| journalctl --user | Reads that user service’s logs. |
| systemctl --user stop | Stops a managed runtime through its service owner. |
| loginctl enable-linger USERNAME | Administrator option for operation after logout/reboot. |
| cobell login --agent-token-file PATH | Explicit agent sign-in after a forced logout. |

## CLI

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

## Conditions and results

Do not simultaneously start a manual cobell server and the user service. A normal saved login can be reused by the service; an agent token forcibly logged out is not automatically reused on restart. For an agent service, configure the supplied service’s command to use cobell agent --token-file with a protected local file.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-service.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
