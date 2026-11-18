# Connect a KnowledgeBox workspace: screen reference

Choose the folder holding a Pure DingDong’s knowledge on this device.

## Open this screen

**Desktop:** Management → Pure → select the DingDong → K-Box/KnowledgeBox → Workspace settings in the left panel.

**Mobile:** Shortcuts → DingDong → select a Pure DingDong → Knowledge → Knowledge folder.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Connect folder | Opens the directory picker. Choosing a folder starts connection; canceling the picker leaves the binding unchanged. |
| Use Cobell default location | Creates/connects the app-managed desktop location; disabled when that location is already current and ready. |
| Change workspace | The dialog title when a binding exists. Connect folder or the default-location action replaces the current binding; previous files stay in place. |
| Cancel | Desktop closes the setup dialog without another connection request. The actions disable while setup is pending. |
| Mobile Create app folder | Appears when no binding exists. Prepares the current device's app-managed folder. It is not an arbitrary-directory picker. |
| Try again / Retry | Desktop retries a failed binding read. Mobile checks local state and explicitly retries pending file-information synchronization. |
| Disconnect folder | Mobile asks for confirmation, then removes the binding while retaining files. Cancel keeps the connection. |
| Create missing folder again | Offered for a missing managed mobile folder. Confirm recreates the folder; it cannot restore removed files and clears saved descriptions for files that no longer exist. |
| Location/status card | Desktop shows location and managed/connected/unavailable state. Mobile shows setup, ready, unavailable, pending sync, incomplete check or recovery needed. Managed mobile paths are not displayed. |
| Knowledge file recovery / Review pending changes | Mobile opens the recovery view for affected paths; folder Retry does not resolve those changes automatically. |

## Conditions and results

Workspaces are per DingDong and per device. Use a separate folder for each DingDong; nested folders can expose the same files to more than one DingDong. Changing Gear does not erase the workspace. Desktop switching keeps previous files. Mobile disconnect keeps files, but old descriptions and summaries do not carry over on reconnect. Cobelly has no KnowledgeBox.

On desktop, selecting the current ready folder reports that it is already connected. A folder occupied by another DingDong produces a conflict; choose a different folder. If the connection fails, inspect the displayed binding before retrying because a local change may have been saved before synchronization failed.

On mobile, Folder synchronization is pending means the local folder was saved; use Retry when connected. Recovery needed pauses file updates until the affected paths are reviewed. An occupied/conflicting folder is left untouched. A deleted KnowledgeBox cannot simply be reconnected; the status explains that its files remain on the device.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

[Import files into KnowledgeBox](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/import-files.md) · [Configure KnowledgeBox Use permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md)

[Review unfinished mobile file changes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/recovery.md)

Reviewed: 2026-10-23. UI labels use the English app language.
