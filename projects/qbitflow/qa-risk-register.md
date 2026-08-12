# QBitFlow QA Risk Register

## Purpose

The risk register prioritizes testing based on potential impact and likelihood of failure.

| Risk | Impact | Priority | QA Response |
|---|---|---|---|
| Incorrect payment amount | Financial | Critical | Dedicated functional testing |
| Incorrect fee calculation | Financial | Critical | Business-rule validation |
| Incorrect settlement | Financial | Critical | End-to-end validation |
| Wrong network or asset | High | High | Compatibility testing |
| Incorrect payment status | High | High | State-transition testing |
| Expired payment mishandled | High | High | Boundary and negative testing |
| API failure | Medium/High | High | API and integration testing |
| UI usability issue | Medium | Medium | Usability testing |

## Risk-Based Principle

Testing effort should be concentrated on areas where failure could cause the greatest customer, merchant, financial, or operational impact.

## Status

This register represents QA planning and risk assessment. Actual risk ratings may change as test evidence becomes available.
