# QBitFlow API Test Scenarios

## Objective

Define API-level scenarios supporting the one-time payment workflow.

## Scenarios

### API-001 — Valid Request

Verify that a valid request produces the expected successful response.

### API-002 — Missing Required Field

Verify that a request missing a required field is rejected appropriately.

### API-003 — Invalid Value

Verify that invalid input values are handled correctly.

### API-004 — Payment Status

Verify that the payment status endpoint returns the expected state.

### API-005 — Invalid Identifier

Verify that an invalid payment identifier is handled appropriately.

### API-006 — Error Response

Verify that API failures return an appropriate status and useful error information without exposing sensitive implementation details.

## QA Principle

API testing should validate both technical correctness and alignment with the underlying business requirements.
