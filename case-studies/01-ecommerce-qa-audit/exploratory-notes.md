# Exploratory Testing Notes

## Session Details

- Tested URL: https://automationexercise.com
- Date: 2026-05-23, approximately 15:35-15:42 EDT
- Environment: Google Chrome 148.0.7778.179 on macOS 26.4.1, viewport 1728 x 944
- Session goal: Limited first-time-user e-commerce checkout audit

## Charters

1. Explore product discovery and whether a new user can understand what is for sale.
2. Explore cart behavior and whether price, quantity, and total are clear for one item.
3. Explore signup/login friction before checkout.
4. Explore checkout validation and whether errors help the user recover.
5. Explore payment-form behavior using fake/demo data only.

## Flow Notes

| Area | Observation | Risk | Follow-Up |
| --- | --- | --- | --- |
| Homepage/products | Homepage, navigation, product listing, and product detail page loaded successfully. | Low for tested path. | Add mobile and secondary-browser checks later. |
| Cart | `Blue Top` added to cart and showed price `Rs. 500`, quantity `1`, total `Rs. 500`. | Quantity editing was not tested. | Test quantity update and remove-item behavior. |
| Checkout gate | Unauthenticated checkout showed clear register/login gate and retained cart item. | Low for tested path. | Test existing-login path later. |
| Signup validation | Invalid email did not advance, but captured page did not show persistent inline validation text. | Low usability concern; needs confirmation. | Re-test manually and capture browser-native validation if visible. |
| Demo signup | Demo account creation succeeded without email or phone verification. | Low for tested path. | Demo account was not deleted because deletion was not authorized. |
| Checkout review | Checkout displayed demo delivery/billing address and accurate order summary for one item. | Limited coverage. | Test multiple items, quantity changes, and address validation. |
| Payment | Empty required payment fields were blocked by browser validation. Fake/demo payment data was accepted by the demo site. | Low usability concern around persistent inline payment validation. | Confirm whether browser-native-only validation is acceptable for this demo site. |
| Confirmation | Demo order confirmation displayed `Order Placed!` and invoice link. | Invoice download not tested. | Test invoice only if approved. |

## Questions To Resolve

- Does quantity update work correctly for cart items?
- Does remove-item behavior work correctly?
- Does login with an existing demo account work correctly?
- Is the checkout flow usable on mobile?
- Are console errors user-impacting or only third-party/ad noise?
- Does invoice download work and avoid private data exposure?
