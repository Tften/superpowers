# Testing Superpowers

Superpowers has two distinct kinds of tests:

- **`tests/`** — does the plugin's non-LLM code work? Bash + node integration tests for brainstorm-server JS, OpenCode plugin loading, and analysis utilities.
- **`evals/`** — do agents behave correctly on real LLM sessions? A separate Python harness (the [superpowers-evals](https://github.com/prime-radiant-inc/superpowers-evals/) eval lab) driving real tmux sessions of coding agents, with an LLM actor and verifier judging skill compliance. Not part of this repo.

## Plugin tests

Live in `tests/`. Currently:

- `tests/opencode/` — bash tests for OpenCode plugin loading, bootstrap caching, and tool registration.
- `tests/diagnosing-superpowers/test-skill-structure.sh` — structural checks for the diagnosing-superpowers skill (frontmatter, referenced files, leak scan, word budget).
- `tests/explicit-skill-requests/` — multi-turn and skill-name-prompted tests not covered by quorum.
- `tests/shell-lint/test-lint-shell.sh` — tests for `scripts/lint-shell.sh`.
- `tests/systematic-debugging/test-find-polluter.sh` — tests for the find-polluter debug helper.
- `tests/version-bump/test-bump-version.sh` — tests for `scripts/bump-version.sh`.

Run plugin tests via the relevant directory's `run-*.sh`.

## Skill behavior evals

Live in the separate `superpowers-evals` repo (see link above). Quorum is the harness CLI — it drives real coding-agent CLIs through a Gauntlet QA agent and grades them against each scenario's acceptance criteria plus deterministic post-checks. See that repo's README for setup, the container runtime, and the safety model.
