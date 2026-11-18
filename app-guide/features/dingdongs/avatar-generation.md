# Generate or remove a DingDong profile image

Generate a candidate for your Pure DingDong, review it, then apply it to the bot identity.

## Open image management

**Desktop:** Management → Pure → card Menu, or open the bot → Menu → Generate profile image / Generate new profile image. The owned bot's public profile also has the generation action. Its label changes to View generation status, Review generated image or Review generation failure when a local job exists.

**Mobile:** Shortcuts → DingDong → your Pure → Overview → Manage image. Your bot's public profile also has Manage image.

These actions require the owner's normal signed-in account. Cobelly uses its supplied image and is outside this flow.

## Desktop: generate and review

1. Choose Anime, Pixel Art, Realistic 3D, Cartoon, Watercolor or Line Art, then Next. Skip (none) proceeds without a style. Next is disabled until a style is selected; Skip clears a prior style choice.
2. In Additional options (optional), choose a local Reference image if wanted. Change reference image replaces that selection; its remove icon clears the selected reference. Current profile is a preview of the existing avatar, not an automatically selected reference. Enter an optional Image generation prompt, up to 80 characters. Previous returns to style selection with the options retained.
3. Press Generate. The options window closes and the status window opens. A valid local reference is uploaded before generation. Cancel/dismiss before Generate abandons the options without starting a job.
4. Wait for a candidate. Closing the status window does not cancel generation. Reopen the same bot's generation action to check progress.
5. Review the candidate and choose Apply. A successful application updates the avatar and closes the window. Generate again uses the previous options; cancel and reopen generation to change them.

At candidate review, Cancel closes without applying the candidate and keeps the current avatar. To change generation options, cancel the candidate and open generation again.

On error, refresh the current profile before trying again. Use Try again when offered. Make the selected reference file available before retrying; reopen generation to change options when available.

## Mobile: generate and apply

1. Manage image shows Current image. Optionally choose a reference from the gallery, or Remove reference image to clear the draft selection. Picker cancellation keeps the previous choice; access/read/format errors are shown beside this control.
2. Select an art style. Cartoon is the default; the dropdown offers the same six styles as desktop. Enter an optional Image generation prompt of up to 80 characters and correct any length error shown by the form.
3. Tap Generate. Reference selection, style, prompt, generation/application/removal controls and Back are blocked while the Pure's request is busy. Progress messages are shown while generating. Pure has no separate Cancel-generation or error Retry button on this screen.
4. Review Generated image and tap Use this image. Success updates the avatar, clears the options draft and returns to the previous screen or management detail.
5. For a different candidate, adjust the options and press Generate again. This uses the currently displayed options. Generation failure leaves an error and re-enables Generate. Application failure retains the candidate: Use this image is the application retry.

Back with unsaved options asks Discard changes? Cancel keeps editing; Discard leaves without saving the options. Do not rely on an unfinished generation draft after restarting the app or changing accounts.

## References, context and uncertain results

- Both reference paths allow at most 10 MiB and reject an empty file. Desktop accepts local JPEG, PNG, WebP and GIF files. Mobile Pure accepts JPEG, PNG and WebP and checks their bytes/content type; the Memory image editor's GIF support is a different path.
- Select a supported reference image and follow any upload error shown by the form.
- Image generation can use the bot's name, Memories from the Gear selected in its personal chat, chosen style, optional prompt and an explicitly supplied reference. Reference selection supplies generation input; it does not directly install that file as the avatar.
- A failed candidate preview does not mean the image was applied. Refresh the current profile after an uncertain Apply before trying again.
- Finish reviewing and applying one image before generating another for the same DingDong, including from another device.
- A lost Apply/removal response can follow a committed server change. Refresh/reopen the bot's current profile before repeating an uncertain action. Generation may also be rejected by AI availability or quota; repeated Generate is a new generation request.

## Remove the applied image

**Desktop:** When an image exists, card/detail Menu → Delete profile image → confirm Delete. Cancel/dismiss makes no request. **Mobile:** Manage image → Remove image → confirm Remove image. The action appears when Current image exists.

Removal clears the applied image, saved reference and pending candidate while keeping the DingDong identity and device files. After an uncertain result, refresh the profile before repeating. There is no image-restore or Undo action.

Also find this under: DingDong avatar, profile image, reference image, 80-character prompt, candidate, Apply, Use this image, image generation retry.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/avatar-generation.md) · [Feature index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/README.md)

[Inspect a DingDong profile](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/profile-and-image.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/equip-gear.md) · [Rename or delete a Pure DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/maintain-pure.md)

Reviewed: 2026-10-23. UI labels use the English app language.
