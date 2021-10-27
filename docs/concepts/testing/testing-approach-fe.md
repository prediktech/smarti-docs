# SMARTi App FE Test Approach
Testing is great it has many benefits like better code quality and ensuring that nothing gets broken when new features are added. Like all good things in life there is also a cost in the case of testing it is the cost of additional time and effort to maintain the tests.

Each application needs to balance these costs and benefits.

For the Frontend of SMARTi we have adopted a strategy of trying to cover the core user journeys through e2e (end to end tests). The intent is to maintain a minimal set of tests that cover the core of the application.

This is not the only tests we write but they are the core. As features are developed that address edge cases we will also add specific tests to deal with those cases as they are not part of a core journey.

## Tools
We use the following tools to assist in testing
- cypress.io
- cucumber with gerkin scripts
- jest for unit tests (not generally used)

## How to decide what to test or where it goes
If a change is going to be made to code it has originated either through product improvement or a bug has been found.
The tester should as the following questions:
- does this change an existing code journey?
  - note: review the TEST_PLAN.md for the core journey tests