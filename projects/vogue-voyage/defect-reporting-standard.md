# Defect Reporting Standard

## Purpose

Defects should be documented clearly enough that another team member can understand the problem, reproduce it, assess its impact, and verify the eventual fix.

## Defect Information

A defect report should contain:

- Clear defect title
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Supporting evidence
- Reproduction status
- Retest status

## Reproduction

Before reporting a defect, the observed behavior should be reproduced where practical to reduce the risk of reporting intermittent or misunderstood behavior.

## Expected vs Actual Behavior

The expected result should describe the behavior required by the product or user flow.

The actual result should describe exactly what occurred during testing without assumptions about the underlying cause.

## Severity and Priority

Severity describes the impact of the defect on the system or user experience.

Priority describes how urgently the issue should be addressed based on business impact, user impact, risk, and release considerations.

## Retesting

After a defect is reported as fixed, the original reproduction steps should be executed again to verify the fix.

Relevant regression checks should also be performed when the change could affect related functionality.
