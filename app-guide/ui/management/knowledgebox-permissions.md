# Configure KnowledgeBox Use permissions: screen reference

Set the Gear's KnowledgeBox file/shell policy and review which advanced settings are reset.

## Open this screen

**Desktop:** Management → Gear → select an editable Gear → KnowledgeBox Use attachment's settings icon.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → KnowledgeBox Use settings. Device priority is a separate Connections section.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Tool execution/target devices | Selects registered devices and orders the selected entries. See the device-priority guide for checkbox/drag behavior and mobile's separate screen. |
| Continue after approval timeout | Toggles whether an unanswered approval expires. When on, the timed-out command is not executed and DingDong can continue within existing permissions; off keeps waiting. |
| Approval timeout (seconds) | Accepts digits from 1 to 86,400; default 60. Disabled while timeout is off. Valid edits update the draft; an invalid number is shown as an error without replacing the previous valid policy value. |
| Expert mode | Shows advanced execution, Git, host-runtime and container controls. Turning it off resets the execution mode to Sandboxed, Git/host-runtime flags off and container settings to defaults, including enabled Dart/Go containers. It keeps the write and approval-timeout choices. |
| Execution mode | Expert-only choice: Sandboxed or Unrestricted. Sandboxed uses structured allowed commands. Unrestricted permits direct executable/argument execution without the sandbox policy; write/Git/runtime/container controls are hidden in that mode. Changing mode alone does not erase their saved values. |
| Allow writes / Allow workspace writes | Shown in Sandboxed mode. Controls KnowledgeBox file changes. Turning it off clears Git writes and all six host-runtime flags; container enablement is separate. |
| Allow Git write operations | Expert + Sandboxed setting, editable only with writes allowed. Permits staging, commits, branch changes, reset, clean, stash and push under the applicable shell policy. |
| Host runtime switches | Expert + Sandboxed controls for Python, JavaScript, C#, Dart, Go and Rust. They require writes; see Runtime settings for host/container differences. |
| Container runtime / image fields | Expert + Sandboxed controls for container permission, languages and images. Default permission is enabled with Dart and Go; turning Expert mode off restores those defaults rather than disabling containers. |
| Desktop Save / Cancel / close | Save validates, submits the Gear update and closes the dialog. Cancel/close discard its unsaved draft. Closing after Save is not proof that the network write was acknowledged. |
| Mobile Save / Back | Save sends a changed policy and leaves after success. Back with a dirty draft asks to keep editing or discard; saving blocks conflicting navigation. |
| Mobile Check saved settings / Retry | Reloads saved policy after uncertainty or a failed initial read. Check saved settings keeps edits and does not send another save. |

## Documents a DingDong can read

DingDong file tools can read and search text files, plus text extracted from PDF (`.pdf`), Word (`.docx`), HWP 5.x (`.hwp`), HWPX (`.hwpx`), PowerPoint (`.pptx`) and Excel (`.xlsx`).[^hwp-format]

These file tools extract text. Page layout, images, embedded files and OCR are outside their scope. Password-protected documents and distribution-protected HWP files are unsupported. Results can be partial when a document contains unsupported elements.

## Conditions and results

Current defaults are Sandboxed, workspace writes on, Git writes off, host-language flags off, approval timeout on at 60 seconds, and container permission on for Dart/Go. Defaults describe the policy, not a guarantee that Docker or a language executable is installed.

To keep containers disabled, turn Expert mode on, remain in Sandboxed mode and turn off the container switch; turning Expert mode off restores enabled Dart/Go defaults. Turning off workspace writes does not itself disable container execution, but prevents exporting container changes into KnowledgeBox.

Android supports file tools and available shell commands; iOS supports file tools without shell/container execution. Mobile container controls configure eligible desktops. A saved policy does not create a workspace, grant device access, install host languages or start Docker. Catalog configuration demos do not save actual Gear.

After a failed/uncertain save, reopen the desktop policy or use mobile Check saved settings before repeating it. Shell approval decisions are separate from these Gear settings.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Connect a KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

[Set KnowledgeBox device priority](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md) · [Configure host and container runtimes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-runtimes.md) · [Shell approval](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/shell-approval.md)

Reviewed: 2026-10-23. UI labels use the English app language.

[^hwp-format]: 본 제품은 한컴의 HWP 문서 파일(.hwp) 공개 문서를 참고하여 개발하였습니다. [Format reference](https://www.hancom.com/support/downloadCenter/hwpOwpml)
