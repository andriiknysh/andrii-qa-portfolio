# E-commerce Checkout Test Cases

| ID | Scenario | Preconditions | Steps | Expected Result | Actual Result | Status | Priority |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TC-001 | Open homepage | Browser is open and network is available | Navigate to the tested URL | Homepage loads without errors and main navigation is visible | To be recorded during real test | Not Run | High |
| TC-002 | View product listing | Homepage is loaded | Open a product category or product list | Products, prices, and product links are visible | To be recorded during real test | Not Run | High |
| TC-003 | Open product detail page | Product listing is visible | Select one product | Product page shows name, price, image, and add-to-cart option | To be recorded during real test | Not Run | High |
| TC-004 | Add product to cart | Product detail page is open | Select add to cart | Product is added to cart and cart count or confirmation updates | To be recorded during real test | Not Run | High |
| TC-005 | Update cart quantity | Product is in cart | Change quantity from 1 to 2 and review subtotal | Quantity and subtotal update correctly | To be recorded during real test | Not Run | High |
| TC-006 | Remove cart item | Product is in cart | Remove the product from the cart | Cart updates and empty-cart state is clear | To be recorded during real test | Not Run | Medium |
| TC-007 | Required signup fields | Checkout or signup form is open | Submit the form with required fields blank | Required-field errors appear clearly beside or near the missing fields | To be recorded during real test | Not Run | High |
| TC-008 | Invalid email format | Signup or checkout form is open | Enter an invalid email address and submit | User sees a clear email-format validation message | To be recorded during real test | Not Run | Medium |
| TC-009 | Shipping information entry | Checkout form is open | Enter valid shipping information and continue | Shipping information is accepted and the next checkout step loads | To be recorded during real test | Not Run | High |
| TC-010 | Empty payment fields | Payment section is open | Submit payment section with empty required fields | Payment errors appear without losing previously entered shipping data | To be recorded during real test | Not Run | High |
| TC-011 | Invalid payment data handling | Payment section is open | Enter invalid sample payment values and submit | User sees validation errors and no order is created | To be recorded during real test | Not Run | High |
| TC-012 | Order confirmation | Checkout form is completed with valid sample data | Submit the order using permitted demo/test payment data | Confirmation page shows order summary and next steps | To be recorded during real test | Not Run | High |
