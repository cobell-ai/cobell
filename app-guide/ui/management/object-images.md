# Manage Memory and Toolbox images: screen reference

Generate, review, apply or remove an owned private Memory/Toolbox picture.

## Open this screen

**Desktop:** Management → Memory or Toolbox → private item → image, or its menu → Generate image/Generate new image. Private collection cards also offer image actions outside selection mode.

**Mobile:** Shortcuts → DingDong → Memory or Toolbox → private item → Overview → Manage image.

## Desktop controls

| Control or area | Location and behavior |
|---|---|
| Image / menu entry | Idle opens options. A busy job, candidate or error reopens its current view. Labels include View generation status, Review generated image and Review generation failure. |
| Select art style | Offers Anime, Pixel Art, Realistic 3D, Cartoon, Watercolor and Line Art. Select one to enable Next. |
| Skip (none) / Next | Both go to Additional options; Skip clears the style choice. Style is optional on desktop. |
| Previous / Cancel | Previous returns from options to style while keeping the open draft. Cancel on the style step dismisses without generating. |
| Current profile preview | Shared UI label for the object's current picture. It is preview-only and is not automatically selected as a reference. |
| Reference image / Change reference image / clear icon | Picks a local file, replaces it or removes it from the generation draft. Picker cancellation retains the prior selection. Clearing a reference does not remove the applied picture. |
| Image generation prompt | Optional text, at most 80 characters. Reference and prompt can both be left empty. |
| Generate | Starts reference upload when needed, then generation. Produces a candidate; it does not apply it. |
| Candidate → Generate again / Apply | Generate again repeats the last style/reference/prompt without reopening options. Apply waits for acceptance, updates the object's picture and closes after success. |
| Error → Try again | Repeats generation with the last inputs, retries acceptance if a candidate remains, or retries a failed image removal. It does not always start a new generation. |
| Close / dialog dismissal | Close is shown for progress/error/accepted states; the candidate view has Generate again/Apply and can be dismissed outside the dialog. Dismissal does not cancel a sent upload/generate/apply/remove request. Reopen the same object's action in the current signed-in session to inspect it. |
| Menu → Delete avatar image | Shown when an applied image exists. Cancel/Delete confirms removal of the picture. A failed removal can be reopened and retried through the generation-failure view. |

## Mobile controls

| Control or area | Location and behavior |
|---|---|
| Current image | Displays the applied picture, separate from the generated candidate. |
| Choose a reference image (optional) / Remove reference image | Opens the photo picker or clears the selected reference from the draft. A canceled/failed pick retains the previous reference. Permission/read/type/size failures are shown near this control. |
| Select art style | Same six styles; defaults to Cartoon. This management form has no Skip/automatic-style choice. |
| Image generation prompt / Generate | Optional prompt, at most 80 characters. Generate uses the current style/reference/prompt, including when replacing an existing candidate. Inputs are blocked while busy. |
| Generated image → Use this image | Accepts the candidate. Success resets the input draft and returns to the item detail. Failure leaves the image screen for review. |
| Memory generation → Cancel | Stops the current Memory generation flow and keeps the applied image. This control is not offered for Toolbox generation. |
| Memory error → Retry | When offered, repeats the failed generation's captured inputs, acceptance or removal. Acceptance retry uses the retained candidate; removal retry repeats the previously confirmed removal. |
| Toolbox error | Has no dedicated Memory-style Retry button. Generate uses current inputs; a retained candidate can be accepted again with Use this image. Remove image can be requested again through confirmation. |
| Remove image | Offered with an applied image. Opens Cancel/Remove image confirmation, then clears that picture. It leaves the object and its content/settings intact. |
| Back | A changed prompt/style/reference asks to keep editing or discard. During Memory generation, leaving is allowed and generation continues; discarding the input draft does not cancel it. Toolbox generation, applying, removing and reference picking block departure. |

## Reference limits

All listed reference paths require a nonempty image of at most 10 MiB (10,485,760 bytes).

| Path | Accepted reference formats |
|---|---|
| Desktop Memory / private Toolbox | JPEG, PNG, WebP, GIF; local file must remain available for a retry. |
| Mobile Memory | JPEG, PNG, WebP, GIF. |
| Mobile private Toolbox | JPEG, PNG, WebP. |

## Conditions and results

These actions require an eligible normal signed-in owner. Preview/agent-login/read-only entries do not provide private mutations. Gear itself has no image generation/Manage image action in these screens; its displayed attachment pictures belong to Memories/Toolboxes.

Applying changes this item's picture. It does not change the user profile or each equipped DingDong's image. Generation and acceptance are separate; loading a preview alone does not confirm acceptance. After an uncertain apply/remove result, refresh the item's saved data before repeating the operation.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/management/object-images.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/management/README.md)

[Flow image](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/image.md) · [DingDong profile and image](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/profile-and-image.md)

Reviewed: 2026-10-23. UI labels use the English app language.
