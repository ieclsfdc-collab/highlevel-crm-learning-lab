# Exercise 07: Trace Full Lead Journey

## Goal

Trace the complete beginner HighLevel journey from lead capture to Contact, Tag, Opportunity, Workflow, Appointment, and activity review.

## Estimated Time

75 to 90 minutes

## Starting Point

Start inside a test sub-account/location after completing Exercises 01 to 06.

## What You Will Inspect

| Area | What to Confirm |
|---|---|
| Form | Lead entry point |
| Contact | Central person record |
| Tag | Label applied to Contact |
| Custom Field | Extra Contact information |
| Workflow | Automation path |
| Opportunity | Lead/deal tracking card |
| Pipeline | Process where Opportunity is tracked |
| Calendar | Booking setup |
| Appointment | Booked meeting |
| Conversations / Contact activity | Communication and activity history |

## Milestone 1: Start from the Lead Entry Point

### Steps

1. Open `MJ Test Lead Form`.
2. Submit a fresh safe test lead.
3. Write down the exact Form name.
4. Go to Contacts and find the submitted Contact.

### Expected Result

You can prove that the Contact entered HighLevel through a Form.

### Milestone Summary

In this milestone, you learned that:

- The lead journey starts from an entry point.
- A Form can be that entry point.
- The Contact is the result you inspect after submission.

### Remember This in GHL Terms

A Contact entered HighLevel through a Form. The Form is the lead entry point.

### Quick Self-Check

1. What was the lead entry point?
2. What Contact was created or updated?
3. Where did I verify it?
4. What could fail at this entry point?
5. What should the Orchestrator ask first?

## Milestone 2: Confirm Contact Data

### Steps

1. Open the submitted Contact.
2. Confirm the Contact name and email.
3. Confirm whether the Tag `ghl-test-lead` appears.
4. Confirm whether `Service Interest` is populated.
5. Write down what is present and what is missing.

### Expected Result

You know whether Contact data, Tag, and Custom Field values are correct.

### Milestone Summary

In this milestone, you learned that:

- Contact inspection confirms whether captured data is usable.
- Tags and Custom Fields help qualify and route Contacts.
- Missing Contact data can break later automation.

### Remember This in GHL Terms

A Contact can have Tags and Custom Fields. Workflows may use those values to decide what happens next.

### Quick Self-Check

1. What Contact data did I confirm?
2. What Tag is present?
3. What Custom Field is present?
4. What was missing, if anything?
5. What should the Orchestrator inspect on Contact data?

## Milestone 3: Confirm Workflow and Opportunity Result

### Steps

1. Go to Workflows.
2. Open `MJ Test Form Follow-Up Workflow`.
3. Confirm the trigger is the Form submission.
4. Confirm the actions apply the Tag and create or update an Opportunity.
5. Go to Opportunities.
6. Confirm the Opportunity is in `MJ Test Pipeline`.
7. Confirm the correct Pipeline stage.

### Expected Result

You can explain how the Form submission became an Opportunity in a Pipeline.

### Milestone Summary

In this milestone, you learned that:

- A Workflow connects the Form submission to later actions.
- A Workflow can apply a Tag and create or update an Opportunity.
- The Opportunity should appear in the correct Pipeline stage.

### Remember This in GHL Terms

The Workflow started from a Form submission. The Workflow applied a Tag and created or updated an Opportunity in the Pipeline.

### Quick Self-Check

1. What Workflow did I inspect?
2. What trigger starts it?
3. What actions does it perform?
4. Where is the Opportunity?
5. What could the Orchestrator inspect if the Opportunity is missing?

## Milestone 4: Confirm Appointment and Activity

### Steps

1. Go to Calendars.
2. Confirm `MJ Test Booking Calendar` exists.
3. Confirm whether a test Appointment exists.
4. Open the related Contact.
5. Review Conversations or Contact activity.
6. Write down what activity you can see.

### Expected Result

You can find Calendar, Appointment, and Contact activity areas.

### Milestone Summary

In this milestone, you learned that:

- Calendars manage booking availability.
- Appointments represent booked meetings.
- Conversations and Contact activity help inspect communication and history.

### Remember This in GHL Terms

A Contact can book an Appointment through a Calendar. Conversations and Contact activity help show what happened with that Contact.

### Quick Self-Check

1. What Calendar did I inspect?
2. What Appointment did I inspect?
3. Where did I find activity?
4. How does this support follow-up?
5. What could the Orchestrator inspect here?

## Final Memory Checkpoint

Explain this without looking:

1. How does a Contact enter HighLevel?
2. What does a Form do?
3. What does a Workflow do?
4. What does a Tag do?
5. What does a Custom Field do?
6. What does an Opportunity track?
7. What does a Pipeline show?
8. What does a Calendar do?
9. What is an Appointment?
10. Where do I inspect Contact communication or activity?

## Final Practice Sentence

Practice saying this clearly:

> A Contact entered HighLevel through a Form. A Workflow applied a Tag, used Contact data, created or updated an Opportunity in a Pipeline, and the Contact's activity can be reviewed through Conversations and Contact activity.

## Learning Note to Save

Update `LEARNING_STATUS.md` using the standard learning note format.

## Orchestrator Reflection

Write 3 possible HighLevel inspection modules:

1. Workflow Inspector
2. Pipeline and Opportunity Inspector
3. Contact Data and Lead Journey Inspector
