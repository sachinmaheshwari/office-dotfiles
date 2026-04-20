# Development Rules

## Test-Driven Development (TDD) — Mandatory

These rules are non-negotiable. No exceptions without explicit user permission.

### The Iron Law
**No production code without a failing test first.**

Write code before the test? Delete it. Start over.

### One Test at a Time
- Write **one** test for **one** behavior.
- Run it. Watch it fail. Then write minimal code to pass it.
- Do NOT write multiple tests upfront before any implementation.
- Do NOT write a test suite of 10, 20, or 100 tests and then start coding.
- After each Red-Green-Refactor cycle, write the **next single test**.

### Red-Green-Refactor (strictly in order)
1. **RED** — Write one minimal failing test. Verify it fails for the right reason.
2. **GREEN** — Write the simplest code that makes it pass. No extras.
3. **REFACTOR** — Clean up code and tests. Keep everything green.
4. Repeat from step 1 for the next behavior.

### Minimal Code
- Write only what is needed to pass the current test. Nothing more.
- No speculative features, no extra configurability, no future-proofing.

### Verification Before Moving On
- Always run the test and confirm the failure message before implementing.
- Always run the full suite after going green to catch regressions.

### Use the TDD Skill
Before any implementation work, invoke: `superpowers:test-driven-development`
