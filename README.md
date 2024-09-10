# TEST PLAN

### Change History
- **Version 1.0** - [2024-09-08] - Initial creation of the test plan.

## Introduction
This test plan aims to validate the functionality of the login page of the Application. The goal is to ensure that all fields on the login page accept expected inputs and handle invalid inputs appropriately. The plan includes functional tests, as well as additional tests to verify the page's security and responsiveness.

## Objectives of the Test
1. Verify that the input fields correctly accept and process valid entries.
2. Validate that the system handles invalid entries correctly and provides appropriate error messages.
3. Test the security of the login page to ensure there are no vulnerabilities.
4. Evaluate the responsiveness of the login page across different devices and screen sizes.

## Definitions and Terms
- **Valid**: username or password registered in the system.
- **Invalid**: username or password does not exist in the system.
- **Empty**: A field that does not contain any data.

## Test Scenarios
Two main software testing techniques were used to create the test scenarios.

### Equivalence Partitioning
Identifies all the main inputs (usually based on business rules) so that they can be divided into smaller partitions.

### Decision Table
In this case, the decision table is used to perform combinations between possible inputs to determine the real number of scenarios.

## Test Coverage
[![coverage.png](https://i.postimg.cc/RVPx65ZW/coverage.png)](https://postimg.cc/hf756Yxn)

Coverage calculation was based solely on functional tests and categorized into 4 areas:

1. **Fields Combinations**: Divided into three partitions: valid, invalid, and empty.
2. **UpperCase**
3. **Max Length**
4. **Special Characters**: Divided into allowed and not allowed special characters

### Explaining the Information in the Table Above
1. **UserName**: Possible entries for the username field.
2. **Password**: Possible entries for the password field.
3. **Total Possible**: Multiplied username entries X password entries.
4. **Total Created**: Count of created scenarios.

### Formula for Coverage %
```
(Total Created Scenarios / Total Possible Combinations) × 100
```

For the planned inputs, all possible combinations resulted in a test case. Therefore, 100% coverage in these areas.

### Possible Input Values
[![possible-input-values.png](https://i.postimg.cc/XNsPKk3D/possible-input-values.png)](https://postimg.cc/MXjtqRny)

### Fields Validations: UpperCase, Max Length, and Special Characters
[![fields-valdation.png](https://i.postimg.cc/R0W5RtWY/fields-valdation.png)](https://postimg.cc/p9M6VpYQ)

## Other Test Types
In addition to the test cases mentioned above, scenarios for Smoke and non-functional tests (security and responsiveness) were created.

1. Smoke Testing
Objective: Quickly verify that essential functionalities are working after a new build.

3. Non-Functional Testing
Objective: Assess aspects beyond functionality, including security, performance, and usability.

## Detailed Test Cases
In this repository, there is a `test-cases` folder where tests are separated by type of testing. 

[CLICK TO ACCESS](https://github.com/alifcflores/e-core-manual-assessment/tree/main/test-cases)

### Template:

TC-000 - Title

| **Attribute**      | **Details**                                                                                           |
|--------------------|--------------------------------------------------------------------------------------------------------|
| **Priority**       | [Priority]                                                                                           |
| **Type**           | [Type]                                                                                               |
| **Preconditions**  | [Preconditions]                                                                                      |
| **Steps to Execute** | 1. [Step 1]<br>2. [Step 2]<br>3. [Step 3]<br>4. [Step 4]                                           |
| **Post Conditions** | [Post Conditions]                                                                                   |
| **Expected Result** | [Expected Result]                                                                                   |

## Test Execution
The execution of scenarios and found bugs are compiled in the link below:

[CLICK TO ACCESS](https://docs.google.com/spreadsheets/d/e/2PACX-1vSnlVwNHbDn67CGCWle_xnLdPK5QzsiFrtIcElnyoO9QKVNnuzn4LCPBezHOrKcr29ree0wVYBVUGo_/pubhtml#) 

*Note: There are tabs at the top of the screen for navigation.*

## Exploratory Tests
Bugs found are described in detail on the [ISSUES](https://github.com/alifcflores/e-core-manual-assessment/issues) tab of this repository.

*Note: In the spreadsheet above, you can also access a bug by clicking on the ID link (first column).*

## Criteria for Acceptance
- **Valid Input**: The system must allow login with valid inputs and redirect the user to the main page.
- **Invalid Input**: The system must display appropriate error messages for invalid inputs.
- **Empty Field**: The system must prompt the user to fill in all required fields.

## Risks and Considerations
- **Connectivity Issues**: Failures in server connection may impact login tests.
- **Test Environment**: Set up correctly to reflect the production environment.
