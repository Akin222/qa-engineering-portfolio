# QBitFlow Negative Test Matrix

| Scenario | Expected Behavior |
|---|---|
| Missing payment information | Request rejected appropriately |
| Unsupported network | Payment not incorrectly accepted |
| Unsupported asset | Payment not incorrectly accepted |
| Invalid amount | Appropriate validation |
| Expired session | Session treated as expired |
| Duplicate submission | Duplicate processing prevented |
| Failed confirmation | Payment not shown as successfully settled |
| API failure | Useful error state presented |

## QA Principle

Negative testing validates how the product behaves when users, integrations, or external systems provide unexpected conditions.
