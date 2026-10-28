
# Employee Data Test Cases

| Test ID | Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC-01 | Add employee with valid data | EMP001, Sara Ahmed | Employee record is saved |
| TC-02 | Add employee with duplicate ID | EMP001 | System rejects duplicate ID |
| TC-03 | Enter invalid email | sara.gmail.com | System rejects invalid email |
| TC-04 | Enter end date before start date | Start: 2026-11-10, End: 2026-11-05 | System rejects invalid dates |
