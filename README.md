# Policy Copilot Governance Demo

**Owner:** Wes Shelton | [LinkedIn](https://www.linkedin.com/in/wallace-shelton-559b0364) | [Agent Showcase](https://automater89.github.io/Agent-Showcase/)

## What This Demonstrates

This project shows how to design and govern a narrow AI assistant for HR or policy questions built in Microsoft Copilot Studio. The point is not the bot itself — it is the governance wrapper: what the bot answers, what it refuses, how it escalates, and how success is measured.

This directly reflects a core AI Process Innovation capability: knowing when AI is appropriate, how to bound its scope, and how to prove it is working safely.

## Problem

Employees repeatedly ask the same HR or policy questions through email, Teams messages, and informal channels. This creates inconsistent answers, delays, and load on HR staff. A narrow, governed AI assistant can reduce this friction — but only if it is designed with clear content boundaries, escalation paths, and measurement.

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Copilot Studio | Agent design and conversation flow |
| SharePoint / OneDrive | Source content / knowledge base |
| Word | FAQ document authoring |
| Power Automate | Optional: log unresolved questions for human review |
| Excel | Test case tracking and metrics |
| VS Code + GitHub Copilot | Documentation and prompt generation |
| GitHub | Version control and portfolio documentation |

## Folder Structure

```
policy-copilot-governance-demo/
├── README.md
├── docs/
│   ├── governance-summary.md
│   ├── content-design-notes.md
│   ├── test-plan.md
│   └── metrics-framework.md
├── source-content/
│   └── sample-faq-template.md
├── prompts/
│   └── copilot-prompts.md
├── screenshots/
│   └── (add Copilot Studio topics, test conversations, and flow screenshots here)
└── exports/
    └── (add test case Excel file and metrics snapshot here)
```

## What This Demonstrates for AI Process Innovation

- Responsible AI thinking: defining boundaries before building
- Conversational AI design with real governance controls
- Escalation path design and human-in-the-loop logic
- Test planning and effectiveness measurement
- Content quality standards for AI knowledge bases
- Alignment between AI output and business outcomes
