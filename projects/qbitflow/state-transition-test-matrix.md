# QBitFlow State Transition Test Matrix

| Current State | Event | Expected State |
|---|---|---|
| Created | Checkout opened | Awaiting Payment |
| Awaiting Payment | Valid payment detected | Payment Detected |
| Payment Detected | Confirmation begins | Confirming |
| Confirming | Required confirmation received | Confirmed |
| Confirmed | Settlement completed | Settled |
| Awaiting Payment | Session expires | Expired |
| Payment Detected | Processing failure | Failed |

## QA Focus

Validate that valid transitions occur as expected and that invalid or contradictory transitions are prevented.

## Important

The actual application state model should be compared against current product requirements and observed behavior.
