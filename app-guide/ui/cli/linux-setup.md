# Prepare the Linux server environment: screen reference

Install the virtual display dependencies and prepare the existing Linux keyring for the supplied companion.

## Open this screen

**Desktop:** Use the matching Linux app and CLI distribution on Ubuntu 24.04 or Debian 12, from the OS account that will run Cobell.

**Mobile:** Mobile is used for login approval after the Linux environment is ready.

## Controls

| Control or area | Location and behavior |
|---|---|
| install.sh app-path | Installs the distributed CLI launcher with an absolute existing app path. |
| PATH | Makes the installed companion available to the terminal. |
| Keyring password file | Allows the virtual session to unlock the user’s login keyring. |
| COBELL_KEYRING_PASSWORD_FILE | Optional protected password-file path for direct execution. |
| cobell login | Starts the virtual runtime and code approval when no display exists. |
| Exit code 78 | Indicates failed keyring preparation instead of a usable signed-in session. |

## CLI

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

## Conditions and results

The CLI alone does not include the Linux app. Raw desktop bundles also need their GTK, libsecret, WebKitGTK and native dependencies. Keep the same OS user, HOME and XDG_DATA_HOME to preserve the existing installation/keyring identity. Never reset an existing keyring just to repair access. The virtual desktop does not need VNC or a public web login.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/linux-setup.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/README.md)

Reviewed: 2026-10-03. UI labels use the English app language.
