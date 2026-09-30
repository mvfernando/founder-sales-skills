---
name: prospecting-outreach
description: Finds eligible leads, drafts sourced outreach and gates each send on human approval.
---

# Prospecting & Outreach

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Find and approach eligible opportunities without duplication or inappropriate contact.

## When to use

A new lead has documented eligibility and a permitted channel.

## Inputs

{{PARAMETERS}}, {{CRM}}, communication history, lead approval, a current public source, privacy rules.

## Output

A record per lead: eligibility, sources, draft, authorization, actual sending status and next step.

## Human approval

Approve contact, message, recipient and channel; an approved list does not waive per-send approval.

## Common mistakes

Mistaking a lead suggestion for approval; duplicate sends; promising unavailable capabilities; proceeding despite a pause.

## Steps

1. Reconcile identity, lead owner, consent or applicable legal basis, status and history across sources.
2. Check prior contact and pauses before **each** attempt; stop for duplicates, an existing reply or conflicting records.
3. Draft a specific, sourced opening, one question and a proportionate next step; submit it for external text review.
4. Show exact message and destination to {{APPROVER}}; act only if approval covers that version and recipient.
5. Confirm the actual send, notify via {{NOTIFY_CHANNEL}} when specified, log it in {{CRM}} and schedule follow-up only within the approved cadence.

## Copy-paste prompt

> Using {{PARAMETERS}}, check {{CRM}} and the history of [internal lead reference]. Determine eligibility, sources and duplicates; draft factual first contact and a next step. Show the exact message and recipient to {{APPROVER}}. Do not send without specific authorization.
