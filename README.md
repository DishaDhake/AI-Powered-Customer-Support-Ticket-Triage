# AI-Powered Customer Support Ticket Triage — Tableau Dashboard

An interactive Tableau dashboard visualizing the output of an AI/ML ticket triage pipeline: 320 synthetic support tickets automatically classified by category, scored for sentiment, assigned a priority/SLA, and routed to a support team.

Built by Disha Dhake as part of a Business Analyst portfolio (Feb 2026 job search).

**Note on data:** No real company data was used. All tickets are synthetically generated to mimic a realistic support queue, so all numbers here demonstrate dashboard-building methodology rather than a production result.

## What's in the Dashboard

- **KPI tiles:** total tickets, average sentiment score, P1-Critical count, model accuracy
- **Breakdown charts:** tickets by category, by priority, by assigned team, by sentiment level
- **Filters:** category, priority, customer tier, sentiment, assigned team
- **Detail table:** ticket-level view with category, priority, sentiment, and team for each ticket

## How to Open

This repo includes the workbook as a `.twbx` (packaged workbook) — the data is embedded inside the file, so it opens with everything intact, no separate CSV needed.

1. Download `Tableau Dashboard for Tickets.twbx`.
2. Open it with Tableau Desktop, or upload it to [Tableau Public](https://public.tableau.com) to view/share it in a browser.

## Tech

Tableau Desktop / Tableau Public.
