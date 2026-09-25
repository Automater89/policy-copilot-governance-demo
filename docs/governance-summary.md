# Governance Summary: Policy Copilot

## Purpose

This document defines the operational boundaries for a narrow HR policy assistant built in Copilot Studio. It governs what the bot can answer, what it must not answer, how it escalates, and how performance is evaluated.

This document would be reviewed and approved by HR, IT, Legal, and the AI governance lead before the bot goes live.

---

## Scope

| In Scope | Out of Scope |
|---|---|
| Benefits eligibility FAQs | Individual benefits calculations or advice |
| Leave policy summaries | Legal interpretation of leave law |
| Onboarding checklist guidance | Compensation or pay decisions |
| IT access request process | Performance management topics |
| General HR contact routing | Disciplinary or termination topics |

---

## Knowledge Sources

| Source | Type | Owner | Review Frequency |
|---|---|---|---|
| Benefits FAQ document | Word doc in SharePoint | HR Benefits Lead | Quarterly |
| Leave Policy summary | Word doc in SharePoint | HR Compliance | At policy change |
| Onboarding checklist | SharePoint page | HR Ops | At process change |

---

## Escalation Rules

| Trigger | Escalation Path |
|---|---|
| Question outside defined topics | "I’m not set up to answer that. Please contact HR at [contact]." |
| Low-confidence answer | "I want to make sure this is accurate. Please confirm with HR directly." |
| Sensitive personal topic detected | Immediate redirect: "This sounds like something that needs a personal conversation. Please reach out to HR directly." |
| 3 consecutive unresolved turns | Offer to log a follow-up request via Power Automate |

---

## Responsible AI Considerations

1. **Hallucination risk:** Bot is grounded in specific source documents only. Responses outside those documents trigger fallback.
2. **Data privacy:** Bot does not ask for or store employee PII. No personal data in conversation logs.
3. **Bias risk:** Source content is reviewed by HR before publishing to ensure inclusive language and accurate representation.
4. **Auditability:** Power Automate log captures unresolved questions for HR review and content iteration.
5. **Human in the loop:** No employment decisions are made by the bot. It informs and routes only.

---

## Review and Maintenance

- Source content reviewed quarterly or at policy change
- Test cases re-run monthly
- Escalation rate reviewed monthly; spikes trigger content review
- Governance doc reviewed annually or at significant scope change
