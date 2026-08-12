# QBitFlow Negative Payment Scenarios

## Objective

Negative testing evaluates how the payment flow behaves when invalid, unexpected, incomplete, or unsupported conditions occur.

## Scenarios

### QBF-NEG-001 — Unsupported Network

Verify that an unsupported network cannot be processed as a valid payment.

### QBF-NEG-002 — Unsupported Asset

Verify that an unsupported payment asset is rejected or handled according to the expected behavior.

### QBF-NEG-003 — Insufficient Payment

Verify that a payment below the required amount is not incorrectly treated as fully settled.

### QBF-NEG-004 — Expired Checkout

Verify that payment attempts against an expired checkout are handled correctly.

### QBF-NEG-005 — Duplicate Payment

Verify that repeated payment activity does not incorrectly create duplicate settlement.

### QBF-NEG-006 — Failed Confirmation

Verify that a payment that does not reach the required confirmation state is not incorrectly represented as successful.

### QBF-NEG-007 — Invalid Payment State

Verify that inconsistent or unexpected payment states are handled without incorrectly confirming settlement.

## QA Risk

Negative testing is particularly important for payment systems because incorrect handling can affect financial outcomes and user trust.
