# Login Page – Test Cases

| Test Case ID | Scenario ID | Title | Precondition | Test Steps | Test Data | Expected Result |
|--------------|------------|--------|-------------|------------|------------|----------------|
| TC-01 | TS-01 | Valid Login | User is registered | 1. Open login page <br> 2. Enter valid username <br> 3. Enter valid password <br> 4. Click Login | valid_user / valid_pass | User is redirected to Dashboard |
| TC-02 | TS-02 | Invalid Password | User exists | 1. Open login page <br> 2. Enter valid username <br> 3. Enter invalid password <br> 4. Click Login | valid_user / wrong_pass | Error message is displayed |
| TC-03 | TS-03 | Invalid Username | User does not exist | 1. Open login page <br> 2. Enter invalid username <br> 3. Enter valid password <br> 4. Click Login | wrong_user / valid_pass | Error message is displayed |
| TC-04 | TS-04 | Empty Fields | No precondition | 1. Open login page <br> 2. Leave fields empty <br> 3. Click Login | empty | Validation message appears |
| TC-05 | TS-05 | Forgot Password Redirect | No precondition | 1. Open login page <br> 2. Click "Forgot Password" | N/A | User is redirected to recovery page |
