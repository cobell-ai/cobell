# Register an App Share app

After registration, choose **Create avatar** or **Skip for now**. If a DingDong registered the app, direct its owner to **Apps → Operate → Settings** in a normal sign-in to create or change its avatar.

## Static files on desktop, Android or iOS

1. Sign in normally. Open Apps → Register app (Shortcuts → Apps on mobile) and enter an app name.
2. Choose **Choose KnowledgeBox folder**, select the folder containing the site, and confirm the start page (default `index.html`). Choose the fallback option if unknown page URLs should open that page.
3. Register. With a folder, this device becomes the host. You can also register just the name on mobile, then choose a folder under **Operate** and select that device in **Change host**.
4. To check the app before sharing, choose **Open on this device** from its details. To share it, add a chat in **Operate** and enable sharing for that chat. Keep Cobell in the foreground on mobile. Saved file changes appear on the next load.

If mobile registration cannot be confirmed, use Retry to check the same request before registering another app. To publish from an agent session, follow the [DingDong tool workflow](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/gear.md).

## Desktop web server

1. Start the web app on the desktop that will host it. Note its local address and port.
2. Open Apps in the top navigation → Register app.
3. Enter App name and Local server address, then register.
4. Use the displayed integration configuration file and implement the App Share status endpoint.
5. In Operate, check the host and app status. Enable [chat sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/operate.md).

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/register.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-11-21.
