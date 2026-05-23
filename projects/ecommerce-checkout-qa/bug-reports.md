# E-commerce Checkout Bug Reports

These are polished sample bug-report formats for the real checkout project. They should be replaced or updated with actual findings after a tested URL, date, environment, screenshots, and Loom link are available.

## BUG-001: Required Signup Error Message Is Not Clear

**Severity:** Medium

**Priority:** High

**Environment:** [browser, OS, device]

**Steps to Reproduce:**

1. Open the tested e-commerce site.
2. Add a product to the cart.
3. Start checkout or account signup.
4. Leave required fields blank.
5. Select the continue or submit button.

**Expected Result:** Each missing required field should show a clear message explaining what the user needs to fix.

**Actual Result:** To be recorded during real test.

**Impact:** A first-time user may not understand why checkout is blocked, which can increase abandonment and support questions.

**Suggested Fix:** Show specific required-field validation messages near the affected fields and keep them visible until corrected.

**Evidence:** To be added after real testing.

## BUG-002: Cart Total Does Not Update Clearly After Quantity Change

**Severity:** Medium

**Priority:** High

**Environment:** [browser, OS, device]

**Steps to Reproduce:**

1. Open the tested e-commerce site.
2. Add a product to the cart.
3. Change the quantity from 1 to 2.
4. Review item total, subtotal, and cart summary.

**Expected Result:** Quantity, item total, subtotal, and cart summary should update clearly without a page refresh problem or stale value.

**Actual Result:** To be recorded during real test.

**Impact:** Users may lose trust in pricing if cart totals are unclear or delayed.

**Suggested Fix:** Update the subtotal immediately after quantity changes and show a clear loading or confirmation state if recalculation takes time.

**Evidence:** To be added after real testing.

## BUG-003: Payment Validation Does Not Explain Invalid Input

**Severity:** Medium

**Priority:** High

**Environment:** [browser, OS, device]

**Steps to Reproduce:**

1. Add a product to the cart.
2. Complete checkout steps until payment.
3. Enter incomplete or invalid sample payment data.
4. Submit the payment form.

**Expected Result:** The payment form should explain which fields are invalid and how the user can correct them.

**Actual Result:** To be recorded during real test.

**Impact:** Users may not know whether payment failed because of their input, site behavior, or a system problem.

**Suggested Fix:** Display field-level validation messages for card number, expiration date, CVV, and billing details.

**Evidence:** To be added after real testing.
