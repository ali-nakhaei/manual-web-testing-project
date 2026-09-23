
# Test Scenarios

## 1. Login

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-LOGIN-001 | Login with valid username and valid password | Positive |
| TS-LOGIN-002 | Login with invalid username and invalid password | Negative |
| TS-LOGIN-003 | Login with valid username and invalid password | Negative |
| TS-LOGIN-004 | Login with invalid username and valid password | Negative |
| TS-LOGIN-005 | Login with empty username and empty password | Negative |
| TS-LOGIN-006 | Login with empty username and valid password | Negative |
| TS-LOGIN-007 | Login with valid username and empty password | Negative |

## 2. Product Listing

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-PRODUCT-001 | Verify that products are displayed | Positive |
| TS-PRODUCT-002 | Verify that product information is displayed correctly | Positive |
| TS-PRODUCT-003 | Verify that product images are displayed | Positive |
| TS-PRODUCT-004 | Verify that product prices are displayed | Positive |
| TS-PRODUCT-005 | Verify that the Add to Cart button is available for products | Positive |
| TS-PRODUCT-006 | Verify that the Add to Cart button changes after adding a product | Positive |
| TS-PRODUCT-007 | Verify that the cart is updated after adding a product | Positive |


## 3. Product Sorting

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-SORT-001 | Verify that the sorting option is available | Positive |
| TS-SORT-002 | Verify that products are sorted correctly by name | Positive |
| TS-SORT-003 | Verify that products are sorted correctly by price | Positive |
| TS-SORT-004 | Verify that the selected sorting option is applied correctly | Positive |


## 4. Product Details

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-DETAILS-001 | Verify that the Product Details page opens when a product is selected | Positive |
| TS-DETAILS-002 | Verify that the product name is displayed correctly | Positive |
| TS-DETAILS-003 | Verify that the product image is displayed correctly | Positive |
| TS-DETAILS-004 | Verify that the product description is displayed | Positive |
| TS-DETAILS-005 | Verify that the product price is displayed correctly | Positive |
| TS-DETAILS-006 | Verify that the Add to Cart button is available | Positive |
| TS-DETAILS-007 | Verify that a product can be added to the cart from the Product Details page | Positive |
| TS-DETAILS-008 | Verify that the user can return to the Product Listing page from the Product Details page | Positive |

## 5. Shopping Cart

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-CART-001 | Verify that a product can be added to the shopping cart | Positive |
| TS-CART-002 | Verify that the cart displays the correct number of added items | Positive |
| TS-CART-003 | Verify that the added product is displayed in the shopping cart | Positive |
| TS-CART-004 | Verify that the product name and price are displayed correctly in the shopping cart | Positive |
| TS-CART-005 | Verify that a product can be removed from the shopping cart | Positive |
| TS-CART-006 | Verify that the cart is updated after removing a product | Positive |
| TS-CART-007 | Verify the behavior when adding multiple units of the same product | Positive |
| TS-CART-008 | Verify that multiple different products can be displayed in the shopping cart | Positive |
| TS-CART-009 | Verify that clicking the product name in the cart opens the corresponding Product Details page | Positive |
| TS-CART-010 | Verify that the cart is empty after all products are removed | Positive |

## 6. Checkout

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-CHECKOUT-001 | Verify that the user can proceed to Checkout from the Shopping Cart | Positive |
| TS-CHECKOUT-002 | Verify that the Customer Information form is displayed | Positive |
| TS-CHECKOUT-003 | Verify that the user cannot proceed with empty required fields | Negative |
| TS-CHECKOUT-004 | Verify that the user can proceed with valid customer information | Positive |
| TS-CHECKOUT-005 | Verify the validation behavior of the Postal Code field | Negative |
| TS-CHECKOUT-006 | Verify that the Order Summary displays the selected products correctly | Positive |
| TS-CHECKOUT-007 | Verify that product prices are displayed correctly in the Order Summary | Positive |
| TS-CHECKOUT-008 | Verify that the total price is calculated correctly | Positive |
| TS-CHECKOUT-009 | Verify that the user can complete the order | Positive |
| TS-CHECKOUT-010 | Verify that an order confirmation message is displayed after completing the order | Positive |

## 7. Logout

| Scenario ID | Scenario | Type |
|---|---|---|
| TS-LOGOUT-001 | Verify that the Logout option is available | Positive |
| TS-LOGOUT-002 | Verify that the user is logged out successfully | Positive |
| TS-LOGOUT-003 | Verify that the user is redirected to the Login page after logging out | Positive |
| TS-LOGOUT-004 | Verify that authenticated pages cannot be accessed after logging out | Functional |
| TS-LOGOUT-005 | Verify the behavior of other active tabs after logging out from one tab | Functional |

