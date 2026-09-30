---
name: meeting-notes-to-record
description: Turns primary meeting notes into citable facts, proposals, decisions and actions.
---

# Meeting Notes to Record

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Convert a transcript into citable memory without conflating statements, proposals and decisions.

## When to use

After a meeting with a transcript or primary note available.

## Inputs

{{PARAMETERS}}, transcript, actual meeting date, participants, calendar and {{CRM}}.

## Output

Document with **facts/proposals/decisions/actions/questions**, objections and sources; unambiguous CRM update if permitted.

## Human approval

Validate ambiguous decisions and any external communication of the summary.

## Common mistakes

Fabricating timestamps; attributing the founder’s proposal to the prospect; using processing date as meeting date.

## Steps

1. Confirm actual date, entity, meeting type and transcript; if the primary source is absent, request it rather than infer speech.
2. Extract separately facts (quote/location), proposals (speaker), decisions (who explicitly accepted), actions (owner/deadline), questions and objections.
3. Cite a timestamp only when one exists; otherwise say “timestamp unavailable”.
4. Avoid duplicates; record the demonstrated opportunity status without promoting “discussed” to “sent” or “accepted”.
5. Update a record only when its identity is unambiguous and permissions allow; add owner decisions to the decision log with a source.

## Copy-paste prompt

> Use {{PARAMETERS}} and transcript [reference] to record the meeting on [actual date]. Separate facts, proposals, explicit decisions, actions and questions; cite available passages/timestamps and flag uncertainty before updating {{CRM}}. Do not send the summary externally.
