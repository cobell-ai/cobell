# Configure KnowledgeBox Use permissions

Set a Gear's KnowledgeBox policy before asking a DingDong to change files or run code.

## Documents a DingDong can read

DingDong file tools can read and search text files, plus text extracted from PDF (`.pdf`), Word (`.docx`), HWP 5.x (`.hwp`), HWPX (`.hwpx`), PowerPoint (`.pptx`) and Excel (`.xlsx`).[^hwp-format]

These file tools extract text. Page layout, images, embedded files and OCR are outside their scope. Password-protected documents and distribution-protected HWP files are unsupported. Results can be partial when a document contains unsupported elements.

## Start here

**Desktop:** Management → Gear → select an editable Gear → KnowledgeBox Use settings icon.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → KnowledgeBox Use settings. Device priority uses its own Connections section.

## Desktop steps

1. Open the Gear's KnowledgeBox Use settings and review its selected devices. Use the device-priority guide for selection/order; this does not move files between devices.
2. Set Continue after approval timeout and a valid 1–86,400-second value. Default is enabled at 60 seconds. Expiry skips the unanswered command; it does not approve it. Off keeps waiting.
3. In Sandboxed mode, set Allow writes. Turning writes off also clears Git writes and host-language flags, while container permission remains separate.
4. Turn Expert mode on to change execution mode, Git writes, host runtimes or containers. Unrestricted allows direct execution outside the sandbox policy and hides the other advanced sections.
5. Review the runtime guide before enabling host languages or changing container settings. Containers default to enabled Dart/Go even when Expert controls are closed.
6. Press Save. It submits the update and closes this desktop dialog; reopen and check saved values if the request failed or its result is uncertain. Cancel/close before Save discard the dialog's draft.

## Mobile steps

1. Set targets separately in Connections → Priority devices → reorder icon. Save that selection in the device-priority screen.
2. Open KnowledgeBox Use settings for the Gear's file/shell policy. Set approval timeout and Allow workspace writes; turn Expert mode on for advanced controls.
3. While Sandboxed, adjust Git writes, host languages and container policy as needed. Mobile does not execute containers; those settings apply to eligible desktop targets.
4. Save the changed policy. Success leaves the screen. Back with a dirty draft offers keep editing/discard; sending blocks conflicting actions.
5. If saving is uncertain, use Check saved settings to reload the saved policy while keeping edits, then compare before saving again. Retry handles a failed initial read.

## Completion, limits and recovery

Defaults are Sandboxed, writes on, Git/host-language flags off, approval timeout on at 60 seconds, and container permission on for Dart/Go. Turning Expert mode off restores the advanced defaults, including container permission on. It does not change the current write/timeout choices. To retain containers off, keep Expert mode on and save that explicit choice.

Switching to Unrestricted hides advanced Sandboxed controls without erasing their values. Invalid timeout text does not replace the last valid draft value; review the field before saving. An empty target selection can be saved for later configuration, but execution still requires an available permitted target and the DingDong's workspace.

Android supports file tools and available shell commands; iOS supports file tools only. Policy saving does not install runtimes, grant device access, create a knowledge folder or prove execution readiness. Host language code can access files beyond the workspace. Catalog configuration demos do not change actual Gear.

Also find this under: file writes, shell sandbox, Git permission, containers, run_shell.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/knowledgebox-permissions.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Connect a KnowledgeBox workspace](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/workspace.md) · [Register and manage devices](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md)

[Set KnowledgeBox device priority](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md) · [Configure host and container runtimes](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-runtimes.md) · [Shell approval](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/shell-approval.md)

Reviewed: 2026-10-23. UI labels use the English app language.

[^hwp-format]: 본 제품은 한컴의 HWP 문서 파일(.hwp) 공개 문서를 참고하여 개발하였습니다. [Format reference](https://www.hancom.com/support/downloadCenter/hwpOwpml)
