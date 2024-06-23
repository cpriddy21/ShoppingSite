Description:
Site created using Django that simulates a clothing shopping site made for DBMS II course.

User Manual:
Shopping System User Manual

The website functions similarly to a standard online shopping site. After an account is created, users can explore products either by department or in a general list. They are then able to select desired items and add them to their cart. When reviewing the cart, users will find a detailed list of chosen products, their individual prices, and the overall cost of all items in the cart. The option to remove any item from the cart is also present while viewing the cart. Once customers are satisfied with the items in their cart, they can begin the checkout process. They will be asked to  provide shipping and billing details along with their debit/credit card information. If all input is valid, their orders will be confirmed. Additionally, users can track both current and past orders.

Create an Account:
Navigate to the “sign up” page by clicking the button labeled “Sign up” in the navigation bar in the top right of the page. The page should now have three input boxes to enter a username, password, and confirmation password. Be sure the chosen password is at least 8 characters in length and unique in comparison to the chosen username. The password also should not be entirely numeric or considered common. Once the information has been input into the boxes, click the gray “Sign Up” button toward the bottom of the page. If there is an issue with any of the information, a message will appear that explains why there was an issue. After adjusting the information to fit the given criteria, click the gray “Sign Up” toward the bottom of the page again. If the page redirects to the login page, the account was created successfully. 

Login:
In the two input boxes, enter the username and password that was chosen during the creation of your account. Once they are entered, click the gray “Login” button toward the bottom of the page. If there is an issue, a message displaying “invalid password or username” will appear at the top of the page. If that happens, the username or password is incorrect. Try entering a different one. Click the gray “Login” button at the bottom of the page again. If the login is successful, the page will redirect to the home page. If the correct username or password is unknown, try creating a different account. 

Browsing Products & Adding Items to Cart:
Products can all be viewed on the home page. Click “Shopping Site” located in the top left of the page to navigate there. All products are represented by the individual boxes on the page. The sidebar on the left of the page lists all departments along with an “All” selection. Clicking “Accessories” will show only products in the accessories department. The same logic applies for footwear, tops, bottoms, and dresses. Clicking “All” will show all products. To view further details of a product, click the gray “view” button in the bottom right of the box. The site will redirect to a page showing product details, a blue button labeled “Add to Cart”, and another blue button labeled “Cart.” Clicking “Add to Cart” will add the product to your cart if you are logged in. The “Cart” button will cause the site to redirect to a page showing all items present in your cart. 

Managing the Cart:
Navigate to the cart page by clicking the “Cart” button in the navigation bar at the top of the page. If the cart is empty, navigate back to the products page to add items to the cart and verify you are logged in. If there are items in the cart, there will be a table listing the product name, description, price, quantity, and a removal option for each product in the cart. Clicking the red “-1” remove button decreases the quantity of the product by 1. The price of all items in the cart (Total cost) can be viewed below table. Once satisfied with all items in the cart, click the blue “Proceed to Checkout” button toward the bottom of the page. The site will redirect to a page allowing the checkout process to begin. 

Checkout:
Navigate to the checkout page by adding desired items to the cart and clicking the blue “Proceed to Checkout” button toward the bottom of the “Cart” page. Review the order by reading the table at the top of the page. Verify the table’s contents are correct. If so, enter the shipping address, billing address, and valid card/debit card number. After verifying all of the input information is correct, click the blue “Place Order” button toward the bottom of the page. If the checkout is successful, the site will redirect to an empty cart page and display a message saying “Checkout successful. Your order has been placed.”


Viewing Orders:
Navigate to the order history page by clicking “Orders” in the navigation bar at the top of the page. If any orders have been placed on the account that is currently logged into, they will appear on the page. The order ID, product ID, quantity, billing address, shipping address, date ordered, and last four digits of the card used for payment will be listed for every product ordered on the account. 
