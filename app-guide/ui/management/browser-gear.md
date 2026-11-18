# Approve Browsers in Gear: screen reference

Choose isolated browsers a DingDong may control and optionally narrow their global policy.

## Open this screen

**Desktop:** Top navigation → Management → Gear → select the Gear → Sandbox Browser Use configuration → Approved browsers.

**Mobile:** Third bottom tab Shortcuts → DingDong → Gear → select the Gear → Connection → Sandbox Browser Use → browser selector/policy controls.

## Controls

| Control or area | Location and behavior |
|---|---|
| Enabled for this Gear | Mobile enables or disables Sandbox Browser Use for this Gear. |
| Approved browsers / Browsers available to this Gear | Check existing Browser objects; clear a checkbox to remove approval. Desktop shows Browser ID/owner device; mobile marks this versus another device. |
| Add / Create browser | Opens Browser creation while preserving the Gear draft. Add on desktop creates a Browser; existing Browsers use their checkboxes. Check the selection after returning, then save the Gear. |
| Refresh browsers | Mobile refreshes the available Browsers while retaining Gear changes. A failed refresh has its own message. |
| Use separate settings for this Gear | Enables a Gear-specific restriction. |
| Visit scope / blocked rules / permissions | Narrows the selected Browser’s global policy. |
| View browser defaults | Mobile opens the selected Browser detail when the Gear-specific policy is off. Return to continue the retained Gear draft. |
| Browser unavailable · remove this selection | Mobile retains a missing Browser reference until you remove it with the minus button. This removes approval, not a Browser object. |
| Save | Desktop starts the update and closes before confirmation. Mobile waits for the saved-value check, requires changes and is disabled during browser navigation/loading/saving. |
| Back / Check saved settings | Mobile Back checks a changed draft before leaving. After an uncertain save, Check saved settings reconciles the result. A failed initial read offers Retry. |

## Conditions and results

A Gear cannot grant access broader than Browser-global settings. Both policies must allow an operation. Browsers retain their own isolated cookies/login state; being approved does not mean the website is signed in. Android runs mobile browsers; iOS can configure eligible remote Browsers but cannot execute a local Browser.

Creating a Browser persists that Browser separately from the Gear draft. Leaving the Gear without saving does not delete the newly created Browser. Approval does not start a runtime or grant a device permission. Use Refresh browsers after an unavailable/stale mobile list and review the selected Browsers before saving.

Host/subdomain choices can appear when leaving an edited allowed-host field or saving. Resolve the choice before continuing. Gear policy and global policy must both permit the site and action, even if a mobile switch can be set in the draft.

Desktop Save starts the update and closes the built-in configuration dialog before the server result. Reopen the saved Gear after it settles; an optimistic display can return to the prior state on failure. Cancel or Close before Save discards the draft. Mobile Save waits for the saved-value check; a failed initial read offers Retry. After an uncertain mobile save, use Check saved settings, which reads without repeating the write and can retain differing edits. Review those before saving again or discarding the draft.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/browser-gear.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Create and edit an isolated Browser](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-create.md) · [Set Browser site access and permissions](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/devices-browsers/browser-policy.md)

Reviewed: 2026-10-23. UI labels use the English app language.
