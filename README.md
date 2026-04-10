# copilot-agents

A collection of GitHub Copilot agent files.

## Repository contents

- `TDD/agents` - TDD orchestrator and phase agents
- `TDD/README.md` - documentation for the TDD agents

## TDD agents

The TDD agents provide a structured Red → Green → Refactor workflow:

- `TDD` orchestrates the overall cycle
- `TDD Red` creates focused failing tests
- `TDD Green` implements the smallest passing change
- `TDD Refactor` performs safe cleanup after tests pass

See `TDD/README.md` for the full TDD agent overview.
