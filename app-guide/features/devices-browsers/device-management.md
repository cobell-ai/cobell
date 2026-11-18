# Register and manage devices

Review registered devices, login state and permission to execute tools or supply KnowledgeBox files.

## Start here

**Desktop:** Management → Device.

**Mobile:** Shortcuts → Device → select a device.

## Desktop steps

1. Sign in to Cobell on the intended device; registration happens during sign-in.
2. Open Management → Device and identify the device by name, ID, OS and login state.
3. Change an editable permission or Share Info directly, or use the row's ⋮ menu.
4. Use Rename for a display-name change. For an agent device, open Agent Logout, wait for the session read and confirm the sessions being ended.
5. Use Unregister only when you intend to remove registration and revoke sessions; review the confirmation first.

## Mobile steps

1. Open Shortcuts → Device and select a device.
2. Check its status and available information; copy Device ID if needed to identify it elsewhere.
3. Use the access/share switches or Edit name. Read failures offer Retry; saving disables conflicting actions.
4. For Agent Logout, wait for the session count. Confirm to end those sessions; Cancel leaves them running. If no eligible sessions remain, close the dialog.
5. To remove a device, choose Unregister device and confirm. Removing the current phone also signs it out.

## Completion, limits and recovery

There is no manual Add Device form. Your plan limits registrations. An enabled device permission does not select the device in Gear or supply OS/runtime capabilities: check all three before execution.

This personal-management screen differs from the local [desktop agent screen](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/desktop-agent-device.md) and [mobile agent dashboard](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/authentication/agent-device.md).

Agent Logout ends the reviewed agent sessions; running tasks may stop. It keeps the registration. If sending fails, retry from the same dialog or close and inspect the current state. Unregister also revokes normal sessions. Signing in again can register the device again.

If list or settings changes cannot be confirmed, reload with Refresh/Retry before relying on the displayed value. Preview data does not authorize real account changes.

## Subscription expiry and lower device limits

When a subscription ends or a lower plan takes effect, registrations above the new device limit are removed. Their normal and agent sessions end; registrations within the limit remain. Removed registrations are not retained as paused devices for automatic recovery.

Subscribing again does not restore those registrations or sessions. Sign in again on an intended device to register within the available limit. Explain this before expiry; see [subscription expiry](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/subscription.md).

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/devices-browsers/device-management.md) · [Share device information](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/share-device-info.md) · [Agent sign-in tokens](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/account/agent-tokens.md)

Reviewed: 2026-11-12. UI labels use the English app language.
