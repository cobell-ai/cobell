# Resize and close the desktop window: screen reference

Control the desktop window without confusing window closure with account logout.

## Open this screen

**Desktop:** Use the title bar, window edges and app-close confirmation.

**Mobile:** Use system app switching and Back; there is no desktop-style title bar.

## Controls

| Control or area | Location and behavior |
|---|---|
| Empty title-bar area | Drag to move the window. Double-click toggles maximize/restore where maximizing is offered. |
| Icon-style minimize / maximize / close | Minimize keeps the app running; maximize toggles restore. Close uses the app-close flow. Sign-in/sign-up omit maximizing and ignore title-bar double-click maximize. |
| Mac-style yellow / green buttons | Yellow minimizes; green toggles maximize/restore when offered. |
| Mac-style red button | On Windows/Linux, minimizes. On macOS, requests native window closure; it does not show Close Cobell when using that Mac-style close path. Last-window closure may terminate the app. |
| Main-window edges / OS resizing | Drag the operating system's window frame to resize within the available limits. |
| Right chat-panel left boundary | Drag horizontally; moving left widens the chat panel within the available space. |
| Left navigation-panel right boundary | Where visible, drag horizontally; moving right widens the panel within the available space. |
| Close Cobell → Cancel / Esc | Keeps the window open. Clicking outside does not dismiss this confirmation. |
| Close Cobell → Close | Starts shutdown. The closing display has no Cancel action. |
| Alt+F4 | Windows/Linux close request handled by Cobell. Uses the same companion/confirmation flow; it is not a logout action. |
| macOS system Quit | Requests shutdown without the Close Cobell confirmation. An active CLI companion can still retain the runtime. |
| Esc in an active view | Uses that view's escape action: for example dismissing a popup, returning from settings or clearing selection. There is no universal Esc-to-quit or Esc-to-undo rule. |

## Conditions and results

Window closure does not log out. Save needed edits and check their result before closing. The global Close Cobell confirmation does not ask every editor to Save/Discard; do not rely on a retained draft or automatic save to protect an unfinished edit.

With a connected CLI companion, closing can hide the GUI while keeping the terminal session available. Use the CLI's GUI-opening action to show it again. The Mac-style red button on Windows/Linux only minimizes.

Panel widths update and save locally without a final Save button. Available window space limits resizing. Minimizing and closing are separate actions; neither logs out.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/window.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/README.md)

[Terminal companion](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/cli/start.md) · [Main navigation](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/main-navigation.md) · [Text size](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/text-size.md)

Reviewed: 2026-10-24. UI labels use the English app language.
