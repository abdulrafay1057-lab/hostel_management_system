# Unit Testing – Hostel Management System

## 1. Purpose

Unit testing verifies individual functions and components of the Hostel Management System independently to ensure that each performs its intended task correctly.

## 2. Test Cases

| Test ID | Function / Component | Test Scenario | Expected Result |
|---|---|---|---|
| UT-01 | Student Registration | Enter valid student details | Student details are accepted |
| UT-02 | Student Registration | Leave a required field empty | Validation error is displayed |
| UT-03 | Login Validation | Enter valid credentials | Login validation succeeds |
| UT-04 | Room Availability | Check a room with available beds | Room is marked available |
| UT-05 | Room Availability | Check a fully occupied room | Room is marked unavailable |
| UT-06 | Bed Allocation | Allocate an available bed | Allocation is accepted |
| UT-07 | Bed Allocation | Allocate an already occupied bed | Duplicate allocation is rejected |
| UT-08 | Fee Validation | Enter a valid non-negative payment amount | Amount passes validation |
| UT-09 | Complaint Validation | Submit a complaint with a description | Complaint passes validation |
| UT-10 | Visitor Records | Enter an exit time earlier than entry time | Invalid time sequence is rejected |

## 3. Testing Procedure

1. Identify the function to be tested.
2. Prepare valid and invalid input values.
3. Execute the function independently.
4. Compare the actual result with the expected result.
5. Record the test outcome and any defects.

## 4. Test Execution Status

The test cases listed above are planned test cases. Their execution status must be updated after the corresponding functions have been implemented and tested.

| Test Status | Meaning |
|---|---|
| Not Run | Testing has not been performed |
| Pass | Actual result matches expected result |
| Fail | Actual result differs from expected result |

## 5. Conclusion

Unit testing will help identify errors in individual components before they are integrated into the complete Hostel Management System. Testing should be performed again whenever relevant functions are modified.

