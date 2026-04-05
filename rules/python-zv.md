---
paths:
  - "**/*.py"
---

Python code should be concise and efficient whenever possible, but still clean and readable.

## New Code Generation

The following rules apply when generating new code. User requests always take precedence over these rules.

- Only keep **ONE** blank line between functions and MAJOR logical blocks within a function.
- For function declarations and invocations with <6 arguments / parameters, inline them.
- Never generate unit tests unless explicitly requested.
- When generating new code, all imports go to the top of the file.
- Default to library mode with a `if __name__ == '__main__':` block at the bottom of the file with usage. DONOT generate argparse script style code unless explicitly requested.
- Inline helper functions that are less than 3 lines of code and used less than 3 times.
- Only try/catch errors for the following 2 cases: 1. The runtime is expected to persist after the error 2. Not catching the error here would lead to silent crashes that's hard to diagnose.
- DONOT use typing hints unless crucial to functionality.