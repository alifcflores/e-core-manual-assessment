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

## Test Case #009 - Login: Empty UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Smoke Test                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Don't fill anything in the username field.<br>3. Don't fill anything in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |