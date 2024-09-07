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

## TC-003 - Login: Valid UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Fill in the field with an **Invalid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-004 - Login: Valid UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Leave the password field empty.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-005 - Login: Invalid UserName - Valid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **Invalid** username.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-006 - Login: Invalid UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Enter an **Invalid** username in the username field.<br>3. Enter an **Invalid** password in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-007 - Login: Invalid UserName - Empty Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **Invalid** username.<br>3. Leave the password field empty.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-008 - Login: Empty UserName - Valid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Leave the username field empty.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |

<br>

## TC-009 - Login: Empty UserName - Invalid Password

| **Attribute**      | **Details**                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                 |
| **Type**           | Functional                                                                                              |
| **Preconditions**  | N/A                                                                                                     |
| **Steps to Execute** | 1. Access the login page.<br>2. Leave the username field empty.<br>3. Enter an **Invalid** password in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                          |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                |