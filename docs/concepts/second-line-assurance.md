# Second Line Assurance
There are typically three levels of assurance:   
- **Level 1** is where the business (or site) verifies their own systems.  
- **Level 2** is where a Group function (internal to the greater business but external from the site) will come and perform a review on specific aspects that are considered critical from a business risk and continuity perspective.   
- **Level 3** is when an external auditor comes in and performs the assessment.

Second line of assurance questions are related to statutory, high risk, or critical requirements. These questions are identified by the ![Image](../assets/screenshots/jobs/secondLineIcon.png) icon.

![Image](../assets/screenshots/jobs/question.png)

When answering second line assurance questions the system can be configured to prompt the user to provide either evidence or actions based on the answer provided. If the business rules are not met the submission will be highlighted as **non-conforming**.

_See also [Maturity and Criticality](/jobs/maturity-and-criticality.html)._

## Configuration
When configuring a submission there is an option to choose the non-compliance prompt. (None, Second Line Only, All non-compliance). 

If second line only is chosen, a prompt will be shown if any second line question is not answered with actions or evidence, no matter the maturity level.

Selecting the "ALL" option means that the system business rule will be used to determine if a non-conformance has occurred. By default the system business rule is configured for Maturity Level 1 and below. This will then display non-conformance discrepancies for all questions on those maturity levels, including second line assurance questions. 

## Discrepancy Errors and Warning
These non-conformance items are referred to as "discrepancies" and there are four types of discrepancy.

- **Statutory Error:** A second line assurance question has been answered with a "No" but no _Action_ has been provided to detail how the gap will be closed.
- **Error:** A non second line assurance question has been answered with a "No" but no _Action_ has been provided to detail how the gap will be closed. 

![Image](../assets/screenshots/jobs/errorIcon.png)

- **Statutory Warning:** A second line assurance question has been answered with a "Yes" but no _Evidence_ has been provided to prove compliance.
- **Warning:** A non second line assurance question has been answered with a "Yes" but no _Evidence_ has been provided to prove compliance.

![Image](../assets/screenshots/jobs/warningIcon.png)

These discrepancy indicators are an easy way during a review of a submission to focus on areas that may need to be addressed. If errors are present there is a high likelihood that the submission will not be approved.