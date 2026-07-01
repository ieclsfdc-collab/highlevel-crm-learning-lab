# HighLevel CRM Learning Lab

This repo tracks MJ's focused HighLevel CRM learning.

## Purpose

Help MJ quickly become comfortable enough to:

- Navigate HighLevel without feeling lost
- Create basic HighLevel records and configuration
- Use proper HighLevel terminology instead of Salesforce terminology
- Understand the basic lead journey inside HighLevel
- Identify where the AI Orchestrator / Business Systems Investigator may need GHL-specific adjustments
- Prepare for a controlled demo or discussion with James

This is not a deep certification repo. This is a high-velocity learning repo.

## Learning Target

Recommended duration: **10 hours total**, ideally across **2 days**.

By the end, MJ should be able to explain this journey using GHL terminology:

> A Contact enters HighLevel through a Form. A Workflow applies a Tag, creates an Opportunity in a Pipeline, and the Contact's activity can be reviewed through Conversations and Contact activity.

## Learning Rhythm

Every exercise follows this rhythm:

```text
Do -> Confirm -> Summarize -> Self-check -> Continue
```

Each short milestone includes:

- Exact steps
- Expected result
- Milestone summary
- GHL terminology practice
- Quick self-check
- Common mistakes to avoid

## Repo Structure

```text
highlevel-crm-learning-lab/
|
├── README.md
├── CHATGPT_INSTRUCTION_RULES.md
├── LEARNING_STATUS.md
├── GHL_TERMINOLOGY.md
├── SALESFORCE_TO_GHL_MAP.md
├── DEMO_READINESS.md
|
├── exercises/
│   ├── 01-navigate-highlevel.md
│   ├── 02-create-contact-tag-custom-field.md
│   ├── 03-create-pipeline-and-opportunity.md
│   ├── 04-create-form-and-submit-test-lead.md
│   ├── 05-create-basic-workflow.md
│   ├── 06-create-calendar-and-appointment.md
│   └── 07-trace-full-lead-journey.md
|
└── templates/
    └── ghl-exercise-template.md
```

## Important Safety Rule

Do not store real client data, API keys, OAuth secrets, private screenshots, or sensitive James/client discussion in this repo.
