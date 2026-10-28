# Employee Data Test Cases

| Test ID | Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC01 | Add employee with valid data | EMP001, Sara Ahmed, sara@gmail.com | Employee record is saved successfully |
| TC02 | Add employee with duplicate ID | EMP001 | The system rejects the duplicate Employee ID |
| TC03 | Enter an invalid email address | sara.gmail.com | The system rejects the invalid email address |
| TC04 | Enter contract end date before contract start date | Contract Start Date: 2026-11-10, Contract End Date: 2026-11-05 | The system rejects the contract end date and displays an error message |
| TC05 | Search for an employee using Employee ID | EMP001 | The system displays the employee record matching the entered Employee ID |
