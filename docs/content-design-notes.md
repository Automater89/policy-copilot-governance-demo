# Content Design Notes: Knowledge Base for Policy Copilot

## Why Content Quality Matters More Than Bot Design

A Copilot Studio agent is only as good as its source content. Vague, inconsistent, or outdated FAQs produce unreliable answers regardless of how well the bot is configured. Content design is the most important and most overlooked step in building an effective policy assistant.

## Content Standards for This Project

| Standard | Why It Matters |
|---|---|
| Each Q&A is one clear question with one clear answer | Prevents multi-part confusion in retrieval |
| Answers use plain language, not policy jargon | Employees ask in natural language; the answer should match |
| Each answer ends with a clear next step or contact | Prevents dead-ends that force escalation unnecessarily |
| Sensitive topics are either excluded or redirected explicitly | Reduces risk of harmful or misleading output |
| Each document has a version date and owner | Enables governance tracking and timely updates |

## Content Review Process

1. Draft FAQ set in Word
2. HR subject matter expert reviews for accuracy
3. Legal or compliance reviews sensitive sections
4. Plain language pass to simplify jargon
5. Upload to SharePoint as source document
6. Link document in Copilot Studio knowledge configuration
7. Run test cases to confirm retrieval accuracy
8. Schedule quarterly review reminder

## What to Avoid

- Do not paste entire policy documents as source content. Extract the relevant Q&A pairs only.
- Do not include content that contradicts other source documents. Copilot cannot resolve conflicts — it will guess.
- Do not add topics the bot was not designed to answer. Scope creep in source content creates unpredictable behavior.
