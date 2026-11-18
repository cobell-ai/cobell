# Install the supplied desktop CLI companion

Connect the distributed terminal companion to an existing desktop app installation.

## Start here

**Desktop:** Use the CLI package’s install.ps1 on Windows, or install.sh on macOS/Linux, with the existing desktop executable path.

**Mobile:** The companion is installed on desktop; a mobile app can approve its login code.

## Desktop steps

1. Install the matching Cobell Desktop distribution first.
2. Open a terminal in the supplied CLI distribution directory.
3. On Windows run install.ps1 with -GuiPath pointing to the desktop executable. On macOS/Linux run install.sh with the absolute app executable path.
4. Open a new terminal; on Unix ensure the installed launcher directory is on PATH.
5. Run cobell version and cobell help, then cobell login if needed.

## Mobile steps

1. Complete installation on the desktop machine.
2. When cobell login displays a code, open Profile → Approve sign-in with a verification code on the signed-in phone.
3. Check the requested desktop device and approve.

## CLI steps

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

## Completion, limits and recovery

The CLI package does not replace or include the installed GUI by itself. Use matching app/companion versions. Windows installation updates the user environment and PATH, so use a new terminal. Headless Linux additionally needs the virtual-display and keyring setup. This documentation repository does not distribute app binaries.

Also find this under: install CLI, PATH, install.ps1, install.sh, companion executable.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/install.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

[Prepare the Linux server environment](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-setup.md) · [Sign in using another signed-in device](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/verification-code.md)

Reviewed: 2026-10-03. UI labels use the English app language.
