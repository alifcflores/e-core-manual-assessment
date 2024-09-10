# Scenarios Planned For Login Page
Two main software testing techniques were used to create the test scenarios.

#### Equivalence Partitioning
Identifies all the main inputs (usually based on business rules) so that they can be divided into smaller partitions. 

#### Decision Table
In this case, the decision table is used to perform combinations between possible inputs to determine the real number of scenarios.

# Test Coverage
[![coverage.png](https://i.postimg.cc/RVPx65ZW/coverage.png)](https://postimg.cc/hf756Yxn)

I based the coverage calculation solely on functional tests and categorized the login scenarios into 4 categories:

1. Fields Combinations: divided into three partitions: valid, invalid and empty.
2. UpperCase
3. Max Length
4. Special Characters: divided into allow and not allow special characters

### Explaining the Information in the Table Above
1. UserName: possible entries for username field
2. Password: possible entries for password field
3. Total Possible: Multiplied username entries X password entries.
4. Total Created: Count of created scenarios.

### Formula for Coverage %
```
(Total Created Scenarios / Total Possible Combinations) × 100
```

For the planned inputs, all possible combinations resulted in a Test Case. Therefore, 100% coverage in these areas.

## Possible Input Values
[![possible-input-values.png](https://i.postimg.cc/XNsPKk3D/possible-input-values.png)](https://postimg.cc/MXjtqRny)

## Fields Validations: UpperCase, Max Length, and Special Characters
[![fields-valdation.png](https://i.postimg.cc/R0W5RtWY/fields-valdation.png)](https://postimg.cc/p9M6VpYQ)

## Other Test Cases
In addition to the test cases mentioned above, scenarios for Smoke and non-functional tests (security and responsiveness) were created.

<br>

# Detailed Test Cases
In this repository, there is a `test-cases` folder where tests are separated by type of testing. <br>

[CLICK TO ACCESS](https://github.com/alifcflores/e-core-manual-assessment/tree/main/test-cases)

#### Template:

TC-000 - Title

| **Attribute**      | **Details**                                                                                           |
|--------------------|--------------------------------------------------------------------------------------------------------|
| **Priority**       | [Priority]                                                                                           |
| **Type**           | [Type]                                                                                               |
| **Preconditions**  | [Preconditions]                                                                                      |
| **Steps to Execute** | 1. [Step 1]<br>2. [Step 2]<br>3. [Step 3]<br>4. [Step 4]                                           |
| **Post Conditions** | [Post Conditions]                                                                                   |
| **Expected Result** | [Expected Result]                                                                                   |

<br>

# Test Execution
The execution of scenarios and found bugs are compiled in the link below:

[CLICK TO ACCESS](https://docs.google.com/spreadsheets/d/e/2PACX-1vSnlVwNHbDn67CGCWle_xnLdPK5QzsiFrtIcElnyoO9QKVNnuzn4LCPBezHOrKcr29ree0wVYBVUGo_/pubhtml#) 
<br><br>
*Note: There are tabs at the top of the screen for navigation.*

# Exploratory Tests
The bugs found are described in detail on the [ISSUES](https://github.com/alifcflores/e-core-manual-assessment/issues) tab of this repository.
<br><br>

*Note: In the spreadsheet above, you can also access a bug by clicking on the ID link (first column).*
