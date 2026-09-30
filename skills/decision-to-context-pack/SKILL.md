---
name: decision-to-context-pack
description: Logs explicit decisions and updates only the affected context and team briefs.
---

# Decision to Context Pack

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Propagate an explicit decision without erasing history or changing unrelated areas.

## When to use

An unambiguous decision-maker statement with source and date.

## Inputs

{{PARAMETERS}}, statement, current context/decision log, affected tasks and roles.

## Output

Dated decision entry, corrected context sections, tasks and draft briefs awaiting approval.

## Human approval

Confirm interpretation of the decision and authorize communication to specific recipients.

## Common mistakes

Treating a suggestion as an order; overwriting the prior decision; broadcasting to the entire team.

## Steps

1. Check source, author, date, scope and difference from prior state; ask for clarification if ambiguous.
2. Log the decision, change and status; mark older decisions superseded rather than deleting them.
3. Edit only affected sections of {{CONTEXT_FOLDER}} and link the decision log.
4. Update tasks/cards only with permission and unambiguous record mapping.
5. Draft the minimum individual brief for each affected role, saying what changes and what **not** to do; send only after approval.

## Copy-paste prompt

> Using {{PARAMETERS}}, check whether [source/date statement] is an explicit decision. If so, propose a decision-log entry and minimal context edits preserving history; draft briefs only for affected roles. Do not send.
