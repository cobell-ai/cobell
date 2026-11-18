# Use the Scheduler for an automatic DingDong response

## Configure the schedule

1. Create an AI-response Scheduler and choose its room and responder.
2. Choose Once, Daily, Weekly or Monthly.
3. Set the time and the date, weekdays or day of month required by that repeat type.
4. Read the timezone shown. An existing schedule keeps its saved timezone.
5. Set the late execution window, enter the prompt and choose room main or a new top-level thread.
6. Choose Always or a connected normal desktop/mobile condition, then save and confirm activation.

## Example: a project-chat recap every weekday at 6 pm

1. Create an AI-response Scheduler and select the project chat and an owned responding DingDong.
2. Set Weekly, Monday–Friday and 18:00. Check the saved timezone; the website example uses Asia/Seoul.
3. Enter: “Summarize today's decisions and open questions in this room.”
4. Use the room main conversation as the response context. Choose the connection condition and late execution window, save and confirm activation.
5. Inspect the new recap message in the project chat after execution. Use Enabled to pause future runs when the project no longer needs it.

The Scheduler invokes a prompt to generate a new response at the chosen time. It is not delivery of a prewritten message or the message-count-based Auto Reply setting. The response uses the conversation and resources accessible to the DingDong. Always can trigger while the owner's devices are offline; work that uses device tools still needs an eligible connected device.

## Completion and recovery

Once must be in the future; Weekly needs selected weekdays. The late window permits delayed execution only within the configured 0–60 minutes. It is not a guarantee that a disconnected device's tools can run.

Use the saved rule's Enabled switch to pause future triggering. If the app says creation needs verification, refresh or retry verification before adding another copy. Saving a schedule does not prove its eventual response completed; inspect the destination chat.

## Related guides

[Screen controls and locations](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/routines-notifications/scheduler.md) · [Routines and notifications index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/routines-notifications/README.md)

Reviewed: 2026-10-24 (Scheduler terminology and weekday recap example). UI labels use the English app language.
