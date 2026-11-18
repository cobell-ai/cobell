# Connect a KnowledgeBox workspace

Choose the folder holding a Pure DingDong’s knowledge on this device.

## Start here

**Desktop:** Management → Pure → select the DingDong → K-Box/KnowledgeBox → Workspace settings in the left panel.

**Mobile:** Shortcuts → DingDong → select a Pure DingDong → Knowledge → Knowledge folder.

## Desktop steps

1. Open Management → Pure and select the DingDong.
2. Choose K-Box/KnowledgeBox and Workspace settings.
3. Choose Connect folder for an existing folder, or Use Cobell default location.
4. Choosing a folder starts setup; wait for it to finish and check the current location. Canceling the picker does not connect a folder.
5. To switch folders, reopen Workspace settings. In Change workspace, connect another folder or choose the default location; files in the previous folder stay there.
6. If the selected folder is already current, read the notice. If another DingDong owns it, choose a different folder. A failed binding read offers Try again.

## Mobile steps

1. Open the Pure DingDong’s management detail → Knowledge → Knowledge folder.
2. Choose Create app folder if setup is required. Mobile uses the app-managed folder rather than letting you bind an arbitrary local directory.
3. Wait for Folder is ready. If synchronization is pending, the local folder is saved; use Retry when connected to synchronize its file information.
4. If file changes need review, open the recovery entry and inspect affected paths before continuing updates. Retry alone does not resolve them.
5. Use Import files or Import folder from the Files view to bring in other apps' content.
6. For a missing managed folder, Create missing folder again asks for confirmation. It creates the folder but does not restore deleted files. To disconnect, choose Disconnect folder and review the confirmation; Cancel keeps the binding.

## Completion, limits and recovery

Workspaces are per DingDong and per device. Use a separate folder for each DingDong; nested folders can expose the same files to more than one DingDong. Changing Gear does not erase the workspace. Desktop switching keeps previous files. Mobile disconnect keeps files, but old descriptions and summaries do not carry over on reconnect. Cobelly has no KnowledgeBox.

Recreating a missing mobile folder clears saved descriptions for files that no longer exist. An occupied/conflicting folder is left untouched. A deleted KnowledgeBox cannot be reconnected through this action; its files remain on the device.

After a setup or check failure, read the current local status before repeating an action. A local change may have committed even when its synchronization failed. Folder checks do not themselves delete files or restore removed content.

Also find this under: connect local folder, knowledge storage, workspace, app folder.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/workspace.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

[Import files into KnowledgeBox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-files.md) · [Configure KnowledgeBox Use permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md)

[Review unfinished mobile file changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md)

Reviewed: 2026-10-23. UI labels use the English app language.
