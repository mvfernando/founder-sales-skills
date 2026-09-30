---
name: weekly-operating-review
description: Reconciles weekly activity, scorecard, risks and pending decisions.
---

# Weekly Operating Review

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Consolidate activity, risks, pending items and decisions into a traceable weekly record.

## When to use

At week-end in the configured time zone and cadence.

## Inputs

{{PARAMETERS}}, context/decision log, {{CRM}}, email, calendar, scorecard and metrics.

## Output

One weekly scorecard row, dated summary, risks and next-cycle priorities.

## Human approval

Review pending decisions; delivery to third parties requires specific authorization.

## Common mistakes

Duplicating a row; entering zero without coverage; double-counting opportunities; counting a booked meeting as held.

## Steps

1. Fix the reporting period and consult available sources; flag gaps in coverage.
2. Deduplicate entities and opportunities; verify dates and actual statuses in {{CRM}}, email and calendar.
3. Write exactly one row for the week; attach source and counting rule to numbers, use “to confirm” for insufficient evidence.
4. Reconcile P-E-T, funnel rates, risks, overdue follow-ups and scale signals without exaggeration.
5. Update context only with dated facts and decision log only with explicit decisions.
6. Draft a brief summary of numbers, requested decisions, overdue/at-risk items and next week; do not claim a notice was delivered without confirmation.

## Copy-paste prompt

> Review [period] with {{PARAMETERS}}: cross-check sources, deduplicate, produce one scorecard row with criteria and summarize risks, decisions and next steps. Flag missing coverage and do not send externally.
