# Register and manage devices: screen reference

Review registered devices, login state and permission to execute tools or supply KnowledgeBox files.

## Open this screen

**Desktop:** Management → Device.

**Mobile:** Shortcuts → Device → select a device.

## Controls

| Control or area | Behavior |
|---|---|
| Device identity and status | Desktop shows a shortened ID with its full value on hover, OS/machine information and User login, Agent login or Offline. Mobile detail shows available platform/model/OS/account/version/registration information. |
| Mobile Device ID / copy | Select the ID text or use its copy button. Missing machine information does not by itself prove the device is offline. |
| Toolbox / Allow Toolbox | Permits Toolbox execution; locked on for normal-login devices, including remote ones. |
| KnowledgeBox / Allow Knowledge Box access | Permits KnowledgeBox file access; locked on for normal-login devices. |
| Share Info | Changes that device's outgoing information sharing. Other devices' incoming sharing is separate. |
| Desktop ⋮ menu | Offers permission/share toggles where editable, Rename, Agent Logout where eligible and Unregister. Clicking the Agent login status also opens Agent Logout. |
| Rename / Edit name | Enter a 1–40-character display label after trimming, then Change/Save; Cancel keeps the old name. Spaces are allowed; the app rejects invalid characters. |
| Agent Logout | Reviews current agent sessions before confirming. Mobile shows their count, loading, empty and failure states. Retry a failed read before confirming. |
| Unregister / Unregister device | Requires confirmation; removes the device registration and revokes its normal and agent sessions. Unregistering this device signs you out. |
| Refresh / Retry | Reloads the device list or failed settings. Mobile settings have a separate Retry when their read fails. |

## Conditions and recovery

There is no manual Add Device form. Your plan limits registrations. An enabled device permission does not select the device in Gear or supply OS/runtime capabilities: check all three before execution.

This personal-management screen differs from the local [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/desktop-agent-device.md) and [mobile agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/authentication/agent-device.md).

Agent Logout ends the reviewed agent sessions; running tasks may stop. It keeps the registration. If sending fails, retry from the same dialog or close and inspect the current state. Unregister also revokes normal sessions. Signing in again can register the device again.

If list or settings changes cannot be confirmed, reload with Refresh/Retry before relying on the displayed value. Preview data does not authorize real account changes.

## Subscription expiry and lower device limits

When a subscription ends or a lower plan takes effect, excess registrations disappear from the registered-device list and their normal/agent sessions end. Devices within the new limit remain registered. The removed entries are not paused registrations that return after a plan increase.

Sign in again to register a removed device within the available limit. A new subscription does not restore its previous sessions. Explain this before expiry; see [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/account/subscription.md).

## Related guides

[Task steps](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/device-management.md) · [Share device information](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/share-device-info.md) · [Agent sign-in tokens](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/agent-tokens.md)

Reviewed: 2026-11-12. UI labels use the English app language.
