This pack contains workflow for mocking Jira and pagerduty incidents.

Workflow follows as 
    - pagerduty ticket would be created with Webhook data request.
    - Based on data from Pagerduty ticket, create Jira ticket
    - Based on Jira ticket, update pagerduty ticket
    - Close alerts based on payload