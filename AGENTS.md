# AGENTS.md — webinterface

Big Five NEO IPIP-300 test interface.

## Onboarding status
- Registry: public, Tools; local path `webinterface`.
- This is a baseline onboarding shell generated from registry metadata on 2026-09-04.
- Full repository audit, domain mapping, and run-command verification remain pending. Do not infer behavior from this file.

## Task state
- `TASK_STATE.md` is the provider-neutral execution contract.
- Read the repository README and local documentation before making changes.

## Safety
- Preserve existing project conventions.
- Do not commit, tag, push, publish, or modify generated artifacts unless explicitly requested.

## Decisions as multichoice (mandatory)

- Whenever a user decision is required — action items, choices, recommendations — present it as a
  multiple-choice question with pickable options (2–5, one line each) via the surface's question
  popup (Hermes: the `clarify` tool, "the questioner"). Never as prose options buried in a report or
  narrative. One question at a time; the popup carries the decision, the message carries the reasoning.
- Source of truth: `master-llm-instructions/settings/AGENTS.md` ("Decisions as multichoice").
