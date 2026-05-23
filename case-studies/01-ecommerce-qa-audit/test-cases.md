# E-commerce QA Audit Test Cases

| ID | Scenario | Preconditions | Steps | Expected Result | Actual Result | Status | Priority |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EC-001 | Homepage loads | Browser is open and network is available | Navigate to the tested URL | Homepage loads without visible errors and key navigation is available | To be recorded during real test | Not Run | High |
| EC-002 | Product listing opens | Homepage is loaded | Open a product category or product listing | Product cards, names, prices, and links are visible | To be recorded during real test | Not Run | High |
| EC-003 | Product detail page opens | Product listing is visible | Select one product | Product detail page shows name, image, price, description, and add-to-cart option | To be recorded during real test | Not Run | High |
| EC-004 | Add product to cart | Product detail page is open | Add the product to cart | Product is added and cart count or confirmation updates | To be recorded during real test | Not Run | High |
| EC-005 | Cart quantity updates | Product is in cart | Change quantity from 1 to 2 | Quantity, item total, and subtotal update clearly | To be recorded during real test | Not Run | High |
| EC-006 | Remove item from cart | Product is in cart | Remove the product | Item is removed and cart state updates correctly | To be recorded during real test | Not Run | Medium |
| EC-007 | Empty cart state | Cart has no products | Open the cart | Empty-cart message and next action are clear | To be recorded during real test | Not Run | Medium |
| EC-008 | Signup required fields | Signup form is available | Submit signup with required fields blank | Required-field messages identify missing fields | To be recorded during real test | Not Run | High |
| EC-009 | Signup email validation | Signup form is available | Enter invalid email format and submit | Email validation message is clear | To be recorded during real test | Not Run | High |
| EC-010 | Login required fields | Login form is available | Submit login with blank fields | Required-field messages appear without page confusion | To be recorded during real test | Not Run | Medium |
| EC-011 | Address/shipping required fields | Checkout address form is available | Submit blank required shipping fields | Missing-field messages are clear and visible | To be recorded during real test | Not Run | High |
| EC-012 | Valid shipping form | Checkout address form is available | Enter valid demo shipping details and continue | User advances to checkout review or next step | To be recorded during real test | Not Run | High |
| EC-013 | Checkout review accuracy | Cart and shipping details exist | Review checkout summary | Product, quantity, subtotal, shipping, tax, and total are clear | To be recorded during real test | Not Run | High |
| EC-014 | Payment validation | Payment form is available | Submit incomplete demo/test payment data | Field-level validation explains what must be fixed | To be recorded during real test | Not Run | High |
| EC-015 | Payment demo/test data path | Payment form allows demo/test data | Submit permitted demo/test payment values | Site accepts demo/test values or clearly explains blocked payment flow | To be recorded during real test | Not Run | High |
| EC-016 | Order confirmation or blocked step | Checkout is submitted with permitted test data | Complete final checkout action | Confirmation or blocked-step message is clear and does not imply a real purchase if demo flow blocks | To be recorded during real test | Not Run | High |
| EC-017 | Mobile responsiveness | Mobile viewport or device is available | Repeat product-to-cart path on mobile | Layout remains readable and primary actions are accessible | To be recorded during real test | Not Run | High |
| EC-018 | Error messaging recovery | A validation error is triggered | Correct the invalid field and resubmit | Error clears and user can continue | To be recorded during real test | Not Run | High |
| EC-019 | Back navigation behavior | User is inside checkout flow | Use browser/app back navigation | User returns to previous step without unexpected data loss | To be recorded during real test | Not Run | Medium |
| EC-020 | Data persistence after validation error | Checkout form has entered data | Trigger a validation error in one field | Previously entered valid data remains available | To be recorded during real test | Not Run | High |
| EC-021 | Help/support visibility | User is blocked or confused during checkout | Look for help, support, FAQ, or contact path | Support/help path is visible or product guidance is clear | To be recorded during real test | Not Run | Low |
