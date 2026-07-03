# GoRest API Assignment (Postman)

## Prerequisites

- Postman installed
- GoRest account
- Valid Bearer Token

## Setup

1. Import `GoRest_API_Assignment.postman_collection.json`.
2. Import `GoRest.postman_environment.json`.
3. Open the imported environment and update the `token` variable with your personal GoRest Bearer Token.
4. Select the **GoRest Environment** before running the collection.

## Test Scenarios

### Scenario 1
- Create a new user using `POST /users`
- Verify:
  - HTTP Status = 201
  - Returned `id` is numeric
  - User details are created successfully

### Scenario 2
- Retrieve users using `GET /users`
- Verify:
  - HTTP Status = 200
  - The first user's `status` is either `active` or `inactive`

## Execution

Open the collection and click **Run**, or use the **Collection Runner** to execute all requests.