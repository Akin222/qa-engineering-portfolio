# QBitFlow Payment Flow Scenarios

## Core Scenarios

### QBF-T001 — Create Payment

Verify that a merchant can create a valid one-time payment request.

### QBF-T002 — Open Checkout

Verify that a customer can open a valid payment checkout.

### QBF-T003 — Supported Payment

Verify that a valid payment using a supported network and asset is accepted.

### QBF-T004 — Payment Detection

Verify that a submitted payment is detected correctly.

### QBF-T005 — Payment Confirmation

Verify that a confirmed payment transitions to the expected state.

### QBF-T006 — Settlement

Verify that a successfully confirmed payment results in the expected merchant settlement.

### QBF-T007 — Payment Expiry

Verify that an expired checkout session cannot be treated as an active payment request.

### QBF-T008 — Invalid Payment

Verify that an invalid or unsupported payment is handled appropriately.

## QA Principle

Payment scenarios should validate both the visible application behavior and the resulting payment state where evidence is available.
