# Let a DingDong manage selected apps

1. [Register the app](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/register.md) under the same account.
2. Open the Gear editor: desktop Management → Gear, or mobile Shortcuts → DingDong → Gear.
3. Add the App Management built-in Toolbox. Refresh apps and select the registered apps it may manage.
4. Save the Gear and assign it to the intended DingDong.
5. Ask the DingDong to manage sharing for the selected app. Confirm availability and access in [Operate](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/operate.md).

## Publish a static app from a mobile agent device

1. In Gear, enable App Management and permit the target phone for KnowledgeBox Use. On the phone, enable **Allow Toolbox on This Device** and **Allow Access to KnowledgeBox Files on This Device**. Keep Cobell in the foreground for hosting.
2. Use `manage_files` to check the selected device's folder, HTML start page and assets.
3. Use `manage_app` to register the static folder on the selected device. Registration links the folder and selects that device as host.
4. Check the registration result. This Gear normally selects apps it registers. If automatic selection is off, ask the owner to select the new app and save. In the intended chat, use `manage_app` to inspect the App and enable sharing for that chat.
5. To replace the source of an allowed app, use `manage_app` to set the new source folder. The owner can select a linked device under **Change host**.

If the registration outcome is unclear, check the catalog and app status before trying again. Use normal sign-in to verify the page in the viewer.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/gear.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-11-21.
