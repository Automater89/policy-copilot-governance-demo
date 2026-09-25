# Metrics Framework: Policy Copilot

## Philosophy

AI productivity does not equal AI effectiveness. A bot that answers 200 questions per day is not effective if 40% of those answers are wrong or if the questions it cannot handle are the most important ones. Metrics should measure outcomes, not volume.

## Core KPIs

| KPI | Definition | Target | Measurement Source |
|---|---|---|---|
| Containment Rate | % of sessions resolved without escalation | > 70% | Copilot Studio analytics |
| Answer Accuracy | % of in-scope answers rated correct in test | > 90% | Monthly test run |
| Escalation Rate | % of sessions that trigger escalation | < 30% | Power Automate log |
| Unresolved Question Rate | % of sessions that end without a clear answer | < 15% | Copilot Studio analytics |
| Top Unresolved Topics | Most frequent questions the bot could not answer | Review monthly | Power Automate log |
| Source Content Freshness | Days since last review of each source document | < 90 days | SharePoint metadata |

## Monthly Review Checklist

- [ ] Pull containment and escalation rates from Copilot Studio
- [ ] Review Power Automate unresolved question log
- [ ] Re-run 10 core test cases and log results
- [ ] Identify top 3 content gaps (questions the bot can’t answer well)
- [ ] Flag any source documents approaching 90-day review threshold
- [ ] Update source content if policy or process has changed
- [ ] Report results to HR and IT governance lead

## Red Flags

| Signal | Likely Cause | Action |
|---|---|---|
| Containment rate drops below 60% | Source content gap or scope creep | Review top unanswered topics, update FAQ |
| Accuracy drops below 80% | Source content conflict or outdated info | Content audit and refresh |
| Same question escalated 5+ times | Missing FAQ entry | Add to source content |
| Sensitive topic reached bot | Scope creep in source or user workaround | Tighten topic boundaries |
