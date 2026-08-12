# QBitFlow Requirements and Business Rules

## Purpose

This document captures the key requirements and business rules identified during QA analysis of the QBitFlow one-time payment flow.

## Payment Flow

The core flow involves:

1. Merchant creates or presents a payment request.
2. Customer opens the checkout experience.
3. Customer selects or provides a supported payment method.
4. Payment is submitted on the supported network.
5. The payment is detected and confirmed.
6. Settlement is processed.
7. The merchant receives the resulting funds in the designated wallet.
8. Relevant payment information is reflected in the dashboard.

## Key Business Rules

- Checkout sessions have a defined expiration period.
- The documented platform fee is 1.5%.
- The platform fee is deducted during settlement.
- Supported networks and assets must match the documented configuration.
- Settlement should result in the expected merchant amount.
- Payment confirmation and settlement should produce a consistent final state.

## QA Focus

Each business rule should be validated independently and also as part of the complete payment journey.

## Risk

Payment calculation, confirmation, and settlement errors can directly affect customer funds and merchant expectations and therefore require high-priority validation.
