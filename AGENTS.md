# Repository Agent Instructions

## Prompt Design Coaching Log

Maintain a running prompt-design log for this repository at:

`PROMPT_DESIGN_LOG.md`

Use silent mode:

- Do not include prompt-coaching feedback in ordinary final responses unless the user asks for it.
- After a substantial prompt or task, append a concise entry to `PROMPT_DESIGN_LOG.md`.
- Do not update the log for tiny clarifications, simple status checks, or mechanical follow-ups.

For each logged entry, capture:

- Timestamp
- User prompt summary
- What made the prompt effective
- How the prompt could have been stronger
- A revised prompt using this structure:
  - Goal
  - Context Pointers
  - Constraints
  - Done When

Use OpenAI prompt-design best practices:

### Goal

State the desired outcome clearly and concretely.

### Context Pointers

Point to relevant files, repo areas, previous decisions, examples, or product context.

### Constraints

Name boundaries such as scope, tools, coding style, verification expectations, time limits, and what should not change.

### Done When

Define observable completion criteria, including tests, local rendering, command output, pushed branches, or artifacts.

