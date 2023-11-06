# Test_Assignment_3

## Which strategies we plan to use
### Unit Testing:
We plan on using test doubles (mocks, stubs, etc.) to isolate individual components or units and test them in isolation. This is particularly useful for testing React components and TypeScript functions.
### Integration Testing:
We're testing the interaction between different components or modules within our project, especially when we're planning on using the microservice architecture.
### Database Integration Testing:
For our MSSQL database, we're setting up integration tests to verify data storage, retrieval, and manipulation.

## How we plan to setup our test environment
### For React/TypeScript frontend:
Use testing libraries such as Jest and React Testing Library for unit and integration tests.
### For MSSQL database:
We're planning to uuse a testing database or create a dedicated testing schema within our database to prevent data corruption during testing.
### CI
If we have the time and we would like to implement continuous integration environment for automated testing and deployment.

## How The plan is intended to work together with the chosen development methodologies
Our testing plan is intented to work almost seamlessly with Scrum. We're doing this bu sensuring that testing activities are integrated through the Scrum procress.

## What measurements we're going to be using for measuring progression on our tests and project.
### Code Coverage:
This metric measures the percentage of our codebase that is covered by tests. It helps ensure that our tests are comprehensive.
### Acceptance Criteria Fulfillment:
Track how well the acceptance criteria for user stories are being met by testing activities.
