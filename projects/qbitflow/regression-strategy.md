# QBitFlow Regression Strategy

## Objective

Regression testing verifies that changes to the payment workflow do not unintentionally break previously functioning behavior.

## Regression Scope

High-priority regression areas include:

- Payment creation
- Checkout
- Supported networks
- Supported assets
- Payment confirmation
- Payment status
- Fee calculation
- Payment expiry
- Merchant settlement
- Dashboard information

## Regression Triggers

Regression testing should be considered after changes affecting:

- Payment processing
- Fee logic
- Checkout behavior
- Network or asset support
- Settlement logic
- API integrations
- Payment status handling

## Risk-Based Priority

Critical payment and settlement paths should receive priority before lower-risk UI changes.

## QA Principle

Regression testing provides confidence that fixes and new changes have not introduced defects into existing functionality.
