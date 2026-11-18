# Add and maintain knowledge web links

Add HTTPS references to a DingDong and maintain their descriptions across devices.

## Start here

**Desktop:** Top navigation → Management → Pure → select your DingDong → KnowledgeBox → source selector → Links.

**Mobile:** Third bottom tab Shortcuts → DingDong → select your Pure → Knowledge → Links.

## Desktop steps

1. Select Links in the KnowledgeBox source selector, then Add link.
2. Enter a valid HTTPS URL and an optional Description. Creation has no Name or Summary field; the saved name uses the URL host.
3. Press Add, or Enter in the URL field. The dialog closes and the request is sent. Check the collection for the resulting card.
4. On the saved card, edit Description/Summary and press Save. Open link launches an external application.
5. To remove a record, use its delete action and confirm. Cancel keeps it.

## Mobile steps

1. Open Knowledge → Links → Add web link.
2. Enter the HTTPS URL, optional Name and Description. Blank Name uses the URL host.
3. Press Add or keyboard Done in Description. Success opens the new link's details.
4. Edit Description/Summary and Save, or use Open to launch an external application. Later, tap a link row to reopen these controls.
5. Delete link asks for confirmation. Back with a changed creation or metadata draft asks whether to discard it or keep editing.

## Completion, limits and recovery

The URL limit is 2,048 characters; include a host and omit embedded credentials. Invalid ports are rejected. Description allows 500 characters and Summary 4,000. A mobile custom name must pass the portable-name rules, including 255 UTF-8 bytes; multibyte names can reach this limit before the character counter.

Saved Name and URL are read-only in these views. Add a separate record for a different address. Links are separate from device-local workspace files; saving one does not download the webpage into the folder or grant Browser permission. Removing it deletes only the record.

Use Refresh on desktop or pull-to-refresh on the mobile list; use Retry for a failed mobile detail read. Check whether a prior mutation already appears before repeating it: refreshing can fail after a successful write. External opening failures leave the record available.

Also find this under: web knowledge, add URL, persistent links, source link.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/knowledgebox/links.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/knowledgebox/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
