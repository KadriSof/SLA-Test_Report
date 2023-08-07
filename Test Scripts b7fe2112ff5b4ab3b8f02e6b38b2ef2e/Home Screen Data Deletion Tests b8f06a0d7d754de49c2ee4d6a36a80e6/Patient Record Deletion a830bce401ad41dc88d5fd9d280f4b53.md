# Patient Record Deletion

**Test Case ID:** TC018
**Test Case Title:** Delete a patient record from the software’s database.
**Test Objective:** To verify that a user can successfully delete a registered patient record from the database.

---

**Captions:**

![**Bin Icon Button:** an icon button for calling the patient record information deletion procedure.](Patient%20Record%20Deletion%20a830bce401ad41dc88d5fd9d280f4b53/Untitled.png)

**Bin Icon Button:** an icon button for calling the patient record information deletion procedure.

---

**Preconditions**:

1. The user must be registered in the database.
2. The user must have permission to delete sample records. (Access Level 1)
3. The patient record must not be attached to an already registered sample.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Click on the “**Search**” button in the patient information section.
4. Select a patient record.
5. Click on the **bin icon button** on the right side of the [patient record item](Patient%20Record%20Deletion%20a830bce401ad41dc88d5fd9d280f4b53.md).

**Expected Results**:

1. The application should open without errors.
2. The “[Search Patient](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Patient%20Record%20Search%2094435d6d34df49bc88ec77d68589289e.md)” popup should open without errors.
3. The patient record deletion process should be executed without errors.
4. After clicking the **bin icon button**, the patient record information should be deleted from the database.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The “[Search Patient](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Patient%20Record%20Search%2094435d6d34df49bc88ec77d68589289e.md)” popup is opened successfully.
3. The patient record is removed successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully deletes a patient record from the database.

**Severity:** High 
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---