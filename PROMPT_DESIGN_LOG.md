# Prompt Design Log

This log is maintained in silent mode. It records substantial prompts and suggests stronger versions using:

- Goal
- Context Pointers
- Constraints
- Done When

## 2026-06-06

### Repo Setup And Prompt-Design Scenario Preparation

- Timestamp: 2026-06-06
- User prompt summary: Find a public React-plus-another-stack repo, clone it locally, set up command-line GitHub repo creation, and publish it as `greg-li/test-codex-scenario3`.
- What made the prompt effective: The desired outcome was concrete, including the repo name and the need for local rendering.
- How the prompt could have been stronger: It could have separated selection criteria, local verification, GitHub publishing, and auth/tooling success conditions up front.

Revised prompt:

```text
Goal
Find a public repo suitable for a Codex prompt-design test scenario, clone it locally, and publish it to my GitHub as greg-li/test-codex-scenario3.

Context Pointers
- Prefer React plus one substantial additional stack element, such as FastAPI, Django, Express, or Next.js.
- The scenario should support local rendering so I can use it in future live exercises.
- My GitHub account is greg-li.

Constraints
- Use a public repo with a permissive license.
- Prefer a repo with clear local development docs and visible UI.
- Configure command-line tooling so Codex can create GitHub repos with gh.
- Avoid using my old google.com email for commit attribution.

Done When
- The repo is cloned locally.
- GitHub CLI can create repos from the command line.
- A public GitHub repo exists at https://github.com/greg-li/test-codex-scenario3.
- The local main branch is pushed and tracks origin/main.
- Any auth or credential issues are explained by layer: Git identity, GitHub account email, gh auth, and Git credential helper.
```

