# Resize and close the desktop window

Control the desktop window without confusing window closure with account logout.

## Start here

**Desktop:** Use the title bar, window edges and app-close confirmation.

**Mobile:** Use system app switching and Back; there is no desktop-style title bar.

## Desktop steps

1. Drag an empty title-bar area to move the window. Double-click it or use maximize/restore where offered. Sign-in/sign-up omit maximizing. Resize using the operating system's window frame.
2. Drag the right chat list's left boundary left to widen it or right to narrow it. Where the left navigation panel is visible, drag its right boundary right to widen it.
3. Drag panel boundaries to resize them within the available window space. Panel widths update and save locally without a final Save.
4. Save unfinished edits and check the result before closing. Close Cobell is an app-exit confirmation; it does not run every editor's Save/Discard check.
5. With icon-style controls, use Close, or Alt+F4 on Windows/Linux. If Close Cobell appears, Close starts shutdown; Cancel or Esc keeps the window. Outside clicks do not dismiss it. The closing display has no Cancel action.

Mac-style controls have different behavior: yellow minimizes and green maximizes/restores when offered. Red minimizes on Windows/Linux. On macOS, red requests native closure without the Mac-style path showing Close Cobell; last-window closure may terminate the app. macOS system Quit requests shutdown without that confirmation.

## Mobile steps

1. Use the system app switcher to leave Cobell.
2. Use the in-app Back button to leave a screen.
3. Resolve any unsaved-change confirmation before leaving an editor.

## Completion, limits and recovery

Closing does not log out. With a connected CLI companion, closing can hide the GUI while keeping the terminal session available. Use the CLI's GUI-opening action to show it again. The Mac-style red button on Windows/Linux only minimizes.

Esc follows the active view's own action, such as closing a popup, returning from settings or clearing selection. It does not universally quit the app or undo an already-sent request. Resolve an editor's own save/discard prompt when offered, and save before global app exit rather than assuming every editor will prompt.

Also find this under: window size, minimize, close app, resize panel.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/window.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/README.md)

[Terminal companion](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/cli/start.md) · [Main navigation](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/main-navigation.md) · [Text size](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/text-size.md)

Reviewed: 2026-10-24. UI labels use the English app language.
