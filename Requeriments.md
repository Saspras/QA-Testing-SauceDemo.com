## Functional Requirements

- The system must include a Login feature that verifies user credentials.  
  If the credentials are invalid, the system must display an appropriate error message.

- The system must include an Inventory section to manage available products.  
  If a product is out of stock, it must be disabled or unavailable for purchase.

- The system must include a Shopping Cart so that users can add or remove products before completing a purchase.

- The system should allow the user to add more than one unit of the same product to the cart.  
  (Currently, the system allows only one of each product.)

- The system must include a Customer Data Input form where users can enter their personal information required for shipping.

- The system must generate a unique Order Number after each successful purchase so that users can identify their orders.

- After completing an order, the system automatically logs the user out.  
  (This could be intentional for security reasons, but may affect user experience.)

- When logging in with a different account, the Shopping Cart must be empty to prevent data from being shared between users.


## Non-Functional Requirements

- The home page should load in less than 3 seconds under normal network conditions.

- The website must be responsive, adapting correctly to different screen sizes and resolutions.

- User data must not be stored in plain text in the database.

- The system must be compatible with major browsers (Chrome, Firefox, and Edge).

- Error messages should be clear, visible, and easy to understand for the user.

- The website should maintain a consistent design and layout across all pages.
