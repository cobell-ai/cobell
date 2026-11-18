# Apps and registration: screen reference

**Desktop:** Top navigation → Apps (grid icon). **Mobile:** Fifth bottom tab More → Apps.

| Control | Behavior |
|---|---|
| My apps / My apps only | Filters the catalog to apps owned by this account. |
| Refresh | Reloads available apps and sharing state. |
| Register app | Desktop: asks for App name and Local server address. Mobile: asks for App name only. Names are limited to 80 characters. |
| Desktop Integration configuration file | Shows the generated file path after registration; the copy icon copies the path. The local app must read the configuration and implement the App Share status endpoint. |
| Open / app card | Opens an accessible share; asks for a room if several are available. |
| Operate | Opens an owned app's operation screen. |
| Mobile Open connections | Reopens retained viewer connections. |

Registration creates an account record. Mobile registration does not bind a hosting device. Desktop registration also prepares a local binding. A registered app is not necessarily running or shared. Registration does not grant a DingDong permission to manage the app.

Normal sign-in is required for the Apps and viewer interface. Agent sign-in can provide local apps through its supported hosting interface, but cannot view shared apps.

[Registration steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/register.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/README.md)

Reviewed: 2026-10-23. Labels use the English app language.
