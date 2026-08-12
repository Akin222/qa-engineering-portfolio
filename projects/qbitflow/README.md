# QBitFlow — QA Project

## Project Overview

QBitFlow is a payment platform designed to allow merchants to accept stablecoin payments and receive settlement directly into their designated wallet.

This QA project focuses on the manual testing of the one-time payment flow and associated dashboard behavior.

## Testing Focus

The testing effort considers:

- Payment creation
- Checkout behavior
- Supported blockchain networks
- Supported payment assets
- Payment confirmation
- Settlement behavior
- Platform fee handling
- Merchant wallet settlement
- Payment session expiry
- Dashboard information
- Error handling
- User experience

## QA Objective

The objective is to validate the expected customer and merchant journeys, identify functional inconsistencies, evaluate business-rule compliance, and communicate quality risks clearly.

## Testing Approach

Testing is organized around requirements analysis, risk identification, test scenario design, functional validation, exploratory testing, defect reporting, and regression considerations.

## Important Business Rules

The documented requirements include rules concerning payment expiry, platform fees, supported networks, supported assets, and settlement behavior.

These rules should be validated explicitly because failures can affect both the merchant's expected funds and the customer's payment experience.

## QA Perspective

The project demonstrates testing of a more complex payment workflow where UI behavior, business rules, blockchain transactions, and settlement outcomes can intersect.
