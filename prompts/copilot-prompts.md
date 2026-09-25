# GitHub Copilot Prompts — Policy Copilot Governance Demo

Use these in VS Code Copilot Chat or GitHub Copilot to accelerate content authoring, governance documentation, and test case generation.

---

## Project Planning

```
/plan Build a narrow HR policy assistant in Microsoft Copilot Studio with a governance wrapper. Break the project into phases: content design, agent configuration, guardrails, testing, and measurement.
```

---

## Governance Document

```
Create a governance document for a narrow HR policy assistant built in Copilot Studio. Include sections for: purpose, in-scope vs out-of-scope topics, knowledge sources with owner and review frequency, escalation rules for out-of-scope and sensitive topics, responsible AI considerations (hallucination, privacy, bias, auditability, human-in-the-loop), and review and maintenance schedule.
```

---

## Source Content Authoring

```
Convert the following rough HR policy notes into clean FAQ entries suitable for a Copilot Studio knowledge base. Each entry should have one clear question, one plain-language answer, and a next step or contact. Keep answers factual and policy-safe. Flag anything that should be reviewed by legal or HR before publishing.
[Paste your raw notes here]
```

---

## Test Case Generation

```
Generate 20 realistic employee questions for testing an HR policy assistant. Include a mix of: clear in-scope questions, ambiguous questions that depend on context, out-of-scope questions the bot should refuse, privacy-sensitive questions that should redirect to HR, and adversarial prompts trying to get the bot to go off-script. Label each question by category.
```

---

## Metrics Framework

```
Create a metrics framework for measuring the effectiveness (not just productivity) of a narrow HR policy chatbot. Include KPIs for containment rate, answer accuracy, escalation rate, unresolved question rate, and content freshness. Include a monthly review checklist and a red flag table that maps metric signals to likely causes and recommended actions.
```

---

## Commit Message Helper

```
Based on the changes I just made to this project (list your changes here), write 3 clear Git commit messages in imperative style that describe what was added or updated.
```
