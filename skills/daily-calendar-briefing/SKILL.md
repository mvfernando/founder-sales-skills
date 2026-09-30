---
name: daily-calendar-briefing
description: Drafts a concise daily agenda from verified calendar logistics.
---

# Daily Calendar Briefing

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Prepare the day with agenda, logistics and confirmed context.

## When to use

A workday or selected period after configuring account, time zone and delivery channel.

## Inputs

{{PARAMETERS}}, chosen calendar, time zone, detail level and delivery channel.

## Output

Short daily agenda with first meeting, preparation, focus blocks and delivery status.

## Human approval

Confirm channel and recipient; no automatic send without configuration and consent.

## Common mistakes

Wrong time zone, old link, assumed context or exposing guests to the wrong recipient.

## Steps

1. Validate account/calendar, time zone and period; reconcile recent changes.
2. List meetings with time, duration, participants and link/location at the permitted detail level.
3. Highlight first meeting, preparation, focus time and relevant new contacts.
4. Format for {{NOTIFY_CHANNEL}} or a specifically authorized channel; protect personal data.
5. Deliver as a draft, or send only if policy and explicit authorization cover this briefing; confirm the result.

## Copy-paste prompt

> Using {{PARAMETERS}} and calendar [account/time zone], prepare the briefing for [date] with first meeting, verified links, preparation and focus. Flag items to confirm and do not send without an authorized channel and recipient.
