# DingDong profile images: screen reference

## Open this screen

**Desktop:** Management → Pure → card/detail Menu → Generate profile image / Generate new profile image. The owned bot's public profile has the same generation flow.

**Mobile:** Shortcuts → DingDong → owned Pure → Overview → Manage image, or its public profile → Manage image.

Owner's normal account only; Cobelly's supplied image is outside this flow.

## Desktop controls

| Control/state | Behavior |
|---|---|
| Generation entry | Opens options when idle; View generation status / Review generated image / Review generation failure reopens existing local state. |
| Style tiles | Anime, Pixel Art, Realistic 3D, Cartoon, Watercolor, Line Art. Next requires a selection. |
| Skip (none) | Clears the style choice and proceeds to optional inputs. |
| Cancel / options dismissal | Before Generate, closes without starting a job; no draft-discard confirmation. |
| Previous | Returns from optional inputs to styles, keeping reference/prompt. |
| Current profile | Existing avatar preview only. |
| Reference image / Change reference image | Picks a local image; picker cancellation keeps the existing selection. Reference preview remove icon clears it. |
| Image generation prompt | Optional, 80-character input limit. |
| Generate | Closes options and starts reference upload/generation; opens status. |
| Progress / Close | Shows progress and recent messages. Close/dismiss keeps generation running. |
| Candidate Apply | Sends application; success updates avatar and closes. Progress Close can still dismiss while applying; it does not undo a sent request. |
| Candidate Generate again | Starts another generation with the previous options. Cancel and reopen generation to change options. |
| Candidate Cancel | Closes without applying the candidate and keeps the current avatar. |
| Error Try again | Retries the failed image action. Check the current profile before retrying an uncertain result. |
| Error Close | Keeps the error for reopening. |
| Change generation options | Cancel the candidate and reopen generation. Make the selected reference file available before retrying. |
| Menu → Delete profile image | Available with an applied image. Confirmation Cancel/Delete; removal is separate from deleting the DingDong. |

## Mobile controls

| Control/state | Behavior |
|---|---|
| Current image | Current applied avatar preview; fallback on missing/failed image. |
| Choose a reference image (optional) | Gallery picker. Cancellation keeps previous choice; permission/read/validation errors appear locally. |
| Reference preview / Remove reference image | Shows and clears the draft reference; does not remove an applied avatar. |
| Select art style | Six styles above; default Cartoon. |
| Image generation prompt | Optional, up to 80 characters. Correct any length error shown by the form. |
| Generate | Uses the current options and optional reference to generate a candidate for review. |
| Busy/progress | Disables options, Generate, Use this image, Remove image and Back for Pure. Memory-only Cancel/Retry controls are not present here. |
| Generated image / Use this image | Applies candidate; success clears draft options and returns. Failure keeps candidate/error so this same button can retry application. |
| Generation error | Error shown; Generate can start a new request with current options. No separate error Retry button for Pure. |
| Remove image | Available with current avatar. Named confirmation → Remove image; Cancel/dismiss sends nothing. |
| Back | Asks before discarding unsaved options. Cancel keeps editing; Discard leaves without saving them. |
| Initial catalog error Retry | Reloads management data, rather than repeating generation or application. |

## Limits and outcome

Reference maximum is 10 MiB, nonempty. Desktop supports local JPEG/PNG/WebP/GIF; mobile Pure supports JPEG/PNG/WebP. Follow any upload error shown by the form. Removing the reference keeps the device file.

Generation can use the bot's name, personal-room Gear Memories, optional style/prompt and chosen reference. Review the candidate before applying it. Finish one image change before starting another for the same DingDong, including from another device. A failed preview does not prove application.

After an uncertain Apply or removal, refresh the current profile before repeating. Image removal clears the applied image, saved reference and pending candidate, with no Undo; the DingDong identity and device files remain. Reopen from the current account after access changes. Do not rely on unfinished image work after an app restart.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/dingdongs/avatar-generation.md) · [UI index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/README.md)

[Inspect a DingDong profile](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/profile-and-image.md) · [Equip Gear](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/equip-gear.md) · [Rename or delete a Pure DingDong](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/dingdongs/maintain-pure.md)

Reviewed: 2026-10-23. UI labels use the English app language.
