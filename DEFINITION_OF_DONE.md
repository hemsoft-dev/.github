# Definition of Done

A change is done only when every applicable item below is satisfied. Target
repositories may add stricter requirements through their instructions,
contribution guide, continuous integration, or branch rules.

## Shared minimum

- Every issue-specific acceptance criterion is met.
- Relevant automated tests are added or updated and pass. The pull request
  explains when an automated test is not appropriate.
- The target repository's build, formatting, lint, analysis, and test gates
  pass.
- Manual checks cover behavior that automated tests cannot prove.
- User-facing behavior, configuration, and operational changes have updated
  documentation when needed.
- Security, privacy, accessibility, compatibility, and performance effects are
  addressed when relevant.
- The change contains no unrelated work, unresolved review findings, or known
  regressions.
- The issue or pull request records enough validation evidence for another
  person to verify the result.

## Repository-specific requirements

Follow the target repository's `AGENTS.md`, contribution guide, and declared
quality gates. When a repository requirement is stricter than this shared
minimum, the stricter requirement wins.

## Exceptions

Marking an item as not applicable requires a short explanation in the issue or
pull request. An exception does not weaken the remaining requirements.
