# QBitFlow Test Data Management

## Objective

Define safe and reproducible test data for payment-flow validation.

## Test Data Categories

- Valid payment amounts
- Boundary amounts
- Invalid amounts
- Supported networks
- Unsupported networks
- Supported assets
- Unsupported assets
- Active payment sessions
- Expired payment sessions
- Test wallet addresses
- Transaction references

## Data Requirements

Test data should:

- Be reproducible.
- Represent realistic scenarios.
- Avoid production credentials.
- Avoid private keys and secrets.
- Support positive and negative testing.
- Allow comparison between expected and observed results.

## Sensitive Data

Private keys, passwords, authentication tokens, and other credentials must never be committed to the repository.

## QA Principle

Good test data allows meaningful scenarios to be executed consistently while protecting sensitive information.
