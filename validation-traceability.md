# Data Validation Traceability Matrix

| Validation Rule ID | Validation Rule | Test Case ID | Expected Outcome |
|---|---|---|---|
| VR01 | Employee ID must be unique | TC02 | Duplicate Employee ID is rejected |
| VR02 | Email Address must follow a valid email format | TC03 | Invalid email address is rejected |
| VR03 | Required employee fields must not be empty | TC06 | Employee record with a missing required field is rejected |
| VR04 | Contract End Date must not be earlier than Contract Start Date | TC04 | Invalid contract dates are rejected |
| VR05 | Employee records must be accessible using Employee ID | TC05 | Matching employee record is displayed |
