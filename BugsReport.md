
# Bug Report – SauceDemo

| ID | Title | Description | Steps to Reproduce | Expected Result | Actual Result | Severity | Status |
|----|--------|--------------|--------------------|------------------|----------------|-----------|---------|
| BUG01 | Cart not cleared after logout | The shopping cart keeps the previously added products even after the user logs out and logs in again. | 1. Log in with valid credentials<br>2. Add a product to the cart<br>3. Log out<br>4. Log in again | The cart should be empty after logging out | The same products remain in the cart | **Medium** | Open |
| BUG02 | Menu button delay | The hamburger (menu) button takes several seconds to open the side menu after clicking. | 1. Log in<br>2. Click the three-line menu button (top-left corner) | The menu should open immediately | The menu opens with a noticeable delay | **Low** | Open |
| BUG03 | problem_user | The user "problem_user", them can't see the real photos of products |1. Login with the user "problem_user" | The home page should be visisible without any problems | The product photos is not correct | **Medium** | Open |
