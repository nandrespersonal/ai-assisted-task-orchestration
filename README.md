# AI-Assisted Task Orchestration Practice

## Provenance

This practice was inspired by agentic AI work performed at Microsoft. The material in this repository is intentionally sanitized: examples, templates, and terminology are generalized so they do not include company-confidential project details, internal system names, customer data, credentials, or operational evidence.

## Core idea

AI-assisted task orchestration is a reusable practice for managing complex work from ambiguity to completion. It is not limited to service retirement or decommission projects. It is a general operating model for any work that requires evidence, owners, decisions, follow-up, and stakeholder communication.

The goal is to turn task management into a learning loop:

```text
Human intent -> AI orchestration -> bounded sensors/helpers -> evidence -> decision -> action -> follow-up -> learning
```

## Why this should be its own GitHub project

This should be productized as a project because the valuable asset is not a single plan or tracker. The durable value is the reusable harness:

- templates for canonical plans and trackers
- evidence and decision logging conventions
- role definitions for humans, AI agents, and tools
- follow-up cadences and escalation rules
- stakeholder communication patterns
- safety gates for owner approval, access, and execution
- lessons learned that improve future runs

The project should preserve the learning loop even when individual models, tools, or agents change.

## Practice principles

1. Human judgment stays central.
2. AI tools are bounded sensors, helpers, and orchestrators, not unchecked decision-makers.
3. Evidence beats inference.
4. Access is not approval.
5. Completion requires validation against the source of truth.
6. Waiting is active: every wait state needs a follow-up trigger.
7. Communication should be high-signal, consolidated, and relationship-aware.
8. Every mistake should become a better checklist, prompt, template, or guardrail.

## Recommended GitHub project shape

```text
ai-assisted-task-orchestration/
  README.md
  docs/
    practice.md
    roles.md
    safety-gates.md
    communication-patterns.md
    harness-engineering.md
  templates/
    operating-plan.md
    tracker-schema.md
    evidence-index.md
    decision-log.md
    eod-update.md
    follow-up-rules.md
  examples/
    generic-complex-task/
  prompts/
    status-check.md
    thread-check.md
    watch-task.md
    ticket-check.md
  evals/
    task-follow-through-rubric.md
    evidence-quality-rubric.md
    communication-quality-rubric.md
```

## Reusable operating model

| Layer | Purpose |
|---|---|
| Human owner | Sets intent, approves risky action, owns relationships and judgment. |
| Orchestrator | Maintains plan, compares evidence, chooses next action, prevents drift. |
| Sensors | Read tickets, threads, dashboards, pages, files, and other source systems. |
| Actuators | Execute approved actions or prepare commands for authorized humans. |
| Plan | Current state, next action, owners, blockers, and evidence. |
| Tracker | Row-level work management and follow-up state. |
| Evidence index | Links screenshots, tickets, logs, source reads, and owner statements. |
| Decision log | Captures why the team chose a path. |
| Communication loop | Turns work into concise stakeholder updates and explicit asks. |

## General template

Every complex task should have:

1. Mission and definition of done.
2. Scope and non-scope.
3. Current snapshot.
4. Active lanes.
5. Blocker table.
6. Owner/action map.
7. Safety gates.
8. Evidence index.
9. Follow-up cadence.
10. Stakeholder communication draft.
11. Decision log.
12. Lessons learned.

## Generic complex-task example

A generic complex task can be used as the seed example for this practice. It should demonstrate:

- reducing ambiguous blockers to concrete owner actions
- separating access enablement from operational approval
- handling source-of-truth disagreement across portals, ticketing systems, and operational records
- using AI/tools as bounded sensors rather than replacing human judgment
- keeping a noisy stakeholder thread high-signal through consolidated updates
- converting mistakes into durable guardrails

## Project thesis

Task management in an AI-assisted enterprise should not be a passive checklist. It should be a harness that compounds human capital and token capital.

The organization owns the learning loop: the patterns, evidence, prompts, decisions, safety gates, and follow-through discipline. Models and tools can change; the practice remains.
