# QBitFlow Supported Networks and Assets

## Scope

The test environment requirements identified during QA analysis include support for the documented blockchain networks and payment assets.

## Networks

The test scenarios considered:

- Base
- Ethereum
- Solana

Where testnet environments are used, the corresponding testnet configuration must be verified before execution.

## Payment Assets

Testing should distinguish between:

- Native network tokens
- USDC

The exact supported combinations should be validated against the current product documentation before execution.

## QA Checks

Verify that:

- Supported networks are presented correctly.
- Supported assets are accepted.
- Unsupported combinations are rejected appropriately.
- Network selection remains consistent throughout checkout.
- The final settlement corresponds to the selected payment configuration.

## Risk

Incorrect network or asset handling can result in failed payments, confusing user experiences, or incorrect settlement behavior.
