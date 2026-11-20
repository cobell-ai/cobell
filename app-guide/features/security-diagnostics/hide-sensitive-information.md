# Hide sensitive information in tool results

On the device that runs the built-in Toolbox, open **Security → Hide sensitive information → Add a value**. On mobile, open **More → Security**. Enter the sensitive text, select the Toolboxes that can return it and save. Configure each execution device separately.

Matches are literal, case-sensitive substrings. Spaces, quotation marks and backslashes are part of the value. A rule for `12` matches both `AC-1207` and `12:30`. Use the full order number if the time should stay readable. A common value such as `true` can also match a required tool status and make the affected result unavailable. If a result is unexpectedly hidden or unavailable, review the value and its selected Toolboxes on the execution device.

Hiding applies to outgoing tool text. The original data and the Toolbox's access permissions are unchanged.

[Screen controls](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/ui/security-diagnostics/hide-sensitive-information.md) · [Features index](https://raw.githubusercontent.com/cobell-ai/cobell/main/app-guide/features/security-diagnostics/README.md)
