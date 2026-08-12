# QBitFlow Wallet Validation

## Objective

Validate wallet-related behavior throughout the payment and settlement workflow.

## Checks

- Verify the expected merchant wallet is associated with the payment.
- Verify wallet information is displayed consistently.
- Verify settlement is directed to the expected destination.
- Verify invalid wallet configuration is handled appropriately.
- Verify wallet information is not incorrectly exposed or modified.

## Evidence

Where blockchain evidence is available, transaction references may be used to support validation.

## Security

Private keys, seed phrases, authentication credentials, and other secrets must never be stored in the repository.

## QA Risk

Incorrect wallet handling can result in failed settlement or funds being associated with an unexpected destination.
