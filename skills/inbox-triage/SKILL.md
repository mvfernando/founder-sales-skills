---
name: inbox-triage
description: Classifies inbox items and flags decisions without unauthorized archival or replies.
---

# Inbox Triage

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Separate urgent items, actions, information and noise in the chosen inbox.

## When to use

After configuring an account, VIPs, urgency terms and archive policy.

## Inputs

{{PARAMETERS}}, inbox/last triage point, urgency criteria, VIPs and retention rules.

## Output

Counts by category, urgent items with sender/subject and pending decisions.

## Human approval

Confirm rules before archiving/deleting; sending and replying follow a separate approval policy.

## Common mistakes

Archiving without a rule; deciding urgency only from a keyword; mixing personal and business accounts.

## Steps

1. Choose the account explicitly and complete triage criteria.
2. Read unseen messages since the last processing point, grouped by thread.
3. Classify URGENT (deadline/risk), ACTION (reply), FYI (read) or LOW PRIORITY; justify borderline cases.
4. Flag and list; archive or delete only if authorized and preserve an audit trail.
5. Report counts and decisions needed; hand drafts to the reply skill, without implicit send authorization.

## Copy-paste prompt

> With {{PARAMETERS}} and approved inbox rules [reference], triage [account] since [checkpoint]. Return counts, urgent items and decisions. Do not delete, archive or reply without express permission for each action type.
