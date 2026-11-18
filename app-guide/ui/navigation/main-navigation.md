# Navigate the main app: screen reference

Find the main destinations and recognize the different desktop and mobile layouts.

## Open this screen

**Desktop:** After personal sign-in, use the main window’s top navigation and chat list.

**Mobile:** After personal sign-in, use the five bottom tabs.

## Controls

| Control or area | Location and behavior |
|---|---|
| Desktop Start | Upper-left Cobell logo and Start text; opens the Cobelly landing conversation. |
| Desktop Management / Flow / Routine | Top navigation; opens configuration, orchestration or automation rules. Hover highlights the button; selected styling marks the current destination. |
| Desktop profile avatar/name | Near upper-right; opens Profile. |
| Desktop Apps grid icon | Opens registered and accessible shared apps; distinct from the Multi Chat layout control. |
| Desktop grid / shield / notification icons | Upper-right: Multi Chat, security/execution history and Notifications. |
| Desktop chat panel | Lists rooms and friends using All, DingDong and Friend tabs. |
| Mobile bottom tabs | Left to right: Home (house), Chat (chat bubble), Shortcuts (mosaic icon), Flow (graph), More (three-line menu); labels are hidden. |
| Switch / reselect mobile tab | Switching tabs restores that tab's last navigation location when available. Selecting the current tab opens its starting location. This is navigation behavior, not an editor-save confirmation. |
| More tab badge | The same pending-shell-approval count or unavailable exclamation mark used by the Security row. |
| Status above mobile tabs | Opens Service status when the warning is current and interaction is allowed. It does not itself retry a connection. |
| Mobile More profile card | Opens Profile; the rows below include Apps, service status, Booster when supported, Screen sharing, Security and App information. |

## Conditions and results

Desktop chat panels can be resized by dragging their vertical separators. An unsaved editor may ask you to save or discard before changing destinations. A service-status or required-update notice can replace the desktop top-bar Cobelly input; see [service status](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/service-status.md). Agent sign-in opens a restricted device-oriented interface rather than the normal personal app.

## Mobile More entries

Open the fifth bottom tab, the three-line More icon. Scroll vertically to reach its lower rows.

| Entry | Behavior |
|---|---|
| Profile card | Name/avatar/email card opens Profile. |
| OS notifications | Switch and permission/recovery controls for this device. See [OS notifications](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/os-notifications.md). Hidden for agent login and preview. |
| Apps | Opens registered and accessible [shared apps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/register.md). |
| Service status | Opens [service connectivity/status](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/service-status.md). |
| Cobell Mobile Booster | Android only; opens [pairing and connection setup](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/android-booster.md). |
| Screen sharing | Opens [mobile screen sharing](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/screen-sharing.md). |
| Security | Opens [shell approvals](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/shell-approval.md) and [local execution history](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/execution-history.md). A number on the shield counts pending approvals; an exclamation mark means approval state is unavailable. Active timed access alone does not add to that count. |
| App information | Opens the app/version screen; see [updates](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/updates.md). |

Market and Delivery rows are disabled by the current build's product configuration. The More entry points do not themselves start screen sharing, approve a shell request or pair Booster; review those destination controls.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/navigation/main-navigation.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/navigation/README.md)

[Apps and registration](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/app-share/register.md)

Reviewed: 2026-10-24 (desktop navigation/status entry; mobile shell navigation, More entries and badge delegates). UI labels use the English app language.
