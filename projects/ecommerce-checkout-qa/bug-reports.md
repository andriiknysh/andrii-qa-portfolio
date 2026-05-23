# E-commerce Checkout Bug Reports

## BUG-001: Checkout Allows Continue With Missing Phone Number

**Severity:** Medium

**Environment:** Desktop browser, sample checkout flow

**Steps to Reproduce:**

1. Add a product to the cart.
2. Open checkout.
3. Enter name, email, and address.
4. Leave phone number blank.
5. Select continue.

**Expected Result:** The form should show a clear required-field message for phone number.

**Actual Result:** Checkout continues to the next step without warning.

**Impact:** Support may need to contact the customer later if delivery information is incomplete.

**Suggested Fix:** Require phone validation before continuing to payment.
