# E-commerce QA Audit Evidence

## Tested Site

https://automationexercise.com

## Date Tested

2026-05-23, approximately 15:35-15:42 EDT

## Environment

- Browser: Google Chrome 148.0.7778.179
- OS: macOS 26.4.1
- Device: Mac, arm64
- Screen size: Viewport 1728 x 944; screen 1728 x 1117; device pixel ratio 2
- Tester: Andrii Knysh
- Evidence executor: Codex browser session under operator authorization

## Loom Link

Not available. No Loom recording was captured in this run.

## Screenshots

| File | Flow/step shown | Description |
| --- | --- | --- |
| `screenshots/01-homepage.png` | Homepage | Homepage, main navigation, featured items, category/brand sections |
| `screenshots/02-products.png` | Products | Products page, search field, product listing, category/brand filters |
| `screenshots/03-product-detail.png` | Product detail | `Blue Top` product detail page with price, quantity, availability, condition, brand, and add-to-cart button |
| `screenshots/04-cart.png` | Cart | Cart page showing `Blue Top`, price `Rs. 500`, quantity `1`, total `Rs. 500` |
| `screenshots/05-checkout-signup-wall.png` | Checkout signup wall | Checkout gate requiring register/login before checkout |
| `screenshots/06-signup-invalid-data.png` | Signup invalid data | Signup form after invalid email attempt with no persistent inline error visible in captured page |
| `screenshots/07-signup-valid-data.png` | Signup valid demo path | Account-created success page after demo account creation |
| `screenshots/08-checkout-form.png` | Checkout review | Checkout address details and order summary using demo address data |
| `screenshots/09-payment-screen.png` | Payment screen | Payment page fields for card details |
| `screenshots/10-confirmation-or-blocked-step.png` | Order confirmation | Demo order confirmation page showing `Order Placed!` |

## Run Summary

| Metric | Count |
| --- | --- |
| Test cases run | 11 executed/partially executed checks |
| Passed | 8 |
| Failed | 0 |
| Blocked | 0 |
| Needs review | 3 |
| Not tested | 10 |

## Top 3 Risks

1. This run is not enough evidence for a full release recommendation.
2. Signup and payment validation behavior needs confirmation because persistent inline guidance was not visible in captured page content.
3. Mobile, cross-browser, quantity update, remove item, existing login, and invoice download remain untested.

## Final Recommendation

Conditional pass for the limited tested happy path. Additional testing is required before any broader release-readiness claim.

## Redaction/Privacy Note

Use demo data only. Do not publish passwords, personal data, payment data, private account information, addresses, phone numbers, email inboxes, order history, or unredacted identifiers.

This run used throwaway/demo data only. No real payment, private account, private inbox, or real purchase was used. The demo account was not deleted because deletion was not authorized.
