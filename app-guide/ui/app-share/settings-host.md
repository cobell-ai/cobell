# App settings and hosting: screen reference

**Desktop:** Apps → owned app → Operate → Settings, This device's binding or Change host. **Mobile:** More → Apps → owned app → Operate → App settings or Change host.

| Control | Behavior |
|---|---|
| App name | Renames the registration; maximum 80 characters. |
| Image URL | Sets an HTTPS image URL; clear it to remove the image. |
| Allowed paths | One path prefix per line. `/` allows all paths; an empty list allows none. |
| End-to-end encryption | Changes encryption for app traffic. Changing it disconnects current viewers. |
| Save / Cancel or Back | Saves settings or leaves the editor. |
| Delete | Requires confirmation; removes registration and ends all shares and viewer connections. |
| Desktop This device's binding | Sets this desktop's local server address for the app and shows its integration configuration path. |
| Desktop Replace integration secret | Replaces this device binding's secret when saving the binding; update the local app's integration accordingly. |
| Desktop binding → Integration configuration file / Delete | Reopens the configuration path, or removes only this desktop's binding. This Delete is separate from deleting the app registration in Settings. |
| Change host | Lists devices already bound to this app. Mobile selects a radio row then Change host; desktop selects a listed device. |

Mobile can select an existing host but cannot create a local binding or display a local integration file. Changing host closes existing connections; viewers must reopen the app. Deleting a registration does not delete the local web app's source files.

[Settings steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/settings-host.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/README.md)

Reviewed: 2026-10-23. Labels use the English app language.
