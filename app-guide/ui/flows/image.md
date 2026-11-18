# Change a Flow image: screen reference

Generate a candidate, apply it to the Flow or remove the current image.

## Open this screen

**Desktop:** Flow list → click the Flow image, or row menu → generate image/remove image.

**Mobile:** Flow list → row menu → Flow image.

## Controls

| Control or area | Behavior |
|---|---|
| Art style | Anime, Pixel Art, Realistic 3D, Cartoon, Watercolor or Line Art. Desktop's first step also offers Skip; Next continues with a selected style. |
| Back / Cancel | Desktop generation options return to the style step or abandon the options dialog. |
| Reference image / Change reference image | Selects optional image guidance. Removing the reference clears the input, not the Flow's current image. |
| Prompt | Optional generation guidance, up to 80 characters. |
| Generate | Starts generation and shows progress. |
| Cancel generation | Mobile cancels the pending generation. Desktop's progress dialog instead offers Close; its job can be reopened from the image/status surface. |
| Candidate preview | Shows the generated result before application. |
| Regenerate | Desktop repeats generation with the last request. Mobile can use Generate again. |
| Apply / Use this image | Applies the displayed candidate to this Flow. |
| Retry | Retries the failed generation, application or removal operation when offered. |
| Remove image / Clear | Asks for confirmation before removing the applied Flow image. |
| Close | Leaves the image view. It does not apply an unaccepted candidate. |

## Conditions and results

Generation and application are separate operations. Image changes do not change the Flow graph. Mobile reference images must be nonempty JPEG, PNG, WebP or GIF data within 10 MiB; permission, format or read errors are shown by the picker.

These controls require a normal signed-in session. Active execution or another image operation can disable actions. Inspect the result after a failed apply/remove rather than assuming it succeeded.

## Related guides

[How to complete this task](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/flows/image.md) · [Flow index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/flows/README.md)

Reviewed: 2026-10-23. UI labels use the English app language.
