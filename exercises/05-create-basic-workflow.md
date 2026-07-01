# Exercise 05: Create Basic Workflow

## Goal

Create a simple Workflow that responds to a Form submission and performs basic actions.

## Estimated Time

75 to 90 minutes

## Starting Point

Start inside a test sub-account/location. Complete Exercise 04 first if possible.

## What You Will Create

| Item Type | Exact Name to Use |
|---|---|
| Workflow | MJ Test Form Follow-Up Workflow |
| Trigger | Form submitted: MJ Test Lead Form |
| Action | Add Tag: ghl-test-lead |
| Action | Create or Update Opportunity in MJ Test Pipeline |

## Milestone 1: Create the Workflow

### Steps

1. Go to Automation or Workflows.
2. Create a new Workflow.
3. Name it `MJ Test Form Follow-Up Workflow`.
4. Keep it unpublished until all steps are reviewed.

### Expected Result

You can see a Workflow named `MJ Test Form Follow-Up Workflow`.

### Milestone Summary

In this milestone, you learned that:

- A Workflow is HighLevel's automation builder.
- A Workflow should have a clear name.
- Keeping it unpublished while building reduces accidental automation.

### Remember This in GHL Terms

A Workflow automates actions in HighLevel. A Workflow can respond to a trigger and perform actions on a Contact or Opportunity.

### Quick Self-Check

1. What Workflow did I create?
2. Where can I find it again?
3. Why should I name it clearly?
4. Why keep it unpublished while building?
5. What could the Orchestrator inspect in a Workflow?

## Milestone 2: Add the Workflow Trigger

### Steps

1. Open the Workflow.
2. Add a Workflow Trigger.
3. Choose a Form submission trigger if available.
4. Select `MJ Test Lead Form`.
5. Save the trigger.

### Expected Result

The Workflow starts when `MJ Test Lead Form` is submitted.

### Milestone Summary

In this milestone, you learned that:

- A Workflow Trigger starts the automation.
- A Form submission can start a Workflow.
- Trigger filters must match the intended entry point.

### Remember This in GHL Terms

A Workflow Trigger is the event that starts a Workflow. In this exercise, the trigger is a Form submission.

### Quick Self-Check

1. What trigger did I add?
2. Which Form starts the Workflow?
3. What happens if the wrong Form is selected?
4. How does this connect to the lead journey?
5. What trigger issue could the Orchestrator inspect?

## Milestone 3: Add Basic Actions

### Steps

1. Add an action to apply the Tag `ghl-test-lead`.
2. Add an action to create or update an Opportunity.
3. Select `MJ Test Pipeline`.
4. Select the stage `New Lead`.
5. Save the actions.
6. Review the full Workflow before publishing.

### Expected Result

The Workflow has a trigger and actions to tag the Contact and create or update an Opportunity.

### Milestone Summary

In this milestone, you learned that:

- Workflow Actions perform the work after the trigger fires.
- A Workflow can apply a Tag.
- A Workflow can create or update an Opportunity in a Pipeline.

### Remember This in GHL Terms

A Workflow Action can apply a Tag or create an Opportunity. This connects the Contact to the Pipeline journey.

### Quick Self-Check

1. What actions did I add?
2. Which Tag is applied?
3. Which Pipeline and stage are used?
4. What could happen if the wrong stage is selected?
5. What should the Orchestrator explain here?

## Milestone 4: Test the Workflow

### Steps

1. Publish the Workflow only if you are in a safe test workspace.
2. Submit the `MJ Test Lead Form` again with safe test data.
3. Go to Contacts and open the new or updated Contact.
4. Confirm the Tag was added.
5. Go to Opportunities.
6. Confirm an Opportunity appears in `MJ Test Pipeline` under `New Lead`.

### Expected Result

The Form submission triggered the Workflow, applied the Tag, and created or updated an Opportunity.

### Milestone Summary

In this milestone, you learned that:

- Testing confirms whether the Workflow actually works.
- The Contact should show the Tag.
- The Opportunity should appear in the correct Pipeline stage.

### Remember This in GHL Terms

A Contact submitted the Form. The Workflow applied a Tag and created or updated an Opportunity in the Pipeline.

### Quick Self-Check

1. Did the Workflow trigger?
2. Was the Tag applied?
3. Was the Opportunity created or updated?
4. Where did I confirm the result?
5. What troubleshooting path should the Orchestrator guide?

## Memory Checkpoint

Answer without looking:

1. What is a Workflow?
2. What is a Workflow Trigger?
3. What is a Workflow Action?
4. What did this Workflow do?
5. What could fail in this setup?
6. How should the Orchestrator inspect the failure?

## Learning Note to Save

Update `LEARNING_STATUS.md` using the standard learning note format.
