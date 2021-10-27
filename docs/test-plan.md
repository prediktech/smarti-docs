# Test Plan
The plan that is our core guide to what needs to be tested. Check out our [testing approach](/concepts/testing/testing-approach-fe.html) if you would like to know more about how we test and why.

Each item listed below is a "Feature" which contains multiple "Scenarios". The scenarios cover different aspects of the user journey. For example a feature for Accountable will contain a scenario for each of the permissions and system settings that affect the user.

## Persona user journeys

|Persona|Feature File|Description|Implemented|
|-|-|-|-|
|Accountable|accountableBasic.feature|Logging in as the accountable user validate that they are able to do assigned submissions. Doing a submission includes answering questions, adding comments, evidence and actions and changing the status of the submission.|<input type="checkbox" checked></input>|
|Accountable|Actions| Accountable users are able to create and manage any actions associated with their submissions. Test CRUD operations of actions as well as closing and reopening |<input type="checkbox"></input>|
| Assessor | assessorPermissions.feature | This feature will test that an assessor user has all the required permissions depending on the system configuration. Test permissions in relation to reviewing submissions, interacting with evidence, actions and comments, adjusting scores, status changes and closing versions |<input type="checkbox"></input>|
| Planner | Planner Core | description |<input type="checkbox"></input>|
| Feedback | feedbackSubmit.feature | Test that if a user is requested to give feedback they are able to access that submissions and test the limited permissions that should be enforced for a feedback user. Test the feedback submit mechanism. |<input type="checkbox"></input>|
| Administrator | System User Management | description |<input type="checkbox"></input>|
| Administrator | System Settings | description |<input type="checkbox"></input>|
| Administrator | Site User and Team Management | description |<input type="checkbox"></input>|
| Administrator | Assessment Management | description |<input type="checkbox"></input>|
| Administrator | Core Question Management | description |<input type="checkbox"></input>|
| Administrator | Assessment Scheduling | description |<input type="checkbox"></input>|

Additional test journeys need to be discussed and approved before they are added.




