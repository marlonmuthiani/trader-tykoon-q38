# AGENTS.md

## Mission

Trader Tykoon Q38 is a documentation-first trading intelligence workspace. This repository is designed to guide future implementation with explicit hierarchy, clear contracts, and a structured planning model.

## Operating model

This project follows the ICM (Interpretable Context Methodology) style:

- root files define purpose and routing
- documentation files describe scope, system behavior, and decisions
- folders separate product, process, and reference material
- every artifact must be clear enough for a new agent to understand without prior memory

## Root map

- `README.md` — project overview
- `PRD.md` — product requirements and business logic
- `ARCHITECTURE.md` — system architecture and boundaries
- `ROADMAP.md` — phased delivery plan
- `CONTRIBUTING.md` — contribution guidelines
- `INTEGRATION.md` — external integrations and contracts
- `.DESIGN.md` — design principles and standards
- `docs/` — supporting documentation and HTML viewer pages
- `skills/` — reusable operational guidance for agents
- `assets/images/` — diagrams and visual references

## Agent principles

1. Preserve clarity over cleverness.
2. Prefer explicit file contracts over implicit state.
3. Treat documentation as executable architecture.
4. Any missing decision must be recorded as a design gap, not a silent assumption.
5. Human review gates must remain visible.

## Working rules

- Do not add implementation code without an architecture and product requirement basis.
- If a feature introduces a new risk path, document the risk before implementation.
- Keep feature narratives and system contracts aligned.
- Prefer small, reviewable changes over broad undocumented rewrites.

## Primary tasks

- product planning and requirement maintenance
- design review and risk assessment
- architecture validation
- integration mapping
- operational readiness documentation
- release and milestone tracking

## Decision protocol

When architecture choices are uncertain:

1. record the option
2. list the trade-offs
3. define the assumptions
4. designate a decision owner
5. attach a review condition

## Completion standard

A task is complete when the output is readable by a new agent, traceable to a requirement, and does not conceal operational or risk assumptions.
