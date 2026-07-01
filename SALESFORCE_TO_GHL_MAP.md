# Salesforce to HighLevel CRM Map

Use this only as a translation aid. In exercise notes, write the HighLevel term first.

| Salesforce Reference | HighLevel Term | Notes |
|---|---|---|
| Org | Agency account / Sub-account / Location | HighLevel often separates agency-level management from client/business locations |
| Lead | Contact | HighLevel is contact-centric; a lead is usually represented as a Contact |
| Contact | Contact | Similar, but HighLevel Contacts are often used more broadly |
| Account | Contact company details / Business information | HighLevel does not always use a Salesforce-style Account object |
| Opportunity | Opportunity | Similar lead/deal tracking concept |
| Sales Process | Pipeline | Pipeline contains the stages |
| Stage | Pipeline Stage | Stage inside a Pipeline |
| Flow | Workflow | Main automation builder |
| Flow Trigger | Workflow Trigger | Event that starts automation |
| Flow Action | Workflow Action | Step inside automation |
| Field | Custom Field | Extra stored information |
| Campaign | Workflow / Campaign / Funnel | Depends on context |
| Web-to-Lead | Form / Survey / Funnel | Lead capture tools |
| Activity Timeline | Conversations / Contact activity | Communication and history area |
| Event | Appointment | Booked meeting |
| Salesforce Scheduler | Calendar | Booking engine |
| Change Set / Metadata package | Snapshot | Reusable setup/configuration template |
| Connected App | Integration / OAuth app | External app connection |
| API callout | Webhook / API request | Technical integration action |

## Rule

Do not document a HighLevel exercise as if it happened in Salesforce.

Correct:

> The Contact submitted a Form. The Workflow applied a Tag and created an Opportunity in the Pipeline.

Incorrect:

> The Lead submitted Web-to-Lead. The Flow updated the Opportunity Stage.
