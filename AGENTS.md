# Project rules

These rules apply to every stage of this project.

1. **Protected files.** Never edit `backend/corpus/`, `docs/project-brief.md`, `AGENTS.md` or `CLAUDE.md`. Once the requirements are approved, `docs/PRD.md` and `docs/features.md` are protected too. If you think a protected file must change, stop and ask.
2. **Decisions belong to people.** When a decision is left open, give the options, the trade-off of each and your recommendation, then stop and wait. Never choose for us, and never fill in an open decision on our behalf.
3. **Stages run in order:** requirements, design and planning, implementation, testing and review, deployment, verification. No code before the plan is approved. Each stage writes its record in `tickets/`.
4. **Always stop and ask before:** adding a library the approved plan does not list, pushing to main, deploying, deleting data, or changing an agreed API or data model.
5. **No hardcoded config.** No literal model name, URL, threshold or secret in code; everything comes from environment variables. Never print, log or commit a secret.
6. **Tests and errors.** Never weaken, skip or delete a test to make it pass. Never swallow an error silently.
7. **No copyleft dependencies** (GPL, AGPL, LGPL, SSPL, EUPL).
8. **Only claim what you checked.** Say "I have not checked X" rather than guess.
