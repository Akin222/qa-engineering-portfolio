# QBitFlow Observability Checklist

## Objective

Define useful signals for investigating payment-flow failures.

## Application Signals

- API errors
- Application exceptions
- Payment processing failures
- State transition errors
- Settlement failures

## Client Signals

- Console errors
- Failed network requests
- Unexpected UI states
- Loading failures

## Transaction Signals

- Payment identifier
- Transaction identifier
- Network
- Asset
- Confirmation state
- Settlement state

## Security

Evidence collection must exclude private keys, passwords, tokens, and other sensitive information.

## QA Principle

Good observability makes defects easier to reproduce, investigate, and communicate.
