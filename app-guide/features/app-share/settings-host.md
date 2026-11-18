# Change an app's settings or host

## Settings

1. Open Apps → owned app → Operate → Settings/App settings. Mobile Apps is under More.
2. Set the name, optional HTTPS image URL and allowed path prefixes, one per line. `/` allows all paths; clearing the field allows no paths.
3. Set End-to-end encryption and save. Changing encryption disconnects current viewers.
4. To remove the registration instead, choose Delete and confirm. This ends its shares and connections; it does not remove the web app's files from the host.

## Hosting

1. On the intended desktop, open the registered app's Operate screen → This device's binding.
2. Set the local server address and save. Use the displayed integration configuration file in the local app.
3. Open Change host on desktop or mobile. Choose a device already bound to the app; mobile requires confirming Change host.
4. Wait for the app to verify, then check chat sharing. Existing viewers must reopen the app after a host change.

Mobile cannot create a hosting binding. If Change host has no devices, bind the app on a desktop first. Desktop Replace integration secret replaces that binding's integration secret; ensure the local app uses the updated configuration. For an existing binding, Integration configuration file reopens its path and Delete removes this device's binding without deleting the app registration.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/settings-host.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-10-23.
