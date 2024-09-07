# Test Cases Summary

## Smoke Test Cases

| **Test Case ID** | **Description**                                    |
|------------------|----------------------------------------------------|
| [TC-001](#test-case-001) | Login: Valid UserName - Valid Password            |
| [TC-002](#test-case-002) | Login: Empty UserName - Empty Password            |

## Functional Test Cases

| **Test Case ID** | **Description**                                    |
|------------------|----------------------------------------------------|
| [TC-003](#test-case-003) | Login: Valid UserName - Invalid Password          |
| [TC-004](#test-case-004) | Login: Valid UserName - Empty Password            |
| [TC-005](#test-case-005) | Login: Invalid UserName - Valid Password          |
| [TC-006](#test-case-006) | Login: Invalid UserName - Invalid Password        |
| [TC-007](#test-case-007) | Login: Invalid UserName - Empty Password          |
| [TC-008](#test-case-008) | Login: Empty UserName - Valid Password            |
| [TC-009](#test-case-009) | Login: Empty UserName - Invalid Password          |

## Security Test Cases

| **Test Case ID** | **Description**                                    |
|------------------|----------------------------------------------------|
| [TC-010](#test-case-015) | Brute Force Attack: Login Attempt Limitation      |
| [TC-011](#test-case-010) | Valid Login With Allowed Special Characters       |
| [TC-012](#test-case-011) | Invalid Login With Special Characters (Not Allowed)|

## Responsiveness Test Cases

| **Test Case ID** | **Description**                                    |
|------------------|----------------------------------------------------|
| [TC-013](#test-case-012) | Responsiveness Test: 1920x1080 (Full HD)          |
| [TC-014](#test-case-013) | Responsiveness Test: 1366x768 (HD)                |
| [TC-015](#test-case-014) | Responsiveness Test: 1440x900 (WXGA+)             |


# Smoke - Test Cases
<br>

## Test Case #001 - Login: Valid UserName - Valid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Smoke Test                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Fill in the field with a **valid** password.<br>4. Click on the login button. |
| **Post Conditions** | User is logged in successfully.                                                                          |
| **Expected Result** | Redirected to the invoices page.                                                                        |

<br><br>

## Test Case #002 - Login: Empty UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Smoke Test                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Don't fill anything in the username field.<br>3. Don't fill anything in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

---

# Functional Test Cases
<br>

## Test Case #003 - Login: Valid UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Fill in the field with an **Invalid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #004 - Login: Valid UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Leave the password field empty.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #005 - Login: Invalid UserName - Valid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **Invalid** username.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #006 - Login: Invalid UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Enter an **Invalid** username in the username field.<br>3. Enter an **Invalid** password in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #007 - Login: Invalid UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **Invalid** username.<br>3. Leave the password field empty.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #008 - Login: Empty UserName - Valid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Leave the username field empty.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br><br>

## Test Case #009 - Login: Empty UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Leave the username field empty.<br>3. Enter an **Invalid** password in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

---

# Security - Test Cases
<br>

## Test Case #010 - Brute Force Attack: Login Attempt Limitation

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | High                                                                                                     |
| **Type**           | Security                                                                                               |
| **Preconditions**  | Access to the system.                                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Enter a **valid username**.<br>3. Enter an **invalid password**.<br>4. Click on the login button.<br>5. Repeat the process until reaching the system's maximum allowed number of failed attempts.<br>6. After reaching the limit, observe the system's behavior regarding new login attempts. |
| **Post Conditions** | The system should block or limit further attempts after the maximum number of failures is reached.                                                            |
| **Expected Result** | - The system should block or limit further login attempts after reaching the maximum number of failures.<br>- The system should provide an appropriate message indicating that the maximum number of attempts has been reached.<br>- The system should implement additional security measures, such as a captcha or temporary lockout, to prevent brute force attacks. |

<br><br>

## Test Case #011 - Valid Login With Allowed Special Characters

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Scope**          | - Valid username with Special Characters Allowed<br>- Valid password with All Special Characters         |
| **Type**           | Security                                                                                                |
| **Preconditions**  | User must be registered in the system.                                                                  |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username with **special characters** allowed.<br>3. Fill in the field with a **valid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | User is redirected to the invoices page.                                                                |

<br><br>

## Test Case #012 - Invalid Login With Special Characters (Not Allowed)

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Scope**          | - Invalid username with Special Characters (Not Allowed)<br>- Invalid password with All Special Characters |
| **Type**           | Security                                                                                                |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2.

 Fill in the field with an **Invalid** username with **special characters** (not allowed).<br>3. Fill in the field with an **Invalid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | The system should display a message indicating the special characters are not allowed.                |
