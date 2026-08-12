# QBitFlow Fee Validation

## Business Rule

The documented platform fee for the tested payment flow is 1.5%.

## Example

For a payment amount of 100 USD:

- Customer payment: 100 USD
- Platform fee: 1.50 USD
- Expected merchant settlement: 98.50 USD

## Validation Scenarios

- Verify that the fee is calculated correctly.
- Verify that the fee is deducted exactly once.
- Verify that the merchant receives the expected net amount.
- Verify that rounding behavior is consistent for different payment amounts.
- Verify that the fee is reflected correctly in relevant transaction information.

## Risk

An incorrect fee calculation can directly affect merchant settlement and therefore represents a high-value business-rule test.

## QA Note

The actual implementation should be validated against the current product requirements and observed transaction data.
