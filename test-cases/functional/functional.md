# Test Cases

## Test Case #002 - Login: Valid UserName - Invalid Password

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Fill in the field with a **Invalid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #003 - Login: Valid UserName - Empty Password

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username.<br>3. Don't fill anything in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #004 - Login: Invalid UserName - Valid Password (of some registered user)

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **Invalid** username.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #005 - Login: Invalid UserName - Invalid Password

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | N/A                                                                                                      |
| **Steps to Execute** | 1. Access the login page.<br>2. Enter an **Invalid** username in the username field.<br>3. Enter an **Invalid** password in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #006 - Login: Invalid UserName - Empty Password

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | N/A                                                                                                      |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **Invalid** username.<br>3. Don't fill anything in the password field.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #007 - Login: Empty UserName - Valid Password (of some registered user)

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Don't fill anything in the username field.<br>3. Fill in the field with a **Valid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |

---

## Test Case #008 - Login: Empty UserName - Invalid Password 

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Type**           | Functional                                                                                               |
| **Preconditions**  | N/A                                                                                                      |
| **Steps to Execute** | 1. Access the login page.<br>2. Don't fill anything in the username field.<br>3. Fill in the field with a **Invalid** password.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | The system should display a message informing the user that the credentials are invalid.                 |