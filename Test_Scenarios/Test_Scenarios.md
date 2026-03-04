Kapital Bank – Test Scenarios
Project Overview

This document contains high-level test scenarios designed for testing the public website of Kapital Bank (for practice purposes only).

The goal of this project is to demonstrate manual QA skills including:

Functional Testing

Negative Testing

Input Validation

UI Verification

🔐 Login Page – Test Scenarios

Authentication and validation behavior testing.

Scenario ID	Description
TS-01	User should be able to login with valid credentials
TS-02	Login should fail when an invalid password is entered
TS-03	Login should not be possible with empty input fields
TS-04	“Forgot Password” link should redirect to the correct recovery page
TS-05	Proper error message should be displayed when invalid credentials are entered
TS-06	Account should be temporarily locked after multiple failed login attempts
💳 Credit Calculator – Test Scenarios

Business logic and input validation testing.

Scenario ID	Description
TS-07	Correct calculation should be performed when valid amount and period are entered
TS-08	Error message should be displayed when zero or negative values are entered
TS-09	Warning should be displayed when entered amount exceeds maximum loan limit
TS-10	Calculation result should be displayed in correct format on the UI
TS-11	Monthly payment should update correctly when loan period changes
🔎 Search Function – Test Scenarios

Testing the internal search functionality of the website.

Scenario ID	Description
TS-12	Relevant results should be displayed when a valid product or service name is entered
TS-13	Search results should not change when using uppercase or lowercase letters
TS-14	System should not crash when special characters are entered
TS-15	Appropriate message should be displayed for empty search query
TS-16	Search results should be relevant to the entered keyword
