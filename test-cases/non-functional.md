# Security Tests

## TC-010 - Brute Force Attack: Login Attempt Limitation

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | High                                                                                                     |
| **Type**           | Security                                                                                               |
| **Preconditions**  | Access to the system.                                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Enter a **valid username**.<br>3. Enter an **invalid password**.<br>4. Click on the login button.<br>5. Repeat the process until reaching the system's maximum allowed number of failed attempts.<br>6. After reaching the limit, observe the system's behavior regarding new login attempts. |
| **Post Conditions** | The system should block or limit further attempts after the maximum number of failures is reached.  |
| **Expected Result** | - The system should block or limit further login attempts after reaching the maximum number of failures.<br>- The system should provide an appropriate message indicating that the maximum number of attempts has been reached.<br>- The system should implement additional security measures, such as a captcha or temporary lockout, to prevent brute force attacks. |

<br>

## TC-011 - Verify Session Timeout Functionality

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | High                                                                                                     |
| **Type**           | Security                                                                                                |
| **Preconditions**  | 1. The user must be authenticated and logged into the system.<br>2. The session timeout must be configured in the system (e.g., 15 minutes of inactivity). |
| **Steps to Execute** | 1. Access the system and log in with a valid user.<br>2. Navigate to an internal page of the system.<br>3. Leave the browser inactive without interacting with the system for the configured session timeout period (e.g., 15 minutes).<br>4. After the timeout period, attempt to interact with the system (e.g., click on a link or button).<br>5. Observe the system’s response. |
| **Post Conditions** | 1. The session should be terminated after the specified inactivity period.<br>2. The system should redirect the user to the login page or display a session timeout message. |
| **Expected Result** | 1. After the inactivity period, the session should automatically expire.<br>2. The system should redirect the user to the login page or display a message indicating that the session has expired.<br>3. The system should not allow interaction with the interface without re-authentication. |

<br>

## TC-012 - Valid Login With Allowed Special Characters

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Scope**          | - Valid username with Special Characters Allowed<br>- Valid password with All Special Characters         |
| **Type**           | Security                                                                                                |
| **Preconditions**  | User must be registered in the system.                                                                  |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username with **special characters** allowed.<br>3. Fill in the field with a **valid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | User is redirected to the invoices page.                                                                |

<br>

## TC-013 - Invalid Login With Special Characters (Not Allowed)

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Scope**          | - Invalid username with Special Characters (Not Allowed)<br>- Invalid password with All Special Characters |
| **Type**           | Security                                                                                                |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **Invalid** username with **special characters** (not allowed).<br>3. Fill in the field with an **Invalid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | The system should display a message indicating the special characters are not allowed.                |

# Responsiveness Test Cases

## TC-014 - Responsiveness Test: 1920x1080 (Full HD)

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Medium                                                                                                  |
| **Type**           | Responsiveness                                                                                         |
| **Preconditions**  | Access to a device with a screen resolution of 1920x1080.                                                |
| **Steps to Execute** | 1. Open the system on a device with a 1920x1080 screen resolution.<br>2. Navigate through different pages and functionalities.<br>3. Observe the layout and functionality. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | The system layout and functionalities should be displayed correctly without any issues on a 1920x1080 resolution. |

<br>

## TC-015 - Responsiveness Test: 1366x768 (HD)

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Medium                                                                                                  |
| **Type**           | Responsiveness                                                                                         |
| **Preconditions**  | Access to a device with a screen resolution of 1366x768.                                                |
| **Steps to Execute** | 1. Open the system on a device with a 1366x768 screen resolution.<br>2. Navigate through different pages and functionalities.<br>3. Observe the layout and functionality. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | The system layout and functionalities should be displayed correctly without any issues on a 1366x768 resolution. |

<br>

## TC-016 - Responsiveness Test: 1440x900 (WXGA+)

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Medium                                                                                                  |
| **Type**           | Responsiveness                                                                                         |
| **Preconditions**  | Access to a device with a screen resolution of 1440x900.                                                |
| **Steps to Execute** | 1. Open the system on a device with a 1440x900 screen resolution.<br>2. Navigate through different pages and functionalities.<br>3. Observe the layout and functionality. |
| **Post Conditions** | N/A                                                                                                     |
| **Expected Result** | The system layout and functionalities should be displayed correctly without any issues on a 1440x900 resolution. |
