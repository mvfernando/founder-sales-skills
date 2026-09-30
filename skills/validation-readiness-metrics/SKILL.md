---
name: validation-readiness-metrics
description: Measures adoption, funnel progress and scale readiness from auditable evidence.
---

# Validation & Readiness Metrics

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Measure adoption, funnel and scale risk with evidence.

## When to use

When defining a pilot, reviewing usage milestones, closing the week or doing a periodic self-assessment.

## Inputs

{{PARAMETERS}}, deduplicated {{CRM}}, correspondence, product data, scorecard and decided criteria.

## Output

P-E-T per pilot, auditable funnel, justified alerts, 0–80 assessment and evidence gaps.

## Human approval

Approve changes to P-E-T and strategic interpretations; external communication needs review and send approval.

## Common mistakes

Counting a proposal as a start; dividing by zero; inferring revenue from an unpaid test; scoring absent evidence.

## Steps

1. Fix P (population), E (event measured by evidence), T (time window/milestones); retain original decision and versions.
2. At each milestone use actual numerator/denominator, date and source; distinguish success within the window from later progress. With no data, say “evidence missing”.
3. Build a weekly funnel: contacts → replies → meetings held → pilots proposed → pilots started → paid conversions. Give source, period, rate against previous stage and comparable change; use “n/a” when denominator is missing.
4. Flag sales without usage, channel dependence or operational friction **only** if owner-approved criteria/thresholds and available data support it.
5. Self-assess 0–80 across four 20-point dimensions: product–market fit, acquisition fit, operational readiness and team readiness. State criteria, evidence and gaps for each point; interpretation bands need owner approval and never replace usage proof.
6. Do not calculate unit economics without sufficient actual revenue and costs; separate external benchmarks, internal hypotheses and measured results.

## Copy-paste prompt

> Using {{PARAMETERS}}, [period/sources] data and approved pilot criteria, produce P-E-T, a funnel with rates and gaps, and a four-part 0–80 assessment with evidence per criterion. Never invent zeros or unsupported grades; list decisions needed.
