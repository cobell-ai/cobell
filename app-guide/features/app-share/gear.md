# Let a DingDong manage selected apps

1. [Register the app](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/register.md) under the same account.
2. Open the Gear editor: desktop Management → Gear, or mobile Shortcuts → DingDong → Gear.
3. Add the App Management built-in Toolbox. Refresh apps and select the registered apps it may manage.
4. Save the Gear and assign it to the intended DingDong.
5. Ask the DingDong to manage sharing for the selected app. Confirm availability and access in [Operate](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/operate.md).

## Publish a static app from a mobile agent device

1. In Gear, enable App Management and permit the target phone for KnowledgeBox Use. On the phone, enable **Allow Toolbox on This Device** and **Allow Access to KnowledgeBox Files on This Device**. Keep Cobell in the foreground for hosting.
2. Use `manage_files` to list the target device's folder and check the HTML start page and assets. Use the returned device identity and `workspace_generation_id`. The `directory` passed to the tool is relative to that workspace.
3. Use `manage_app` to register the static folder on the selected device. Registration binds the files and selects the source device as host. Keep the returned `app_id`.
4. Ask the owner to select the new app in this Gear and save. In the intended chat, use `manage_app` to inspect the App and enable sharing for that chat.
5. To replace the source of an allowed app, use `manage_app` to set the new source folder. The owner can select the desired bound device under **Change host**. Revoking the app or device grant prevents a pending publication from changing the app.

If a mobile publication returns `effect_state: not_started`, correct the reported problem, for example by restoring the start page. For `not_applied`, check the rejection code and current permissions or revision. For `unknown` with `retry_policy: never`, check the catalog or app status before taking further action. Use normal sign-in to verify the page in the viewer, including on the host itself.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/gear.md) · [App Share index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/app-share/README.md)

Reviewed: 2026-11-19.
