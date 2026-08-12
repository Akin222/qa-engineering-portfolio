# QBitFlow Payment State Model

## Purpose

Define the expected conceptual progression of a payment through the system.

## State Flow

Created
? Awaiting Payment
? Payment Detected
? Confirming
? Confirmed
? Settled

Alternative outcomes may include:

Awaiting Payment
? Expired

Payment Detected
? Failed

Confirming
? Failed

## QA Validation

Test scenarios should verify that:

- Valid transitions occur correctly.
- Invalid transitions are prevented.
- Failed payments are not shown as settled.
- Expired sessions are not treated as active.
- Settlement occurs only after the required confirmation state.

## Risk

Incorrect state transitions can create conflicting information between customer-facing and merchant-facing interfaces.
