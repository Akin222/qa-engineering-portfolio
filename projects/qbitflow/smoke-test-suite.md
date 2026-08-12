# QBitFlow Smoke Test Suite

## Objective

Smoke testing provides a rapid assessment of whether the core payment workflow is stable enough for deeper testing.

## Smoke Scenarios

### SMK-001

Verify that the application is accessible.

### SMK-002

Verify that a valid payment request can be created.

### SMK-003

Verify that checkout can be opened.

### SMK-004

Verify that a supported payment can be initiated.

### SMK-005

Verify that payment status updates appropriately.

### SMK-006

Verify that successful payment can progress toward settlement.

### SMK-007

Verify that merchant-facing payment information is available.

## Exit Consideration

If a critical smoke scenario fails, deeper testing may need to be paused until the blocking issue is understood.

## QA Principle

Smoke testing is intended to quickly identify major blockers, not replace comprehensive testing.
