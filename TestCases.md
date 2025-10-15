# 🧾 Test Cases – SauceDemo

| ID | Title | Preconditions | Steps | Expected Result | Status |
|----|--------|----------------|--------|------------------|---------|
| TC01 | Valid Login | User is on the Login Page | 1. Enter valid credentials<br>2. Click the Login button | User is redirected to the Inventory page | Pass |
| TC02 | Invalid Login | User is on the Login Page | 1. Enter invalid password<br>2. Click the Login button | System displays an error message | Pass |
| TC03 | Add Product to Cart | User is logged in | 1. Click **Add to Cart** on a product<br>2. Go to the Cart page | The product appears in the cart list | Pass |
| TC04 | Remove Product from Cart | Products must be in the cart | 1. Go to the Cart page<br>2. Click **Remove** | Product disappears from the cart list | Pass |
| TC05 | Remove Product from Inventory Page | The product must be in the cart, and the user must be on the Inventory page | 1. Click **Remove** on the same product | Product disappears from the cart list | Pass |
| TC06 | Checkout Without Data | User has products in the cart | 1. Go to Checkout<br>2. Leave all fields empty<br>3. Click **Continue** | System shows an error message | Pass |
| TC07 | Successful Checkout | User is logged in with items in the cart | 1. Add a product to the cart<br>2. Proceed to Checkout<br>3. Fill in valid information<br>4. Click **Finish** | Order confirmation page is displayed with a unique order ID | Pass |
| TC08 | Logout | User is logged in | 1. Click the three-line **menu button** (hamburger icon) in the top-left corner<br>2. Click **Logout** | User is successfully logged out and redirected to the Login page | Pass |
