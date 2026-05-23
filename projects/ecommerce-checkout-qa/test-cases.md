# E-commerce Checkout Test Cases

| ID | Scenario | Steps | Expected Result | Priority |
| --- | --- | --- | --- | --- |
| TC-001 | Update cart quantity | Add an item to cart, change quantity from 1 to 2, review subtotal | Quantity and subtotal update correctly | High |
| TC-002 | Required shipping fields | Continue checkout with missing required shipping fields | Required-field errors appear clearly | High |
| TC-003 | Invalid email format | Enter an invalid email address during checkout | User sees an email-format validation message | Medium |
| TC-004 | Empty payment fields | Submit payment section with empty required fields | Payment errors appear without losing entered shipping data | High |
| TC-005 | Order confirmation | Complete checkout with valid sample data | Confirmation page shows order summary and next steps | High |
