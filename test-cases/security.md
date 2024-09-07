# Security - Test Cases

<br>

## Test Case #010 - Valid Login With Allowed Special Characters

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Scope**          | - Valid username with Special Characters Allowed<br>- Valid password with All Special Characters          |
| **Type**           | Security                                                                                                 |
| **Preconditions**  | User must be registered in the system.                                                                   |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with a **valid** username with **special characters** allowed.<br>3. Fill in the field with a **valid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | N/A                                                                                                      |
| **Expected Result** | User is redirected to the invoices page.                                                                 |

<br><br>

## Test Case #011 - Invalid Login With Special Characters (Not Allowed)

| **Atributo**       | **Detalhes**                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **Priority**       | Highest                                                                                                  |
| **Scope**          | - Invalid username with Special Characters (Not Allowed)<br>- Invalid password with All Special Characters|
| **Type**           | Security                                                                                                 |
| **Preconditions**  | N/A                                                                                                      |
| **Steps to Execute** | 1. Access the login page.<br>2. Fill in the field with an **invalid** username with **special characters** not allowed.<br>3. Fill in the field with an **invalid** password with all **special characters**.<br>4. Click on the login button. |
| **Post Conditions** | Login should not be performed.                                                                           |
| **Expected Result** | - The system should display a message informing the user that the credentials are invalid.<br>- The request should behave the same way as using regular characters. |