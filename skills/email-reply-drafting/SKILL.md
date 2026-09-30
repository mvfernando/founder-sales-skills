---
name: email-reply-drafting
description: Drafts contextual replies and escalates money, complaints and commitments.
---

# Email Reply Drafting

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Prepare a reply matching an approved style without assuming commitments beyond the mandate.

## When to use

An incoming email asks for an answer or clarification.

## Inputs

{{PARAMETERS}}, full thread, approved style/signature, escalation topics and verifiable data.

## Output

Draft with subject and recipients, or escalation summary and question for the decision-maker.

## Human approval

Send only after applicable authorization; money, complaints and commitments must be escalated.

## Common mistakes

Inventing a deadline; accepting a discount; replying outside the thread; revealing confidential information.

## Steps

1. Configure account, style, signature and escalation rules; otherwise do not imitate someone without a basis.
2. Read the entire thread and identify the main request, context and recipients.
3. If it involves money, partnership, complaint, legal risk, commitment or uncertainty, prepare an escalation; otherwise draft.
4. Lead with the answer, add brief context and one next step; verify tone, sources, deadlines and confidentiality.
5. Provide draft and notes; never treat “ready” as “sent”.

## Copy-paste prompt

> Using {{PARAMETERS}}, approved style [reference] and thread [reference], draft a brief response or escalate price, commitment or uncertainty. Identify recipients, claim sources and open items. Do not send.
