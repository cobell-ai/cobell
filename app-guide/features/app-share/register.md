# Register an App Share app

## Desktop

1. Start the web app on the desktop that will host it. Note its local address and port.
2. Open Apps in the top navigation → Register app.
3. Enter App name and Local server address, then register.
4. Copy the Integration configuration file path shown after registration. Configure the local app to read it and implement the App Share status endpoint. An address alone does not complete integration.
5. In Operate, check the host and app runtime state. Configure [chat sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/operate.md).

## Mobile

1. More → Apps → Register app.
2. Enter the name and register. Successful registration opens Operate.
3. Connect this registered app on a hosting desktop. Mobile registration has no local-address field or integration-file dialog.
4. Once a desktop binding exists, choose it with Change host and enable a chat share.

If mobile registration cannot be confirmed, use Retry to check the same request before registering another app. On either platform, verify the catalog and operation state after an error.

The host desktop, local web app and a Cobell GUI or CLI hosting session must remain running. Registration and [Gear permission](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/gear.md) are separate.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/register.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-10-23.
