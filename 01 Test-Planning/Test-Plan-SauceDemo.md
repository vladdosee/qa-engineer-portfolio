Test Plan — SauceDemo

1. Document Information

Project:	SauceDemo
Application:	https://www.saucedemo.com
Testing Type:	Web Application Testing
Test Management Tool:	TestRail
Operating System:	macOS
Browser: Safari


2. Test Objectives
The objective of testing is to verify the functionality of the SauceDemo web application.
The testing covers:
•User login
•Login validation
•Locked user login
•Session persistence
•Logout
•Product display
•Product information
•Product sorting
•Product details
•Shopping cart
•Checkout
•Order completion
•Order confirmation


3. Test Scope

Authentication
•Login with valid credentials
•Login with invalid username
•Login with invalid password
•Login with empty username
•Login with empty password
•Login with empty username and password
•Login with locked account
•Session persistence after page refresh
•Logout

Products
•Product list display
•Product information
•Sorting products by price from low to high
•Sorting products by price from high to low
•Opening product details

Shopping Cart
•Adding a product to the cart
•Removing a product from the cart
•Cart contents
•Product persistence after navigation

Checkout
•Opening the checkout page
•Checkout information fields
•Checkout with valid information
•Validation of empty checkout information
•Validation of missing first name
•Validation of missing last name
•Validation of missing postal code
•Checkout overview
•Completing an order
•Order confirmation


4. Test Approach
The application is tested using functional testing.

The test suite contains:
•Positive test cases
•Negative test cases
•UI verification
•Input validation
•Navigation verification

Test cases are created and maintained in TestRail.

Each test case contains:
•Test case title
•Preconditions
•Test steps
•Expected results
•Testing type

5. Test Data
The following SauceDemo users are used:

standard_user:	    Main test account
locked_out_user:    Locked account test

Password:           secret_sauce

standard_user is used for the main test scenarios.
locked_out_user is used for testing locked account behaviour.


6. Test Cases
The current TestRail test suite contains 27 test cases.

Authentication:
•TC001 – User is logged in successfully with valid credentials
•TC002 – Login fails if password is invalid
•TC003 – Login fails if username is invalid
•TC004 – User is not able to login with empty username
•TC005 – User is not able to login with empty password
•TC006 – User login fails with empty username and password fields
•TC007 – User is not able to login with locked account
•TC008 – User session persists after page refresh
•TC009 – User can log out successfully

Products:
•TC010 – Products are displayed correctly after login
•TC011 – Product information is displayed correctly
•TC014 – Products are sorted by price from low to high successfully
•TC015 – Products are sorted by price from high to low successfully
•TC016 – User opens product details successfully

Shopping Cart:
•TC012 – Cart shows single added item after it's added to the cart
•TC013 – User removes a product from the cart successfully
•TC017 – Added product remains in the cart after navigation

Checkout:
•TC018 – User opens the checkout page successfully
•TC019 – Checkout information fields are displayed correctly
•TC020 – User proceeds to checkout with valid information successfully
•TC021 – User cannot proceed with empty checkout information
•TC022 – User cannot proceed without a first name
•TC023 – User cannot proceed without a last name
•TC024 – User cannot proceed without a postal code
•TC025 – Checkout overview displays order information correctly
•TC026 – User completes the order successfully
•TC027 – Order confirmation message is displayed correctly

7. The current SauceDemo testing project includes:
•Test Plan
•Test Scenarios
•Test Cases
Test cases are created and maintained in TestRail.


8. Test Summary
The SauceDemo project contains 27 TestRail test cases covering:
•Authentication
•Products
•Shopping Cart
•Checkout
•The test cases include positive and negative scenarios and define the expected behavior of the application.
