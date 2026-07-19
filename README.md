# HighLevel CRM Learning Lab

## Current status

**Reference/learning repository. Parked from the Salesforce MVP critical path.**

This repo remains useful for HighLevel terminology, exercises, demo preparation, and future connector research. It is not the active Business Systems Orchestrator product repo and should not receive Salesforce MVP implementation tasks.

Active Salesforce product work belongs in:

```text
ieclsfdc-collab/business-systems-orchestrator
```

Cross-project ideas and decisions belong in:

```text
ieclsfdc-collab/mj-kb
```

Resume this lab when HighLevel learning directly supports a customer engagement or when a HighLevel connector becomes an approved post-pilot priority.

## Purpose

Help MJ quickly become comfortable enough to:

- navigate HighLevel without feeling lost;
- create basic HighLevel records and configuration;
- use proper HighLevel terminology instead of Salesforce terminology;
- understand the basic lead journey inside HighLevel;
- identify future Business Systems Orchestrator connector adjustments;
- prepare for a controlled demo or client discussion.

This is not a deep certification repo. It is a high-velocity learning and reference repo.

## Learning target

Recommended duration: **10 hours total**, ideally across **2 days**.

By the end, MJ should be able to explain this journey using HighLevel terminology:

> A Contact enters HighLevel through a Form. A Workflow applies a Tag, creates an Opportunity in a Pipeline, and the Contact's activity can be reviewed through Conversations and Contact activity.

## Learning rhythm

```text
Do → Confirm → Summarize → Self-check → Continue
```

Each milestone includes exact steps, expected results, terminology practice, self-checks, and common mistakes.

## Repo structure

```text
highlevel-crm-learning-lab/
├── README.md
├── CHATGPT_INSTRUCTION_RULES.md
├── LEARNING_STATUS.md
├── GHL_TERMINOLOGY.md
├── SALESFORCE_TO_GHL_MAP.md
├── DEMO_READINESS.md
├── exercises/
│   ├── 01-navigate-highlevel.md
│   ├── 02-create-contact-tag-custom-field.md
│   ├── 03-create-pipeline-and-opportunity.md
│   ├── 04-create-form-and-submit-test-lead.md
│   ├── 05-create-basic-workflow.md
│   ├── 06-create-calendar-and-appointment.md
│   └── 07-trace-full-lead-journey.md
└── templates/
    └── ghl-exercise-template.md
```

## Safety rule

Do not store real client data, API keys, OAuth secrets, private screenshots, or sensitive client discussions in this repository.