
# SauceDemo - Manual Test Execution Report

## Project Information

- Application: SauceDemo
- URL: https://www.saucedemo.com/
- Test Type: Manual Functional Testing
- Test Environment: Web Browser
- QA Analyst: Ana Paula Pelegrini
- Execution Status: Completed

## Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases | 8 |
| Executed | 8 |
| Passed | 8 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

## Test Execution Results

| Test ID | Test Scenario | Status |
|---|---|---|
| TC-001 | Login with valid credentials | PASS |
| TC-002 | Login with invalid password | PASS |
| TC-003 | Login with empty fields | PASS |
| TC-004 | Add product to cart | PASS |
| TC-005 | Remove product from cart | PASS |
| TC-006 | Sort products by price (low to high) | PASS |
| TC-007 | Complete checkout with valid information | PASS |
| TC-008 | Checkout with missing required information | PASS |

## Observations

During the initial execution of TC-001, an unexpected
redirection was observed after pasting the password,
without explicitly clicking the Login button.

The behavior could not be reproduced during subsequent
attempts, including another test using copy and paste.

The standard login flow was successfully executed
afterward.

No confirmed defect was identified.

## Conclusion

All eight documented manual test cases passed during
the completed execution cycle.

The tested login, cart, sorting, and checkout
functionalities behaved as expected during the
successful test executions.

This report documents the observed results and does
not represent exhaustive application coverage.
