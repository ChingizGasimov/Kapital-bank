# Login Page – Test Cases

| Test Case ID | Scenario ID | Title | Precondition | Test Steps | Test Data | Expected Result |
|--------------|------------|--------|-------------|------------|------------|----------------|
| TC-01 | TS-01 | Valid Login | User is registered | 1. Open login page <br> 2. Enter valid username <br> 3. Enter valid password <br> 4. Click Login | valid_user / valid_pass | User is redirected to Dashboard |
| TC-02 | TS-02 | Invalid Password | User exists | 1. Open login page <br> 2. Enter valid username <br> 3. Enter invalid password <br> 4. Click Login | valid_user / wrong_pass | Error message is displayed |
| TC-03 | TS-03 | Invalid Username | User does not exist | 1. Open login page <br> 2. Enter invalid username <br> 3. Enter valid password <br> 4. Click Login | wrong_user / valid_pass | Error message is displayed |
| TC-04 | TS-04 | Empty Fields | No precondition | 1. Open login page <br> 2. Leave fields empty <br> 3. Click Login | empty | Validation message appears |
| TC-05 | TS-05 | Forgot Password Redirect | No precondition | 1. Open login page <br> 2. Click "Forgot Password" | N/A | User is redirected to recovery page |

## Credit Calculator – Test Cases

| Test Case ID | Scenario ID | Title | Precondition | Test Steps | Test Data | Expected Result |
|--------------|------------|--------|-------------|------------|------------|----------------|
| TC-07 | TS-08 | Valid Credit Calculation | Calculator page is open | 1. Enter loan amount <br> 2. Select loan period <br> 3. Click "Calculate" | 10000 AZN / 12 months | Monthly payment is calculated correctly |
| TC-08 | TS-09 | Zero Amount Validation | Calculator page is open | 1. Enter 0 in amount field <br> 2. Select period <br> 3. Click "Calculate" | 0 AZN | Error message is displayed |
| TC-09 | TS-10 | Negative Amount Validation | Calculator page is open | 1. Enter negative value <br> 2. Click "Calculate" | -500 AZN | System does not accept negative values |
| TC-10 | TS-11 | Exceed Maximum Limit | Calculator page is open | 1. Enter amount above maximum limit <br> 2. Click "Calculate" | 1,000,000 AZN | Warning message is displayed |
| TC-11 | TS-12 | Result Format Validation | Calculator page is open | 1. Enter valid data <br> 2. Click "Calculate" | 5000 AZN / 6 months | Result is displayed in correct currency and format |
| TC-12 | TS-13 | Different Loan Periods | Calculator page is open | 1. Enter loan amount <br> 2. Select different periods <br> 3. Click "Calculate" | 10000 AZN / 24 months | Monthly payment updates correctly |

## Search Function – Test Cases

| Test Case ID | Scenario ID | Title | Precondition | Test Steps | Test Data | Expected Result |
|--------------|------------|--------|-------------|------------|------------|----------------|
| TC-13 | TS-14 | Valid Search Keyword | Home page is open | 1. Enter product name in search field <br> 2. Press Enter | credit | Relevant results are displayed |
| TC-14 | TS-15 | Case Sensitivity Check | Home page is open | 1. Enter same keyword in uppercase <br> 2. Press Enter | CREDIT | Results match lowercase search |
| TC-15 | TS-16 | Special Characters Search | Home page is open | 1. Enter special characters <br> 2. Press Enter | @#$% | System does not crash and shows proper message |
| TC-16 | TS-17 | Empty Search Validation | Home page is open | 1. Leave search field empty <br> 2. Press Enter | empty | Validation message is displayed |
| TC-17 | TS-18 | Search Result Relevance | Home page is open | 1. Search for keyword <br> 2. Review results | loan | Only relevant results are displayed |
