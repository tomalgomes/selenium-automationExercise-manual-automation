# Test Scenarios

## 1. User Management

| Scenario ID | Scenario                                                          |
| ----------- | ----------------------------------------------------------------- |
| TS-UM-001   | Verify user can register with valid details                       |
| TS-UM-002   | Verify user cannot register with invalid details                  |
| TS-UM-003   | Verify user cannot register with already registered email         |
| TS-UM-004   | Verify user cannot register with empty required fields            |
| TS-UM-005   | Verify user can log in with valid credentials                     |
| TS-UM-006   | Verify user cannot log in with invalid credentials                |
| TS-UM-007   | Verify user cannot log in with empty credentials                  |
| TS-UM-008   | Verify user can log out successfully                              |
| TS-UM-009   | Verify authenticated user remains authenticated during active session |
| TS-UM-010   | Verify user session ends after logout                             |
| TS-UM-011   | Verify authenticated user can delete account                      |

## 2. Product Catalog

| Scenario ID | Scenario                                                                      |
| ----------- | ----------------------------------------------------------------------------- |
| TS-PC-001   | Verify user can search for products using valid keywords                      |
| TS-PC-002   | Verify system displays relevant results for searched queries                  |
| TS-PC-003   | Verify system behaviour when search is performed with empty input             |
| TS-PC-004   | Verify system displays "no results" message for invalid or non-matching input |
| TS-PC-005   | Verify case sensitivity does not affect search results                        |
| TS-PC-006   | Verify user can view product details from search results                      |
| TS-PC-007   | Verify product details page displays correct product information              |
| TS-PC-008   | Verify system displays products under respective categories                   |
| TS-PC-009   | Verify system displays products under respective brands                       |
| TS-PC-010   | Verify user can submit product review in product details page                 |

## 3. Cart Management

| Scenario ID | Scenario                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------ |
| TS-CM-001   | Verify user can add products to cart                                                                   |
| TS-CM-002   | Verify user can increase and decrease product quantity from product details page before adding to cart |
| TS-CM-002   | Verify user cannot enter invalid product quantity from product details page before adding to cart      |
| TS-CM-004   | Verify cart contains correct details for added product(s)                                              |
| TS-CM-005   | Verify user can remove product(s)                                                                      |
| TS-CM-006   | Verify cart retains added product(s) after page refresh or navigation                                  |

## 4. Checkout & Payment

| Scenario ID | Scenario                                                                          |
| ----------- | --------------------------------------------------------------------------------- |
| TS-CP-001   | Verify checkout page displays address details to authenticated user                   |
| TS-CP-002   | Verify system displays correct order details to authenticated user before payment     |
| TS-CP-003   | Verify authenticated user can add comment about their order                           |
| TS-CP-004   | Verify authenticated user can enter valid credit card details                         |
| TS-CP-005   | Verify system prevents payment with invalid credit card details                   |
| TS-CP-006   | Verify system prevents payment with empty credit card details                     |
| TS-CP-007   | Verify system displays order confirmation message after successful payment        |
| TS-CP-008   | Verify authenticated user can download invoice after order completion                 |
| TS-CP-009   | Verify user can navigate back to home page after order completion                 |
| TS-CP-010   | Verify guest or logged out user is restricted from accessing checkout and payment |

## 5. UI & Navigation

| Scenario ID | Scenario                                                                                                                                                                          |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TS-UN-001   | Verify guest user can navigate between Home, Products, Cart, Signup / Login, Test Cases, API Testing, Video Tutorials, and Contact us pages using the navigation menu             |
| TS-UN-002   | Verify authenticated user can navigate between Home, Products, Cart, Logout, Delete Account, Test Cases, API Testing, Video Tutorials, and Contact us pages using the navigation menu |
| TS-UN-003   | Verify key UI elements (menu, buttons, and headings) are visible on all pages                                                                                                     |
| TS-UN-004   | Verify layout remains consistent across different pages                                                                                                                           |
| TS-UN-005   | Verify correct page title or heading is displayed on each page                                                                                                                    |
| TS-UN-006   | Verify spellings and text formatting are consistent across all pages                                                                                                              |
