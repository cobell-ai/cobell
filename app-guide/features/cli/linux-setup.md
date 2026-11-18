# Prepare the Linux server environment

Install the virtual display dependencies and prepare the existing Linux keyring for the supplied companion.

## Start here

**Desktop:** Use the matching Linux app and CLI distribution on Ubuntu 24.04 or Debian 12, from the OS account that will run Cobell.

**Mobile:** Mobile is used for login approval after the Linux environment is ready.

## Desktop steps

1. Install the virtual display/keyring packages shown below.
2. Prepare the matching Cobell Linux app; if FUSE is unavailable, extract the AppImage and use its AppRun executable.
3. From the supplied CLI directory run install.sh with the absolute app path.
4. Prepare a protected keyring password file using the existing login keyring’s password, or choose a password for a new keyring.
5. Run cobell login and complete code approval from a signed-in app.

## Mobile steps

1. Prepare Linux using the Desktop steps.
2. Open Profile → Approve sign-in with a verification code on the signed-in phone.
3. Review and approve the terminal’s login code.

## CLI steps

On the supported host:

```sh
sudo apt-get update
sudo apt-get install -y xvfb xauth dbus-daemon gnome-keyring openbox libglib2.0-bin libgl1-mesa-dri util-linux ca-certificates
sh install.sh /absolute/path/to/Cobell.AppImage
export PATH="$HOME/.local/bin:$PATH"
```

In Bash, prepare the password without placing it in a command argument:

```bash
install -d -m 700 "$HOME/.config/cobell"
umask 077
read -r -s -p "Login keyring password: " cobell_keyring_password
printf "\n"
printf "%s" "$cobell_keyring_password" > "$HOME/.config/cobell/keyring-password"
unset cobell_keyring_password
chmod 600 "$HOME/.config/cobell/keyring-password"
```

## Completion, limits and recovery

The CLI alone does not include the Linux app. Raw desktop bundles also need their GTK, libsecret, WebKitGTK and native dependencies. Keep the same OS user, HOME and XDG_DATA_HOME to preserve the existing installation/keyring identity. Never reset an existing keyring just to repair access. The virtual desktop does not need VNC or a public web login.

Also find this under: Linux prerequisites, install companion, keyring, AppImage, no display.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/linux-setup.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
