# GitHub Copilot Overview

## Keyboard Shortcuts

| Action                     | Visual Studio        | VS Code           |
| -------------------------- | -------------------- | ----------------- |
| Next inline suggestion     | `Alt`+ `.`           | `Alt`+ `]`        |
| Previous inline suggestion | `Alt` + `,`          | `Alt`+ `[`        |
| Trigger inline suggestion  | `Ctrl` + `Alt` + `\` | `Alt` + `\`       |
| Accept inline suggestion   | `Tab`                | `Tab`             |
| Dismiss inline suggestion  | `Esc`                | `Esc`             |
| Inline Copilot Chat        | `Alt` + `/`          | `Ctrl` + `I`      |
| Open Copilot Chat          | `Ctrl` + `\`, `C`    | `Ctrl` + `Return` |

## Slash Commands

- `/doc` to add a documentation comment
- `/explain` to explain the code
- `/fix` to propose a fix for the problems in the selected code
- `/generate` to generate code to answer your question
- `/help` to get help with Copilot Chat
- `/optimize` to analyze and improve the running time of the selected code
- `/tests` to create unit tests for the selected code

## Context and Scope

The context variables allow you to scope your conversation with Copilot to a file, a specific error or to the entire solution using the `#` symbol.

| Context variable              | Scope                                                            |
| ----------------------------- | ---------------------------------------------------------------- |
| `#file:<path>`                | Scope to the given file                                          |
| `#file:<path>:start-end`      | Scope to a range of lines within a file                          |
| `#solution`                   | Include all files in the current solution                        |
| `#error:<error_code>`         | Scope to a specific error                                        |
| `#errors:<path>`              | Scope to all errors in a file                                    |
| `#errors:<path>:<error_code>` | Scope to all errors with the given error code in the given file. |

!!! note "Examples"
    - `How do I fix #errors:CompanyStats.cs?`
    - `What does #file:'GitHubService.cs':78-122 do?`
    - `/optimize #file:'GitHubService.cs':100-116`.
