# Test Scenarios

## User Management

1. Verify user can register with valid details
2. Verify user cannot register with invalid details
3. Verify user cannot register with already registered email
4. Verify user cannot register with empty required fields
5. Verify user can log in with valid credentials
6. Verify user cannot log in with invalid credentials
7. Verify user cannot log in with empty credentials
8. Verify user can log out successfully
9. Verify user remains logged-in after login
10. Verify user session ends after logout

## Product Catalog

1. Verify user can search for products using valid keywords
2. Verify system displays relevant results for searched queries
3. Verify system behaviour when search is performed with empty input
4. Verify system displays "no results" message for invalid or non-matching input
5. Verify case sensitivity does not affect search results
6. Verify user can view product details from search results
7. Verify product details page displays correct product information
8. Verify system displays products under respective categories
9. Verify system displays products under respective brands
10. Verify user can submit product review in product details page

## Cart Management

1. Verify user can add products to cart
2. Verify user can increase and decrease product quantity from product details page before adding to cart
3. Verify system displays confirmation message when product is added to cart
4. Verify cart contains correct details for added product(s)
5. Verify user can remove product(s)
6. Verify cart retains added product(s) after page refresh or navigation

## Checkout & Payment

1. Verify checkout page displays address details to logged-in user
2. Verify system displays correct order details to logged-in user before payment
3. Verify logged-in user can add comment about their order
4. Verify logged-in user can enter valid credit card details
5. Verify system prevents payment with invalid credit card details
6. Verify system prevents payment with empty credit card details
7. Verify logged-in user can place order after entering valid payment details
8. Verify system displays order confirmation message after successful payment
9. Verify logged-in user can download invoice after order completion
10. Verify user can navigate back to home page after order completion
11. Verify guest or logged out user is restricted from accessing checkout and payment

## UI & Navigation

1. Verify user can navigate between Home, Products, Cart, Signup / Login, Test Cases, API Testing, Video Tutorials, and Contact us pages using the navigation menu
2. Verify key UI elements (menu, buttons, and headings) are visible on all pages
3. Verify layout remains consistent across different pages
4. Verify correct page title or heading is displayed on each page
5. Verify navigation menu links redirect to correct pages
6. Verify spellings and text formatting are consistent across all pages
