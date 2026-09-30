---
name: weekly-calendar-review
description: Finds calendar conflicts and focus-time risks without moving events.
---

# Weekly Calendar Review

Use the filled [product parameters](../../PARAMETERS.md) at runtime; `{{PARAMETERS}}` means that filled block, not the blank template.

> **Shared rule:** Read the filled `{{PARAMETERS}}` block, current context and decision log. Separate fact, hypothesis, proposal and decision; give the source, date and scope for every number. Editorial approval never authorizes sending. If sources conflict, stop the claim/action and request a decision. Without a connected tool, access or evidence, report a draft/pending item—never pretend an action happened. Every external send requires specific human approval of the exact content, recipient, channel and sender.

## Objective

Identify conflicts and protect deep-work time.

## When to use

Before the next workweek, after configuring thresholds and calendar.

## Inputs

{{PARAMETERS}}, week’s agenda, focus target, meeting-load threshold and priority contacts.

## Output

Meeting summary, busiest day, focus hours, conflicts and suggestions.

## Human approval

Validate any rescheduling, invitation or message to participants.

## Common mistakes

Moving a meeting without consent; flagging load without a threshold; missing agenda-less meetings or breaks.

## Steps

1. Read the full agenda for the period in the chosen time zone.
2. Flag overlaps, back-to-back meetings without a break, load beyond the approved threshold, meetings without an agenda and new external contacts.
3. Compare focus blocks with the configured target; if encroached upon, offer options and consequences.
4. Return a decision table and recommendations without changing events on your own.

## Copy-paste prompt

> Review [week] using {{PARAMETERS}}, approved focus target and meeting-load threshold. Show conflicts, load, focus blocks and rescheduling options; do not change events or contact participants.
