# Approve Browsers in Gear

Choose isolated browsers a DingDong may control and optionally narrow their global policy.

## Start here

**Desktop:** Top navigation → Management → Gear → select the Gear → Sandbox Browser Use configuration → Approved browsers.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → Sandbox Browser Use → browser selector/policy controls.

## Desktop steps

1. Open the Gear’s Sandbox Browser Use configuration.
2. Check an existing Browser in Approved browsers. Add opens new Browser creation; after returning, check the Browser you intend to approve.
3. Enable Use separate settings for this Gear only if additional restrictions are needed.
4. Set the narrower visit and permission policy. Resolve any host/subdomain choice and save the Gear configuration.
5. Start/check the Browser on its owning device.

## Mobile steps

1. Open the Gear’s Sandbox Browser Use configuration.
2. Check existing Browsers or use Create browser, then review the selection after returning. Refresh browsers reloads available Browsers while keeping Gear changes.
3. Enable Use a policy for this Gear for additional restrictions. With it off, View browser defaults opens the selected Browser detail; return to resume the Gear draft.
4. Resolve any host/subdomain prompt. Remove an unavailable Browser reference with its minus button, or clear an ordinary checkbox to stop approving it.
5. Save. If leaving with changes, choose whether to keep editing or discard them. Check runtime availability on the owning device separately.

## Example: use an office-only work session from a shared chat

Assume the internal portal is reachable only from the owner's office PC, or its work account is signed in only within that PC's sandbox browser. The owner can ask DingDong from home after hours. While the owner is on leave or unavailable, an authorized colleague or manager can request the task in a shared chat.

1. Keep the office PC connected under the DingDong owner's account, with device tool access allowed. Agent sign-in can keep it available as an execution device.
2. Start the sandbox browser on that PC and sign in to the work site inside that isolated profile. It does not inherit the user's ordinary browser login.
3. Allow the required site and actions in Browser-global policy, including private-network access if needed. Approve this Browser in the Gear assigned to the DingDong in the work chat; review any narrower Gear policy and save.
4. Invite the DingDong into the team chat. In its room settings, give [Bell permission](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/behavior.md) only to the colleagues who should be able to request work.
5. The owner at home or an allowed colleague asks, for example, “Use the office PC's portal to change tomorrow's dispatch quantity from 120 to 150,” then rings the Bell. Execution occurs in the office PC's approved browser, with a result reported in chat.

Bell access does not transfer the device, browser profile or website credentials to the colleague's account. It authorizes invoking the owner's configured DingDong. The PC and Browser must be available and the site's session valid; site permissions, reauthentication and required approvals still apply. Confirm the changed value and review Browser activity when needed. A saved Gear selection alone does not prove the browser is running or signed in.

## Completion, limits and recovery

A Gear cannot grant access broader than Browser-global settings. Both policies must allow an operation. Browsers retain their own isolated cookies/login state; being approved does not mean the website is signed in. Android runs mobile browsers; iOS can configure eligible remote Browsers but cannot execute a local Browser.

Creating a Browser persists it separately. Discarding the Gear draft does not delete that Browser. Removing its Gear selection removes approval only. Desktop Save starts the update and closes the built-in configuration dialog before the server result. Reopen the saved Gear after it settles; an optimistic display can return to the prior state on failure. Cancel or Close before Save discards the draft. Mobile Save waits for the saved-value check; a failed initial read offers Retry. After an uncertain mobile save, use Check saved settings, which reads without repeating the write and can retain differing edits. Review those before saving again or discarding the draft.

Also find this under: Sandbox Browser Use, approved browser, per-Gear policy.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/browser-gear.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/README.md)

[Create and edit an isolated Browser](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md) · [Set Browser site access and permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md)

Reviewed: 2026-10-24 (office sandbox browser and shared-chat delegation example). UI labels use the English app language.
