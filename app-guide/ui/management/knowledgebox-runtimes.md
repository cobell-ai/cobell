# Configure host and container runtimes: screen reference

Keep host language commands separate from the Gear's desktop container policy.

## Open this screen

**Desktop:** Management → Gear → select the Gear → KnowledgeBox Use settings → Expert mode on → Sandboxed.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → KnowledgeBox Use settings → Expert mode on → Sandboxed.

## Controls

| Control or area | Location and behavior |
|---|---|
| Runtime commands / Shell language runtimes | Host switches for Python, JavaScript, C#, Dart, Go and Rust. All default off; editable only while workspace writes are allowed. Turning writes off clears them. |
| Host-runtime notice | Host language code, invoked scripts/toolchains/package managers and build steps can access or modify files outside the workspace. These switches do not run code inside Docker. |
| Enable container runtime / Enable run_container on eligible desktops | Separate container permission. Defaults on, with Dart and Go selected. Turning it off keeps its runtime/image choices in the policy draft. |
| Container Python / JavaScript / C# / Dart / Go / Rust | Independent from host-language switches. Editable while container permission is on. If enabling with no selected runtime, Dart/Go are selected. Trying to remove the last enabled runtime is rejected with a notice. |
| Desktop image fields | Six direct fields for Python, JavaScript, C#, Dart, Go and Rust; editable while container permission is on. |
| Mobile Container image overrides | Expands the six image fields. They can be prepared while container permission is off, provided the policy form is otherwise editable. |
| Image text | Sets each runtime's image reference. Blank references are normalized to defaults rather than disabling a runtime. To reset explicitly, enter its default image below. Saving text does not pull/build an image or verify Docker readiness. |
| Expert mode off | Resets host flags off and container policy to defaults: enabled Dart/Go with all default images. To keep containers off or retain custom choices, leave Expert mode on. |
| Save / Cancel or Back | Uses the containing Gear policy's save/discard flow. Mobile save uncertainty offers Check saved settings without discarding edits. |

## Default container images

| Runtime | Image |
|---|---|
| Python | `python:3-slim` |
| JavaScript | `node:lts-slim` |
| C# | `mcr.microsoft.com/dotnet/sdk:10.0` |
| Dart | `dart:stable` |
| Go | `golang:1-bookworm` |
| Rust | `rust:1-slim` |

## Conditions and results

Container execution is supported on Windows/macOS/Linux desktops with Docker available and the target DingDong's local KnowledgeBox folder. Mobile can edit this Gear policy but does not execute containers. A host-language permission likewise does not install or prove availability of that executable.

Container changes do not automatically replace KnowledgeBox source files. Exporting changes requires workspace write permission. Dependency preparation can use internet access.

Workspace writes off prevents exporting container changes into KnowledgeBox, while container work can remain enabled. Host-language flags, container languages and workspace write permission are different controls. The Unrestricted mode hides these Sandboxed sections without erasing their values.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-runtimes.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Device priority](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md)

Reviewed: 2026-10-23. UI labels use the English app language.
