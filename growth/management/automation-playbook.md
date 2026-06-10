# Managing the 7 (then 15) Without Drowning — Automation Playbook

Your words: "My day job of managing the 7 requires a lot of follow up, checkins, assistance."
The fix is not more discipline; it's changing who initiates. Today information flows because you
chase it. Every system below flips one flow so information arrives without you asking.

## 1. Kill the chase: the Friday scorecard (do this first, costs $0)

The single biggest time sink for producing-team managers is *pulling* status. Flip it:

- Every originator fills one row of `team-production-tracker.csv` (or its Google Sheet twin) by
  **Friday 3pm** — 9 numbers, 2 text fields, five minutes of their time.
- Non-negotiable rule: **if it's not on the scorecard by 3pm Friday, it doesn't exist** — no
  credit in the Monday meeting, no exceptions. Two weeks of enforcement and it runs itself.
- Your Monday huddle then runs off one sheet in 20 minutes instead of seven fishing expeditions.
- What you stop doing forever: "hey, where are we on…" texts. The sheet is where we are.

## 2. Restructure the check-ins (recover ~6 hrs/week)

| Today (typical) | Replace with |
|---|---|
| Ad-hoc check-ins all week | Daily 15-min stand-up at 8:15am, whole team, pipeline-only, no chairs |
| 7 × 60-min weekly 1:1s | 7 × 25-min 1:1s, agenda auto-built from their scorecard row (see §4); deep-dive 60-min only monthly |
| "Got a sec?" interruptions | Daily office-hours block 4:00-5:00pm; everything non-urgent waits for it |
| You chasing deal statuses | Pipeline review IS the Monday meeting; CRM is the only source of truth |

The 1:1 agenda from a scorecard row writes itself: biggest pipeline delta, pull-through vs team
average, the blocker they listed, one coaching point. That's the meeting.

## 3. Standup/check-in bots (if the team lives in Slack or Teams)

Geekbot, Standuply, or DailyBot (~$3/user/mo) DM each originator the scorecard questions and
post a digest to a channel. Same flip — they answer once, you read one thread. Worth it if
Genesis is Slack/Teams-native; skip if the Google Sheet ritual sticks on its own.

## 4. What I (Claude) can run for you on a schedule

This repo + a recurring Claude session = a chief of staff that costs nothing. Once you say go,
each scheduled run can:

1. **Monday 6am — 1:1 prep pack**: read the week's scorecard, write a one-page brief per
   originator (trend vs last 4 weeks, outlier metrics, suggested coaching point, the question
   they should not be allowed to dodge), drop it in this repo or email it to you.
2. **Daily 6am — recruiting batch**: read the recruiting tracker, generate today's 10-15
   personalized outreach messages with names filled in, flag overdue follow-ups, draft Gmail
   follow-ups for candidates with known emails (drafts only — you hit send).
3. **Friday 4pm — week-in-review**: scorecard roll-up vs the $100M glidepath (see PLAN.md
   targets), recruiting funnel stats, the 3 things that most need your attention Monday.
4. **Monthly — roster refresh**: re-scan the trades for layoffs/wind-downs/M&A at western
   lenders and add fresh names to the roster with a "disruption" flag.

One note from looking at what's connected today: your **Gmail and Calendar here are the
personal account** (bradenhryan@gmail.com) — I can see dinner with the Newmans, not your team
1:1s. Connecting your Genesis account (or just sharing the team calendar / forwarding scorecards
to a label I can read) is what unlocks #1-3 fully. Timeline: send the scorecard email this week,
first scorecards due Friday June 19, first one-sheet Monday meeting June 22.

## 5. CRM hygiene (the unsexy one that matters at $200M)

At 7 originators you can manage from memory and texts. At 15 you cannot — and the #1 reason
scaling origination teams stall is that the manager's head stops scaling before the pipeline
does. Whatever Genesis runs (Salesforce/HubSpot/proprietary): every deal in the CRM same-day,
stage definitions written down, automated stale-deal alerts (no activity 7 days = flag), and
dashboards pulled from CRM, not from asking humans. If the current stack can't do that, raising
it with leadership is part of the $200M plan, not an IT nicety — say so in those words.

## 6. Delegate upward visibility

Once §1-2 run, your own weekly report to leadership is a 10-minute edit of the Friday roll-up.
And when the team hits ~10 people, promote your best operator to player-coach over a pod of 4-5
(keeping a reduced personal book). You cannot personally manage 15 originators and recruit and
produce — the org chart is also an automation.
