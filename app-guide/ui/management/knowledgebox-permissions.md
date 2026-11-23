# Configure KnowledgeBox Use permissions: screen reference

Set the Gear's KnowledgeBox file and shell policy.

## Open this screen

**Desktop:** Management → Gear → select an editable Gear → KnowledgeBox Use attachment's settings icon.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → KnowledgeBox Use settings. Device priority is a separate Connections section.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Tool execution/target devices | Selects registered devices and orders the selected entries. See the device-priority guide for checkbox/drag behavior and mobile's separate screen. |
| Continue after approval timeout | Toggles whether an unanswered approval expires. When on, the timed-out command is not executed and DingDong can continue within existing permissions; off keeps waiting. |
| Approval timeout (seconds) | Accepts digits from 1 to 86,400; default 60. Disabled while timeout is off. Valid edits update the draft; an invalid number is shown as an error without replacing the previous valid policy value. |
| Advanced settings | Expands or collapses execution mode, Git controls and the runtimes available for the selected mode. |
| Execution mode | Sandboxed follows the Gear's command policy. Unrestricted authorizes direct command execution through the Gear and hides the host and container runtime controls. |
| Allow writes / Allow workspace writes | Controls KnowledgeBox file changes. Turning it off clears Git local changes and the host-runtime flags. Containers have a separate switch. |
| Git permissions | Advanced settings separates local changes, fetch, push and discard. Workspace writes must be on to edit these switches. |
| Host runtime switches | Advanced Sandboxed controls for Python, JavaScript, C#, Dart, Go and Rust. They require workspace writes. |
| Container runtime / image fields | Advanced Sandboxed controls for container permission, languages and images. Containers default on for Dart and Go in new Gear. |
| Desktop Save / Cancel / close | Save validates, submits the Gear update and closes the dialog. Cancel/close discard its unsaved draft. Closing after Save is not proof that the network write was acknowledged. |
| Mobile Save / Back | Save sends a changed policy and leaves after success. Back with a dirty draft asks to keep editing or discard; saving blocks conflicting navigation. |
| Mobile Check saved settings / Retry | Reloads saved policy after uncertainty or a failed initial read. Check saved settings keeps edits and does not send another save. |

## Documents a DingDong can read

DingDong file tools can read and search text files, plus text extracted from PDF (`.pdf`), Word (`.docx`), HWP 5.x (`.hwp`), HWPX (`.hwpx`), PowerPoint (`.pptx`) and Excel (`.xlsx`).[^hwp-format]

These file tools extract text. Page layout, images, embedded files and OCR are outside their scope. Password-protected documents and distribution-protected HWP files are unsupported. Results can be partial when a document contains unsupported elements.

## Conditions and results

New Gear defaults to Sandboxed, workspace writes on, Git local changes and fetch on, Git push and discard off, host-language flags off, approval timeout on at 60 seconds, and containers on for Dart and Go.

To disable containers, expand Advanced settings in Sandboxed mode, turn off the container switch, and save. Workspace writes are required to export container changes into KnowledgeBox.

Android supports file tools and available shell commands; iOS supports file tools without shell/container execution. Mobile container controls configure eligible desktops. A saved policy does not create a workspace, grant device access, install host languages or start Docker.

After a failed/uncertain save, reopen the desktop policy or use mobile Check saved settings before repeating it. Shell approval decisions are separate from these Gear settings.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Connect a KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

[Set KnowledgeBox device priority](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md) · [Configure host and container runtimes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-runtimes.md) · [Shell approval](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/shell-approval.md)

Reviewed: 2026-10-23. UI labels use the English app language.

[^hwp-format]: 본 제품은 한컴의 HWP 문서 파일(.hwp) 공개 문서를 참고하여 개발하였습니다. [Format reference](https://www.hancom.com/support/downloadCenter/hwpOwpml)
