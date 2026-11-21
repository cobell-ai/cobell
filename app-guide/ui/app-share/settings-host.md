# App settings and hosting: screen reference

**Desktop:** Apps → owned app → Operate → Settings, This device's binding or Change host. **Mobile:** Shortcuts → Apps → owned app → Operate → App settings, Choose KnowledgeBox folder or Change host.

| Control | Behavior |
|---|---|
| App name | Renames the registration; maximum 80 characters. |
| App avatar | Choose a style, optionally add a prompt and up to five reference images, then generate. Review and apply the candidate, generate another, or remove the current avatar. |
| Allowed paths | One path prefix per line. Use `/` to allow all paths or a specific prefix to restrict access. An empty list also allows all paths. |
| End-to-end encryption | Changes encryption for app traffic. Changing it disconnects current viewers. |
| Save / Cancel or Back | Saves settings or leaves the editor. |
| Delete | Requires confirmation; removes registration and ends all shares and viewer connections. |
| Desktop This device's binding | Sets this desktop's local server address for the app and shows its integration configuration path. |
| Desktop Replace integration secret | Replaces this device binding's secret when saving the binding; update the local app's integration accordingly. |
| Desktop binding → Integration configuration file / Delete | Reopens the configuration path, or removes only this desktop's binding. This Delete is separate from deleting the app registration in Settings. |
| Choose KnowledgeBox folder / Disconnect source | Bind or replace a local static folder and its start page, or disconnect it from this device. The files stay in the KnowledgeBox. |
| Change host | Lists devices already bound to this app. Mobile selects a radio row then Change host; desktop selects a listed device. |

Mobile serves its selected folder while Cobell is in the foreground. Changing host closes existing connections; viewers must reopen the app. Deleting a registration does not delete the local web app's source files.

[Settings steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/settings-host.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/README.md)

Reviewed: 2026-11-21. Labels use the English app language.
