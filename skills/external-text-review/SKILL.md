---
name: external-text-review
description: Audits external drafts for evidence and policy, without granting send permission.
---

# External Text Review

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Give an evidence-backed editorial verdict and correct a draft before sending.

## When to use

An email, proposal, presentation or post intended for third parties.

## Inputs

{{PARAMETERS}}, full text, audience, sender, links, sources and decision log.

## Output

**APPROVED/FIX** verdict, checklist, problematic excerpts, sources and corrected full text.

## Human approval

APPROVED means editorial quality only; {{APPROVER}} separately authorizes sending to a recipient.

## Common mistakes

Accepting numbers without a denominator; overlooking third-party data; approving unverified links or sender.

## Steps

1. Confirm the full draft, purpose, audience and visible identity of {{SENDER}}; ask if any are missing.
2. Audit maturity, contracts/acceptances, price, claims, numbers and periods, confidentiality, technical promises, positioning, names and links.
3. Mark each check compliant/error/to confirm; apply the seven-point quality test; separate what is known, under test and unknown.
4. Return **FIX** for a material issue, missing essential evidence or two quality failures; supply a complete revision and retest.
5. Return **APPROVED** only when applicable checks pass, explicitly stating that send authorization is still required.

## Copy-paste prompt

> Review [text] for [audience/channel] using {{PARAMETERS}} and [source references]. Check claims, maturity, numbers, personal data, sender and links; give APPROVED/FIX, cite problematic excerpts and sources and propose a full corrected version. Do not send.
