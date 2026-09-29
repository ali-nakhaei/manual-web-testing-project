
# Test Cases

## 1. Login

**Test Case ID:** TC-LOGIN-001

**Title:** Login with valid username and valid password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is successfully logged in.
- The user is redirected to the Products page.

**Actual Result:**
The user was successfully redirected to the Products page.


**Status:**
Status: PASS


### TC-LOGIN-002 — Login with invalid username and invalid password

**Test Case ID:** TC-LOGIN-002

**Title:** Login with invalid username and invalid password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: `invalid_user`
- Password: `invalid_password`

**Steps:**
1. Enter `invalid_user` in the Username field.
2. Enter `invalid_password` in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate error message is displayed.

**Actual Result:**
The login attempt was rejected and an error message stating that the username and password do not match was displayed.

**Status:**
PASS


### TC-LOGIN-003 — Login with valid username and invalid password

**Test Case ID:** TC-LOGIN-003

**Title:** Login with valid username and invalid password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: `standard_user`
- Password: `invalid_password`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `invalid_password` in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate error message is displayed.

**Actual Result:**
The login attempt was rejected and an error message stating that the username and password do not match was displayed.

**Status:**
PASS


### TC-LOGIN-004 — Login with invalid username and valid password

**Test Case ID:** TC-LOGIN-004

**Title:** Login with invalid username and valid password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: `invalid_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `invalid_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate error message is displayed.

**Actual Result:**
The login attempt was rejected and an error message stating that the username and password do not match was displayed.

**Status:**
PASS


### TC-LOGIN-005 — Login with empty username and empty password

**Test Case ID:** TC-LOGIN-005

**Title:** Login with empty username and empty password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: Empty
- Password: Empty

**Steps:**
1. Leave the Username field empty.
2. Leave the Password field empty.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate validation error message is displayed.

**Actual Result:**
The login attempt was rejected and the error message "Epic sadface: Username is required" was displayed.

**Status:**
PASS


### TC-LOGIN-006 — Login with empty username and valid password

**Test Case ID:** TC-LOGIN-006

**Title:** Login with empty username and valid password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: Empty
- Password: `secret_sauce`

**Steps:**
1. Leave the Username field empty.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate validation error message is displayed.

**Actual Result:**
The login attempt was rejected and the error message "Epic sadface: Username is required" was displayed.

**Status:**
PASS



### TC-LOGIN-007 — Login with valid username and empty password

**Test Case ID:** TC-LOGIN-007

**Title:** Login with valid username and empty password

**Preconditions:**
- The SauceDemo login page is open.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Test Data:**
- Username: `standard_user`
- Password: Empty

**Steps:**
1. Enter `standard_user` in the Username field.
2. Leave the Password field empty.
3. Click the Login button.

**Expected Result:**
- The user is not logged in.
- The user remains on the Login page.
- An appropriate validation error message is displayed.

**Actual Result:**
The login attempt was rejected and the error message "Epic sadface: Password is required" was displayed.

**Status:**
PASS




## 2. Product Listing

### TC-PRODUCT-001 — Verify that products are displayed

**Test Case ID:** TC-PRODUCT-001

**Title:** Verify that products are displayed

**Preconditions:**
- The SauceDemo login page is open.


**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the Products page.

**Expected Result:**
- The user is successfully logged in.
- The Products page is displayed.
- A list of products is displayed.

**Actual Result:**
The Products page was displayed successfully and the list of products was displayed correctly.

**Status:**
PASS


### TC-PRODUCT-002 — Verify that product information is displayed correctly

**Test Case ID:** TC-PRODUCT-002

**Title:** Verify that product information is displayed correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the products displayed on the Products page.
5. Check the information displayed for each product.

**Expected Result:**
- Each product displays its name.
- Each product displays its description.
- Each product displays its price.
- The product information is displayed correctly and clearly.

**Actual Result:**
Product information including the name, description, and price was displayed correctly.

**Status:**
PASS


### TC-PRODUCT-003 — Verify that product images are displayed

**Test Case ID:** TC-PRODUCT-003

**Title:** Verify that product images are displayed

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the products displayed on the Products page.
5. Check the product images.

**Expected Result:**
- Product images are displayed for the products.
- The images are loaded correctly.
- The images correspond to the respective products.

**Actual Result:**
The product prices were displayed correctly and clearly for the products.

**Status:**
PASS



### TC-PRODUCT-004 — Verify that product prices are displayed

**Test Case ID:** TC-PRODUCT-004

**Title:** Verify that product prices are displayed

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the products displayed on the Products page.
5. Check the price displayed for each product.

**Expected Result:**
- A price is displayed for each product.
- The price is displayed clearly and is readable.
- The price is displayed in the expected currency format.

**Actual Result:**
The Add to Cart button was displayed and available for the products.

**Status:**
PASS



### TC-PRODUCT-005 — Verify that the Add to Cart button is available for products

**Test Case ID:** TC-PRODUCT-005

**Title:** Verify that the Add to Cart button is available for products

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the products displayed on the Products page.
5. Check the Add to Cart button for each product.

**Expected Result:**
- An Add to Cart button is displayed for each product.
- The button is visible and readable.
- The button is available for interaction.

**Actual Result:**
The Add to Cart button was displayed and available for the products.

**Status:**
PASS


### TC-PRODUCT-006 — Verify that the Add to Cart button changes after adding a product

**Test Case ID:** TC-PRODUCT-006

**Title:** Verify that the Add to Cart button changes after adding a product

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button for the selected product.
6. Observe the button after adding the product.

**Expected Result:**
- The selected product is added to the shopping cart.
- The Add to Cart button changes to the expected state after the product is added.

**Actual Result:**
The product was added to the cart and the Add to Cart button changed to the expected state.

**Status:**
PASS


### TC-PRODUCT-007 — Verify that the cart is updated after adding a product

**Test Case ID:** TC-PRODUCT-007

**Title:** Verify that the cart is updated after adding a product

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button for the selected product.
6. Observe the shopping cart.

**Expected Result:**
- The selected product is added to the shopping cart.
- The shopping cart is updated to reflect the added product.
- The cart item count is updated correctly.

**Actual Result:**
The selected product was added to the cart successfully, and the cart was updated correctly.

**Status:**
PASS



## 3. Product Sorting

### TC-SORT-001 — Verify that the sorting option is available

**Test Case ID:** TC-SORT-001

**Title:** Verify that the sorting option is available

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Observe the Products page.
5. Locate the sorting option.

**Expected Result:**
- The sorting option is displayed on the Products page.
- The sorting option is visible and available for interaction.

**Actual Result:**
The sorting option was displayed and available for interaction.

**Status:**
PASS


### TC-SORT-002 — Verify that products are sorted correctly by name

**Test Case ID:** TC-SORT-002

**Title:** Verify that products are sorted correctly by name

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the sorting option.
5. Select a name-based sorting option.
6. Observe the order of the products.

**Expected Result:**
- The products are sorted according to the selected name-based sorting option.
- The product order is updated correctly.

**Actual Result:**
The products were sorted correctly according to the selected name-based sorting option.

**Status:**
PASS


### TC-SORT-003 — Verify that products are sorted correctly by price

**Test Case ID:** TC-SORT-003

**Title:** Verify that products are sorted correctly by price

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the sorting option.
5. Select a price-based sorting option.
6. Observe the order of the products.

**Expected Result:**
- The products are sorted according to the selected price-based sorting option.
- The product order is updated correctly.

**Actual Result:**
The products were sorted correctly according to the selected price-based sorting option.

**Status:**
PASS




## 4. Product Details

### TC-DETAILS-001 — Verify that the Product Details page opens when a product is selected

**Test Case ID:** TC-DETAILS-001

**Title:** Verify that the Product Details page opens when a product is selected

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the page after selecting the product.

**Expected Result:**
- The Product Details page is displayed.
- The selected product is displayed on the Product Details page.

**Actual Result:**
The Product Details page was displayed successfully and the selected product was displayed correctly.

**Status:**
PASS


### TC-DETAILS-002 — Verify that the product name is displayed correctly

**Test Case ID:** TC-DETAILS-002

**Title:** Verify that the product name is displayed correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Check the product name.

**Expected Result:**
- The product name is displayed on the Product Details page.
- The displayed product name matches the product selected from the Products page.

**Actual Result:**
The product name was displayed correctly and matched the selected product.

**Status:**
PASS


### TC-DETAILS-003 — Verify that the product image is displayed correctly

**Test Case ID:** TC-DETAILS-003

**Title:** Verify that the product image is displayed correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Check the product image.

**Expected Result:**
- The product image is displayed on the Product Details page.
- The image is loaded correctly.
- The displayed image corresponds to the selected product.

**Actual Result:**
The product image was displayed correctly and matched the selected product.

**Status:**
PASS


### TC-DETAILS-004 — Verify that the product description is displayed

**Test Case ID:** TC-DETAILS-004

**Title:** Verify that the product description is displayed

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Check the product description.

**Expected Result:**
- The product description is displayed on the Product Details page.
- The description corresponds to the selected product.
- The description is readable and clearly displayed.

**Actual Result:**
The product description was displayed correctly and matched the selected product.

**Status:**
PASS


### TC-DETAILS-005 — Verify that the product price is displayed correctly

**Test Case ID:** TC-DETAILS-005

**Title:** Verify that the product price is displayed correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Check the product price.

**Expected Result:**
- The product price is displayed on the Product Details page.
- The displayed price matches the price of the selected product.
- The price is clearly displayed and readable.

**Actual Result:**
The product price was displayed correctly and matched the price shown for the selected product on the Products page.

**Status:**
PASS


### TC-DETAILS-006 — Verify that the Add to Cart button is available

**Test Case ID:** TC-DETAILS-006

**Title:** Verify that the Add to Cart button is available

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Locate the Add to Cart button.

**Expected Result:**
- The Add to Cart button is displayed on the Product Details page.
- The button is visible and readable.
- The button is available for interaction.

**Actual Result:**
The Add to Cart button was displayed and available for interaction.

**Status:**
PASS


### TC-DETAILS-007 — Verify that a product can be added to the cart from the Product Details page

**Test Case ID:** TC-DETAILS-007

**Title:** Verify that a product can be added to the cart from the Product Details page

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button on the Product Details page.
6. Open the shopping cart.
7. Observe the cart contents.

**Expected Result:**
- The selected product is added to the shopping cart.
- The selected product is displayed in the shopping cart.
- The cart item count is updated correctly.

**Actual Result:**
The selected product was added to the shopping cart successfully, and the cart was updated correctly.

**Status:**
PASS


### TC-DETAILS-008 — Verify that the user can return to the Product Listing page from the Product Details page

**Test Case ID:** TC-DETAILS-008

**Title:** Verify that the user can return to the Product Listing page from the Product Details page

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Observe the Product Details page.
6. Click the Back to products button.
7. Observe the page after clicking the button.

**Expected Result:**
- The user is returned to the Product Listing page.
- The Products page is displayed correctly.
- The product list is displayed.

**Actual Result:**
The user was successfully returned to the Product Listing page, and the list of products was displayed.

**Status:**
PASS




### TC-CART-001 — Verify that a product can be added to the shopping cart

**Test Case ID:** TC-CART-001

**Title:** Verify that a product can be added to the shopping cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Observe the cart contents.

**Expected Result:**
- The selected product is added to the shopping cart.
- The selected product is displayed in the shopping cart.

**Actual Result:**
The cart indicator displayed the correct number of added items, and the number of products in the cart matched the number of items added.

**Status:**
PASS


### TC-CART-002 — Verify that the cart displays the correct number of added items
**Test Case ID:** TC-CART-002

**Title:** Verify that the cart displays the correct number of added items

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Observe the shopping cart icon.
7. Open the shopping cart.
8. Observe the number of products displayed in the cart.

**Expected Result:**
- The cart indicator displays the correct number of added items.
- The number of products displayed in the shopping cart matches the number of products added.

**Actual Result:**
The cart indicator displayed the correct number of added items, and the number of products in the cart matched the number of items added.

**Status:**
PASS


### TC-CART-003 — Verify that the added product is displayed in the shopping cart

**Test Case ID:** TC-CART-003

**Title:** Verify that the added product is displayed in the shopping cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Observe the product displayed in the shopping cart.

**Expected Result:**
- The added product is displayed in the shopping cart.
- The displayed product is the same product that was added from the Products page.

**Actual Result:**
The added product was displayed correctly in the shopping cart and matched the selected product.

**Status:**
PASS


### TC-CART-004 — Verify that the product name and price are displayed correctly in the shopping cart

**Test Case ID:** TC-CART-004

**Title:** Verify that the product name and price are displayed correctly in the shopping cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Note the product name and price.
6. Click the Add to Cart button.
7. Open the shopping cart.
8. Check the product name and price.

**Expected Result:**
- The product name is displayed correctly in the shopping cart.
- The product price is displayed correctly in the shopping cart.
- The product name and price match the selected product.

**Actual Result:**
The product name and price were displayed correctly in the shopping cart and matched the information shown on the Products page.

**Status:**
PASS


### TC-CART-005 — Verify that a product can be removed from the shopping cart

**Test Case ID:** TC-CART-005

**Title:** Verify that a product can be removed from the shopping cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Remove button for the selected product.
8. Observe the shopping cart.

**Expected Result:**
- The selected product is removed from the shopping cart.
- The removed product is no longer displayed in the shopping cart.

**Actual Result:**
The selected product was successfully removed from the shopping cart and was no longer displayed.

**Status:**
PASS


### TC-CART-006 — Verify that the cart is updated after removing a product

**Test Case ID:** TC-CART-006

**Title:** Verify that the cart is updated after removing a product

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Remove button for the selected product.
8. Observe the shopping cart and cart indicator.

**Expected Result:**
- The removed product is no longer displayed in the shopping cart.
- The cart indicator is updated correctly after removing the product.
- The cart reflects the current number of products.

**Actual Result:**
The removed product was no longer displayed in the shopping cart, and the cart indicator was updated correctly.

**Status:**
PASS


### TC-CART-007 — Verify the behavior when adding multiple units of the same product

**Test Case ID:** TC-CART-007

**Title:** Verify the behavior when adding multiple units of the same product

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Return to the Products page.
7. Click the Add to Cart button for the same product again.
8. Open the shopping cart.
9. Observe how the same product is displayed in the cart.

**Expected Result:**
- The same product is handled according to the application's expected behavior when it is added more than once.
- The cart reflects the added units correctly.
- No unexpected or duplicate behavior occurs.

**Actual Result:**
After adding a product to the cart, the Add to Cart button changed and the same product could not be added again from the Products page.

**Status:**
PASS


### TC-CART-008 — Verify that multiple different products can be displayed in the shopping cart

**Test Case ID:** TC-CART-008

**Title:** Verify that multiple different products can be displayed in the shopping cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Products: Two different available products

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select the first product.
5. Click the Add to Cart button.
6. Select a different product.
7. Click the Add to Cart button for the second product.
8. Open the shopping cart.
9. Observe the products displayed in the shopping cart.

**Expected Result:**
- Both selected products are displayed in the shopping cart.
- The products displayed in the cart match the products that were added.
- The cart reflects the correct number of added products.

**Actual Result:**
Both different products were displayed correctly in the shopping cart, and the cart item count was updated correctly.

**Status:**
PASS


### TC-CART-009 — Verify that clicking the product name in the cart opens the corresponding Product Details page

**Test Case ID:** TC-CART-009

**Title:** Verify that clicking the product name in the cart opens the corresponding Product Details page

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the product name.
8. Observe the page that opens.

**Expected Result:**
- The Product Details page is displayed.
- The displayed product is the same product selected from the shopping cart.

**Actual Result:**
The Product Details page opened successfully and displayed the same product selected from the shopping cart.

**Status:**
PASS


### TC-CART-010 — Verify that the cart is empty after all products are removed

**Test Case ID:** TC-CART-010

**Title:** Verify that the cart is empty after all products are removed

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Products: Two different available products

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Add two different products to the shopping cart.
5. Open the shopping cart.
6. Remove the first product.
7. Remove the second product.
8. Observe the shopping cart.

**Expected Result:**
- All products are removed from the shopping cart.
- No products are displayed in the shopping cart.
- The cart reflects that there are no remaining products.

**Actual Result:**
All products were successfully removed from the shopping cart, and the cart was empty afterward.

**Status:**
PASS



### TC-CHECKOUT-001 — Verify that the user can proceed to Checkout from the Shopping Cart

**Test Case ID:** TC-CHECKOUT-001

**Title:** Verify that the user can proceed to Checkout from the Shopping Cart

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Observe the page that opens.

**Expected Result:**
- The Checkout page is displayed.
- The Customer Information form is displayed.
- The user can enter the required customer information.

**Actual Result:**
The user successfully proceeded from the Shopping Cart to the Checkout page, and the Customer Information form was displayed.

**Status:**
PASS


### TC-CHECKOUT-002 — Verify that the Customer Information form is displayed

**Test Case ID:** TC-CHECKOUT-002

**Title:** Verify that the Customer Information form is displayed

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Observe the Customer Information page.

**Expected Result:**
- The Customer Information form is displayed.
- The First Name field is displayed.
- The Last Name field is displayed.
- The Postal Code field is displayed.
- The Continue button is displayed.

**Actual Result:**
The Customer Information form was displayed correctly, including the First Name, Last Name, Postal Code fields, and Continue button.

**Status:**
PASS


### TC-CHECKOUT-003 — Verify that the user cannot proceed with empty required fields

**Test Case ID:** TC-CHECKOUT-003

**Title:** Verify that the user cannot proceed with empty required fields

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Leave all Customer Information fields empty.
9. Click the Continue button.

**Expected Result:**
- The user cannot proceed to the next Checkout step.
- An appropriate validation message is displayed.
- The Customer Information page remains displayed.

**Actual Result:**
The user could not proceed with empty required fields, and the error message "First Name is required" was displayed.

**Status:**
PASS


### TC-CHECKOUT-004 — Verify that the user can proceed with valid customer information

**Test Case ID:** TC-CHECKOUT-004

**Title:** Verify that the user can proceed with valid customer information

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter a valid first name.
9. Enter a valid last name.
10. Enter a valid postal code.
11. Click the Continue button.
12. Observe the next Checkout page.

**Expected Result:**
- The customer information is accepted.
- The user proceeds to the next Checkout step.
- The Order Summary page is displayed.

**Actual Result:**
The valid customer information was accepted, and the user was successfully redirected to the Order Summary page.

**Status:**
PASS


### TC-CHECKOUT-005 — Verify the validation behavior of the Postal Code field

**Test Case ID:** TC-CHECKOUT-005

**Title:** Verify the validation behavior of the Postal Code field

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: Invalid or empty value
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter a valid first name.
9. Enter a valid last name.
10. Enter an invalid or empty value in the Postal Code field.
11. Click the Continue button.
12. Observe the result.

**Expected Result:**
- The system validates the Postal Code field.
- If the value is invalid or empty, the user cannot proceed to the next Checkout step.
- An appropriate validation message is displayed.

**Actual Result:**
The user could not proceed with an empty Postal Code field, and the error message "Postal Code is required" was displayed.

**Status:**
PASS


### TC-CHECKOUT-006 — Verify that the Order Summary displays the selected products correctly

**Test Case ID:** TC-CHECKOUT-006

**Title:** Verify that the Order Summary displays the selected products correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter valid customer information.
9. Click the Continue button.
10. Observe the Order Summary page.
11. Check the product displayed in the Order Summary.

**Expected Result:**
- The Order Summary page is displayed.
- The selected product is displayed in the Order Summary.
- The product displayed matches the product added to the shopping cart.

**Actual Result:**
The Order Summary displayed the selected product correctly, and it matched the product in the shopping cart.

**Status:**
PASS


### TC-CHECKOUT-007 — Verify that product prices are displayed correctly in the Order Summary

**Test Case ID:** TC-CHECKOUT-007

**Title:** Verify that product prices are displayed correctly in the Order Summary

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Note the product price.
6. Click the Add to Cart button.
7. Open the shopping cart.
8. Click the Checkout button.
9. Enter valid customer information.
10. Click the Continue button.
11. Observe the Order Summary page.
12. Check the product price.

**Expected Result:**
- The product price is displayed in the Order Summary.
- The displayed price matches the price of the selected product.
- The price is clearly displayed and readable.

**Actual Result:**
The product price was displayed correctly in the Order Summary and matched the price shown on the Products page.

**Status:**
PASS


### TC-CHECKOUT-008 — Verify that the total price is calculated correctly

**Test Case ID:** TC-CHECKOUT-008

**Title:** Verify that the total price is calculated correctly

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Products: Two different available products

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Add two different products to the shopping cart.
5. Note the prices of the selected products.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter valid customer information.
9. Click the Continue button.
10. Observe the Order Summary page.
11. Calculate the expected subtotal by adding the product prices.
12. Compare the calculated subtotal with the subtotal displayed by the application.
13. Observe the total price displayed by the application.

**Expected Result:**
- The subtotal is calculated correctly based on the selected product prices.
- The displayed subtotal matches the expected subtotal.
- The total price is calculated correctly according to the application's pricing rules.

**Actual Result:**
The subtotal was calculated correctly based on the selected product prices, and the displayed total price was calculated correctly.

**Status:**
PASS


### TC-CHECKOUT-009 — Verify that the user can complete the order

**Test Case ID:** TC-CHECKOUT-009

**Title:** Verify that the user can complete the order

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter valid customer information.
9. Click the Continue button.
10. Observe the Order Summary page.
11. Click the Finish button.
12. Observe the result.

**Expected Result:**
- The order is completed successfully.
- The user is redirected to the order confirmation page.

**Actual Result:**
The order was completed successfully, and the order confirmation page.

**Status:**
PASS


### TC-CHECKOUT-010 — Verify that an order confirmation message is displayed after completing the order

**Test Case ID:** TC-CHECKOUT-010

**Title:** Verify that an order confirmation message is displayed after completing the order

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`
- First Name: `Ali`
- Last Name: `Test`
- Postal Code: `12345`
- Product: Any available product

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Select a product from the Products page.
5. Click the Add to Cart button.
6. Open the shopping cart.
7. Click the Checkout button.
8. Enter valid customer information.
9. Click the Continue button.
10. Click the Finish button.
11. Observe the order confirmation page.

**Expected Result:**
- The order confirmation page is displayed.
- An order confirmation message is displayed.
- The message indicates that the order has been completed successfully.

**Actual Result:**
The order confirmation page was displayed with the message "Thank you for your order!".

**Status:**
PASS



### TC-LOGOUT-001 — Verify that the Logout option is available

**Test Case ID:** TC-LOGOUT-001

**Title:** Verify that the Logout option is available

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the navigation menu.
5. Locate the Logout option.

**Expected Result:**
- The Logout option is displayed in the navigation menu.
- The Logout option is visible and available for interaction.

**Actual Result:**
The Logout option was displayed and available for interaction.

**Status:**
PASS



### TC-LOGOUT-002 — Verify that the user is logged out successfully

**Test Case ID:** TC-LOGOUT-002

**Title:** Verify that the user is logged out successfully

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the navigation menu.
5. Click the Logout option.
6. Observe the application after logging out.

**Expected Result:**
- The user is logged out successfully.
- The user is no longer able to access the authenticated application state.

**Actual Result:**
The user was successfully logged out.

**Status:**
PASS


### TC-LOGOUT-003 — Verify that the user is redirected to the Login page after logging out

**Test Case ID:** TC-LOGOUT-003

**Title:** Verify that the user is redirected to the Login page after logging out

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the navigation menu.
5. Click the Logout option.
6. Observe the page after logging out.

**Expected Result:**
- The user is redirected to the Login page.
- The Username field is displayed.
- The Password field is displayed.
- The Login button is displayed.

**Actual Result:**
The user was redirected to the Login page after logging out, and the Username, Password, and Login button were displayed.

**Status:**
PASS



### TC-LOGOUT-004 — Verify that authenticated pages cannot be accessed after logging out

**Test Case ID:** TC-LOGOUT-004

**Title:** Verify that authenticated pages cannot be accessed after logging out

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open the navigation menu.
5. Click the Logout option.
6. Attempt to access the Products page again.
7. Observe the result.

**Expected Result:**
- The user cannot access the authenticated Products page after logging out.
- The user is redirected to the Login page or is otherwise required to log in again.

**Actual Result:**
After logging out, attempting to access the Products page directly was blocked, and the error message "Epic sadface: You can only access '/inventory.html' when you are logged in." was displayed.

**Status:**
PASS



### TC-LOGOUT-005 — Verify the behavior of other active tabs after logging out from one tab

**Test Case ID:** TC-LOGOUT-005

**Title:** Verify the behavior of other active tabs after logging out from one tab

**Preconditions:**
- The SauceDemo login page is open.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.
4. Open another browser tab.
5. Navigate to the Products page in the second tab.
6. Return to the first tab.
7. Open the navigation menu.
8. Click the Logout option.
9. Switch to the second tab.
10. Attempt to interact with the Products page.
11. Observe the result.

**Expected Result:**
- The behavior of the second tab is consistent with the application's session management.
- The user should not be able to continue accessing authenticated functionality if the session has been invalidated by Logout.

**Actual Result:**
After logging out from one tab, the other active tab no longer allowed access to the authenticated page and redirected to the Login page.

**Status:**
PASS




