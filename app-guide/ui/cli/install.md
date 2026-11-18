# Install the supplied desktop CLI companion: screen reference

Connect the distributed terminal companion to an existing desktop app installation.

## Open this screen

**Desktop:** Use the CLI package’s install.ps1 on Windows, or install.sh on macOS/Linux, with the existing desktop executable path.

**Mobile:** The companion is installed on desktop; a mobile app can approve its login code.

## Controls

| Control or area | Location and behavior |
|---|---|
| Windows -GuiPath | Absolute installed Cobell.exe path when different from the installer’s default. |
| Windows -Binary | Selects the supplied companion executable when needed. |
| Windows -Destination | Optional user installation directory. |
| Unix install.sh app-path | Records the existing executable/AppImage path in the launcher. |
| PATH | Makes cobell available in a newly opened terminal. |
| cobell version / help | Checks the installed companion. |
| cobell login | Starts the supported device-login flow. |

## CLI

Windows PowerShell, from the supplied package:

```powershell
.\install.ps1 -GuiPath "C:\Program Files\Cobell\Cobell.exe"
```

macOS/Linux, with the actual installed app executable:

```sh
sh install.sh /absolute/path/to/Cobell-executable
export PATH="$HOME/.local/bin:$PATH"
```

Use your actual app path; do not type an example path if the app is installed elsewhere.

## Conditions and results

The CLI package does not replace or include the installed GUI by itself. Use matching app/companion versions. Windows installation updates the user environment and PATH, so use a new terminal. Headless Linux additionally needs the virtual-display and keyring setup. This documentation repository does not distribute app binaries.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/install.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

[Prepare the Linux server environment](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-setup.md) · [Sign in using another signed-in device](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md)

Reviewed: 2026-10-03. UI labels use the English app language.
