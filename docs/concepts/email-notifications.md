# Email notifications

Regular emails updates are able to be configured. These emails provide a summary of the information in SMART!. 
Email types are:
- Accountable Weekly Digest
- Action Modifications
- Approval Workflow

```NB: Only the system admin can configure email notifications.```

## Email Templates
The smart! system uses email templates for sending email. At the moment these are deployed with the system and development work is required to deploy new templates.

**In future clients will be able to upload new templates to the azure storage container.** 

## Acountable Weekly Digest
Email is configured to be sent as a weekly overview of the state of submissions and actions for each accountable person.

## Event Emails
Both Action changes and workflow changes are event based notifications. This means when this event occurs it is added to an event queue, periodically the system will attempt to clear the queue and send emails based on the events that have occurred.

The default system check period is every 30 seconds. This means if you set the delay period to "Immediate" there may still be a 30 second delay.

It is recommended to have a longer delay to avoid spamming your users. The email will then group all occurrences of an event over that period of time into a single email. 

### Action Email
This email will contain a list of actions that have changed within the send delay period.


### Approval Workflow Email
This email contains