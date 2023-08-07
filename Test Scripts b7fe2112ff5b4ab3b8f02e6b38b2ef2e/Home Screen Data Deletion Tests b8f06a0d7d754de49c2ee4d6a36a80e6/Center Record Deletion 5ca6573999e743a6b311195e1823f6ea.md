# Center Record Deletion

**Test Case ID:** TC020
**Test Case Title:** Delete a center's record from the software’s database.
**Test Objective:** To verify that a user can successfully delete a registered center record from the database.

---

**Captions:**

![**Bin Icon Button:** an icon button for calling the center record information deletion procedure.](Center%20Record%20Deletion%205ca6573999e743a6b311195e1823f6ea/Untitled.png)

**Bin Icon Button:** an icon button for calling the center record information deletion procedure.

---

**Preconditions**:

1. The user must be registered in the database.
2. The user must have permission to delete doctor records. (Access Level 1)
3. The center's record must not be attached to an already registered sample.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Click on the “**Search**” button in the doctor information section.
4. Select a doctor's record.
5. Click on the **bin icon button** on the right side of the [center record item](Center%20Record%20Deletion%205ca6573999e743a6b311195e1823f6ea.md).

**Expected Results**:

1. The application should open without errors.
2. The “[Search Center](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Center%20Record%20Search%203a8c605f0d4b48259ff3ee8423052c79.md)” popup should open without errors.
3. The center record deletion process should be executed without errors.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The “[Search Doctor](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Doctor%20Record%20Search%20e586aa341d634aa5a219c56cb9c2d839.md)” popup is opened successfully.
3. The center record is removed successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully deletes a center's record from the database.

**Severity:** High 
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---