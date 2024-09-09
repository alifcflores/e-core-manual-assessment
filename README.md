# Scenarios Planned For Login Page
Two main software testing techniques were used to create the test scenarios.

#### Equivalence partitioning
Identifies all the main inputs (usually based on the business rule) so that they can be divided into smaller partitions.

#### Decision Table
In this case, the decision table is used to perform combinations between the possible inputs, to determine the real number of scenarios.

# Test Coverage
[![coverage.png](https://i.postimg.cc/RVPx65ZW/coverage.png)](https://postimg.cc/hf756Yxn)

I based the coverage calculation only on functional tests and categorized the login scenarios into 4 categories:

1. Fields Combinations
2. UpperCase
3. Max Length
4. Special Characters

### Explaining the Information in the Table Above
1. UserName: possible entries for username (valid, invalid, empty)
2. Password: possible entries for password (valid, invalid, empty)
3. Total Possible: Multiplied username entries X password entries.
4. Total Created: Count of created scenarios.

### Formula for Coverage %
```
(Total Created Scenarios / Total Possible Combinations) × 100
```

For the planned inputs, all possible combinations resulted in a Test Case. Therefore, 100% coverage in these areas.



## Possible Input Values
[![possible-input-values.png](https://i.postimg.cc/XNsPKk3D/possible-input-values.png)](https://postimg.cc/MXjtqRny)


## Fields Validations: UpperCase, Max Lenght and Special Characters
