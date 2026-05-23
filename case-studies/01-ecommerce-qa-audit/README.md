# Case Study 01: E-commerce QA Audit

## Overview

This is a limited manual QA review of [Automation Exercise](https://automationexercise.com), a public demo e-commerce practice site. The review covers the observed browse, product detail, cart, signup gate, demo signup, checkout, payment, and order-confirmation path.

## Case Study Details

- **Site tested:** https://automationexercise.com
- **Test type:** Manual functional QA plus exploratory QA notes
- **Scope:** E-commerce browse/cart/signup/checkout/order confirmation path
- **Evidence:** Screenshots `01` through `10` in [screenshots](screenshots/README.md)
- **Recording:** Not available
- **Status:** Evidence-backed case study, limited scope

## Evidence Status

Real browser evidence has been collected for the tested happy path. No confirmed functional bugs were found in that tested path. Two low-severity usability observations and one ad-distraction observation were recorded for follow-up.

## Executed Flows

| Flow | Status | Evidence |
| --- | --- | --- |
| Homepage -> products | Pass | `01-homepage.png`, `02-products.png` |
| Product detail | Pass | `03-product-detail.png` |
| Add to cart | Pass | `04-cart.png` |
| Checkout signup wall | Pass | `05-checkout-signup-wall.png` |
| Signup negative validation | Needs Review | `06-signup-invalid-data.png` |
| Signup valid demo path | Pass | `07-signup-valid-data.png` |
| Checkout/payment/order confirmation | Pass with usability note | `08-checkout-form.png`, `09-payment-screen.png`, `10-confirmation-or-blocked-step.png` |

## Deliverables

- [Test plan](test-plan.md)
- [Environment matrix](environment.md)
- [Test cases](test-cases.md)
- [Exploratory notes](exploratory-notes.md)
- [Bug reports](bug-reports.md)
- [Usability findings](usability-findings.md)
- [Release-readiness summary](release-readiness-summary.md)
- [Evidence log](evidence.md)
- [Screenshots folder](screenshots/README.md)

## Remaining Evidence Gaps

- No Loom recording was captured.
- Quantity update behavior was not tested.
- Remove-item behavior was not tested.
- Existing-login behavior was not tested.
- Mobile responsiveness was not tested.
- Invoice download was not tested.
- Cross-browser coverage was not tested.
- Console errors were observed but not investigated as user-facing issues.
