
# Employee Data Test Cases

| Test ID | Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC01 | Add employee with valid data | EMP001, Sara Ahmed | Employee record is saved |
| TC02 | Add employee with duplicate ID | EMP001 | System rejects duplicate ID |
| TC03 | Enter invalid email | sara.gmail.com | System rejects invalid email |
| TC04 | Enter end date before start date | Start: 2026-11-10, End: 2026-11-05 | The system rejects the end date and displays an error message |
| TC05 | Search employee by ID | EMP001 | The system displays employee data matching the entered Employee ID |
| TC06 | Submit leave request using Employee ID | EMP001, Start: 2026-11-01, End: 2026-11-03 | The system accepts the leave request and records its status as Pending |
