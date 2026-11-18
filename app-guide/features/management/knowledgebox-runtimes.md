# Configure host and container runtimes

Choose which language commands and desktop container runtimes this Gear permits.

## Start here

**Desktop:** Management → Gear → select the Gear → KnowledgeBox Use settings → Expert mode on → Sandboxed.

**Mobile:** Shortcuts → DingDong → Gear → select the Gear → Connections → KnowledgeBox Use settings → Expert mode on → Sandboxed.

## Desktop steps

1. Review the target device and workspace. Host languages must be installed there; containers require Docker on a supported desktop.
2. For host commands, allow workspace writes and choose Python, JavaScript, C#, Dart, Go or Rust. They execute on the host and can access files outside the workspace through code/toolchains; they are not container settings.
3. For containers, review the separate Enable container runtime switch. It defaults on with Dart/Go; host switches default off.
4. Select container languages independently. With container permission on, at least one must remain selected. Enabling an empty selection restores Dart/Go.
5. Enter image overrides in the six fields if needed. See the screen reference for exact defaults. Blank images normalize to defaults; an image value alone does not enable its language or verify the image can run.
6. Save the Gear policy. To retain containers off or custom choices, keep Expert mode on: turning it off restores enabled Dart/Go and default images.

## Mobile steps

1. Open the policy's Expert + Sandboxed controls. Set host-language permissions only for a target that can execute them.
2. Use Enable run_container on eligible desktops and select its languages. This edits desktop-target policy; the phone does not become a container executor.
3. Expand Container image overrides to edit the six images. Mobile allows preparing them even while the container switch is off; the runtime switches require it on.
4. Save, then verify the target desktop's Docker/workspace readiness. If the save is uncertain, use Check saved settings to read the saved policy while keeping edits.

## Completion, limits and recovery

Turning workspace writes off clears host languages and Git writes, but does not disable containers. Container changes do not automatically replace KnowledgeBox source files; exporting changes requires workspace write permission. Dependency preparation can use internet access.

Saving does not install host languages, start Docker or verify image readiness. Expert mode off restores enabled Dart/Go containers with default images and disables host-language flags. Unrestricted hides the Sandboxed controls while retaining their values.

Also find this under: runtime permission, Docker, container images, host Python, Dart container, Go container.

## Related guides

[Screen controls and defaults](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/knowledgebox-runtimes.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[KnowledgeBox permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-permissions.md) · [Device priority](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/knowledgebox-devices.md)

Reviewed: 2026-10-23. UI labels use the English app language.
