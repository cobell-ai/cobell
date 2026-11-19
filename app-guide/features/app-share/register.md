# Register an App Share app

## Desktop web server

1. Start the web app on the desktop that will host it. Note its local address and port.
2. Open Apps in the top navigation → Register app.
3. Enter App name and Local server address, then register.
4. Copy the Integration configuration file path shown after registration. Configure the local app to read it and implement the App Share status endpoint. An address alone does not complete integration.
5. In Operate, check the host and app runtime state. Configure [chat sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/operate.md).

## Static files on desktop, Android or iOS

1. Sign in normally. Open Apps → Register app (More → Apps on mobile) and enter an app name.
2. Choose **Choose KnowledgeBox folder**, select the folder containing the site, and confirm the start page (default `index.html`). Choose the fallback option if unknown page URLs should open that page.
3. Register. With a folder, this device becomes the host. You can also register just the name on mobile, then choose a folder under **Operate** and select that device in **Change host**.
4. Enable sharing for the intended chat in Operate. Keep Cobell in the foreground on mobile. Saved file changes appear on the next load.

If mobile registration cannot be confirmed, use Retry to check the same request before registering another app. To publish from an agent session, follow the [DingDong tool workflow](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/gear.md).

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/register.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-11-19.
