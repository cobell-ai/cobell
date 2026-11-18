# Add and maintain knowledge web links: screen reference

Store a DingDong's cross-device web links separately from device-local workspace files.

## Open this screen

**Desktop:** Top navigation → Management → Pure → select your DingDong → KnowledgeBox → source selector → Links.

**Mobile:** Third bottom tab Shortcuts → DingDong → select your Pure → Knowledge → Links.

## Controls

| Control or area | Location and behavior |
|---|---|
| Add link / Add web link | Opens creation. Desktop asks for URL and optional Description. Mobile also offers an optional Name. Summary is edited after creation. |
| URL | Required HTTPS address, up to 2,048 characters. A host is required; embedded credentials and invalid ports are rejected. |
| Mobile optional Name | Blank uses the URL host. A supplied name must pass the portable-name rules, including the 255 UTF-8-byte limit. Desktop creation uses the host without a name field. |
| Description in creation | Optional, up to 500 characters. |
| Add | Submits creation; Enter in the desktop URL field and keyboard Done in the mobile Description field also submit. Desktop closes the form before sending; mobile opens the new link's details after success. |
| Desktop Cancel / close | Closes the creation form without creating a link. |
| Refresh / mobile pull-to-refresh | Reloads the link collection. Mobile loading/detail errors also offer Retry. |
| Desktop saved-link card / mobile link row | Desktop shows each link's controls inline. A mobile row opens the link detail screen. Name and URL are displayed, not editable in these saved-link views. |
| Description / Summary → Save | Updates the saved explanation, not the webpage. Limits are 500 and 4,000 characters. Save requires changes and is disabled during a conflicting operation. |
| Open link / Open | Requests the system's external application for the HTTPS address; an opening failure is reported in Cobell. |
| Delete link | Asks for confirmation, then removes the saved record. Cancel keeps it. |
| Mobile Back | Changed creation or metadata drafts prompt to keep editing or discard. Sending blocks conflicting navigation/actions. |

## Conditions and results

Links belong to the DingDong across devices and do not require a particular device's connected knowledge folder. Saving a link does not import the webpage as a local file or grant Browser permission.

Existing link Name and URL cannot be changed in these views. To use another address, add a separate record and remove the old one if appropriate. Deleting a record does not delete the webpage.

On failure, keep the draft where available and check the collection before repeating creation or deletion. A successful write can be followed by a failed refresh. A failed external opening does not remove the saved link.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/links.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
