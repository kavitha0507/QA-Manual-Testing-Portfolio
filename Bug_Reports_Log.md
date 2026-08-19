Sample Bug Report 1 (Functional / Validation Defect)
Bug ID: BUG_01

Bug Title: Checkout proceeds successfully even when the Postal/Zip Code field is left blank.

Module: Checkout

Severity / Priority: High / Medium

Environment: Chrome Browser (Desktop), SauceDemo v1.0

Pre-conditions: User has added an item to the cart and navigated to the checkout information page.

Steps to Reproduce:

Enter a valid First Name (e.g., "Kavitha").

Enter a valid Last Name (e.g., "Mynala").

Leave the Postal/Zip Code field completely blank.

Click on the Continue button.

Expected Result: The system should display a validation error message stating that the Postal Code field is mandatory and prevent the user from proceeding to the overview page.

Actual Result: The system bypasses the blank postal code field and successfully redirects the user to the checkout overview page.

Status: Open / Active

Sample Bug Report 2 (UI / Error Handling Defect)
Bug ID: BUG_02

Bug Title: Generic error message displayed when locking out standard user credentials.

Module: Login

Severity / Priority: Medium / Low

Environment: Chrome Browser (Desktop), SauceDemo v1.0

Pre-conditions: User is on the application login page.

Steps to Reproduce:

Enter the locked-out username (locked_out_user).

Enter any valid password.

Click the Login button.

Expected Result: The error message should explicitly guide the user or clearly state that the account has been temporarily suspended or locked out due to multiple attempts.

Actual Result: The system displays a standard mismatch error ("Username and password do not match") instead of indicating the account lock status.

Status: Open / Active
