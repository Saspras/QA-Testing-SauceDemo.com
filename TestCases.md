# 🧾 Test Cases – SauceDemo

| ID | Title | Preconditions | Steps | Expected Result | Status |
|----|--------|----------------|--------|------------------|---------|
| TC01 | Valid Login | User is on the Login Page | 1. Enter correct credentials in the form <br>2. Click the Login button | User is redirected to the Inventory page | Pass |
| TC02 | Invalid Login | User is on the Login Page | 1. Enter invalid password in the form <br>2. Click the Login button | System displays an error message | Pass |
| TC03 | Add Product to Cart | User is logged in | 1. click the Add to Cart button <br>2. Click on the button with the shopping cart image in the upper right corner.  | The product appears in the cart list | Pass |
| TC04 | Remove Product from Cart | The user must be logged in with a valid account and the Products must be in the cart | 1. Click on the button with the shopping cart image in the upper right corner. <br>2. click the Remove button | Product disappears from the cart list | Pass |
| TC05 | Remove Product from Inventory Page | The user must be logged in with a valid account and the product must be in the cart, the user must be on the Inventory page | 1. Click the Remove button on the same product | Product disappears from the cart list | Pass |
| TC06 | Checkout Without Data | The user must be logged in with a valid account, must be in the shopping cart, and must have products in it | 1. Click in the buttons checkout <br>2. Leave all fields empty<br>3. Click in continues button | System shows an error message | Pass |
| TC07 | Successful Checkout | The user must log in with a valid account, have products added to their cart, and be on the checkout page. t | 1. Fill in all fields with the required information. <br>2. Fill in all fields with the relevant information. <br> 3.  Click on the Continue button <br> 4. Confirm that the information is correct and click on the Continue button at the bottom left.| Order confirmation page is displayed with a unique order ID | Pass |
| TC08 | Logout | User is logged in | 1. Click the three-line **menu button** (hamburger icon) in the top-left corner<br>2. Click Logout button. | User is successfully logged out and redirected to the Login page | Pass |
