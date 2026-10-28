# Employee Data Test Cases

| Test ID | Scenario | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC01 | Add employee with valid data | EMP001, Sara Ahmed, sara@gmail.com | Employee record is saved successfully | Not Executed | Not Run |
| TC02 | Add employee with duplicate ID | EMP001 | The system rejects the duplicate Employee ID | Not Executed | Not Run |
| TC03 | Enter an invalid email address | sara.gmail.com | The system rejects the invalid email address | Not Executed | Not Run |
| TC04 | Enter contract end date before contract start date | Start: 2026-11-10, End: 2026-11-05 | The system rejects the contract end date and displays an error message | Not Executed | Not Run |
| TC05 | Search for an employee using Employee ID | EMP001 | The system displays the matching employee record | Not Executed | Not Run |
| TC06 | Add employee with missing required field | EMP002, Email Address: Empty | The system rejects the employee record and displays an error message | Not Executed | Not Run |
