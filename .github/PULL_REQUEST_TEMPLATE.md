# Pull Request: Apex Verification Gate

## 1. Commit & Title Guidelines
*   **Title Format:** Must strictly adhere to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/): `<type>(<scope>): <description>`
    *   *Example Scopes for Mobile:* `(scanner)`, `(ui)`, `(api)`, `(state)`, `(config)`.
    *   *Example Titles:* `feat(scanner): Add support for Aztec code decoding`, `fix(ui): Correct layout shift on configuration screen`.

## 2. Type Selection
<!-- Select ONE primary type that best describes the impact of this PR -->

- [ ] **feat**: A new feature or capability (Signals a Minor version bump).
- [ ] **fix**: A bug fix addressing functional or visual errors (Signals a Patch version bump).
- [ ] **refactor**: Code reorganization that preserves external behavior (Signals a Patch version bump).
- [ ] **test**: Adding missing tests or correcting existing test implementation.
- [ ] **docs**: Documentation-only changes (README, comments, templates).
- [ ] **chore**: Changes to the build process, CI/CD, or auxiliary tools (No version bump).

## 3. Bottom Line Up Front (BLUF) Summary
<!-- Provide a concise, two-sentence summary of what this PR achieves. Why should the reviewer care? -->

## 4. Context & Motivation
<!-- Why is this change necessary? Link directly to related issues using keywords (e.g., `Closes #123`, `Fixes #45`). -->

<!-- Describe architectural impact: Did this implement a Command or Query? Did it adhere to SOLID principles (especially SRP)? -->

## 5. Implementation Details & Verification
### A. Feature/Logic Description
<!-- Detail the core changes. If modifying the scanning pipeline, explain the new algorithm or dependency usage. -->

### B. Testing Protocol Execution (MANDATORY GATE)
*   **Unit/Component Tests:**
    *   [ ] New or modified logic is covered by Unit Tests (Vitest/Jest).
    *   [ ] State transition verification is in place.
*   **E2E/Integration Tests (if applicable):**
    *   [ ] Critical user flows impacted by this PR are validated by E2E tests (Detox/Playwright).
*   **Coverage Verification:**
    *   [ ] CI pipeline shows zero test failures.

### C. Documentation & Configuration
*   [ ] In-app documentation (Tooltips, Settings descriptions) updated if UI/UX changed.
*   [ ] Environment variables or configuration files (`app.config.ts`, etc.) reviewed and updated if necessary.
*   [ ] Architecture/Agent documentation reviewed if fundamental changes occurred.

## 6. Apex Architectural Alignment Check
<!-- Self-audit against the Authority Principles before submission. -->

- [ ] **CQS Adherence:** Is this PR purely a Command (writes) or purely a Query (reads)? (Avoid mixing).
- [ ] **Guard Clauses:** Are excessive nested `if/else` statements eliminated in favor of early returns?
- [ ] **Self-Documenting Code:** Is the code readable without relying on excessive line-by-line comments?
- [ ] **Security:** Are all external inputs (from user gestures or peripherals) appropriately validated/sanitized?

---

**⚠️ SELF-REVIEW CONFIRMATION**

By checking the boxes above, I confirm that this branch has passed all local linting (`biome check --apply`) and local testing (`jest` or `vitest`) with **ZERO WARNINGS OR ERRORS**.
