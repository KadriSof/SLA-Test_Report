# Sample Record Insertion

**Test Case ID:** TC011
**Test Case Title:** Insert a new sample record into the software’s database.
**Test Objective:** To verify that a user can successfully create a new sample record using the “**Sample Information Section**” tools.

---

**Captions:**

![**Sample information section:** a composite UI feature that includes all of the patient, doctor, and center information sections](Sample%20Record%20Insertion%2093e67af27f8b45b5b9532d937c978a15/Untitled.png)

**Sample information section:** a composite UI feature that includes all of the patient, doctor, and center information sections

---

**Preconditions**:

1. The user must have access.
2. The user must have permission to add a sample record. (Access Level 2)
3. The patient, doctor, and center information attachment is mandatory for completing the sample registration process.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Use the “**[Sample Information Section](Sample%20Record%20Insertion%2093e67af27f8b45b5b9532d937c978a15.md)**” widgets to fill in the new sample information.
4. Associate patient information by [searching](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Patient%20Record%20Search%2094435d6d34df49bc88ec77d68589289e.md) and [importing](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Patient%20Record%20Importing%2065ad0b523f8b40d0b680c8e3726e3747.md) the patient record using the “**Search Patient**” feature.
5. Associate doctor information by [searching](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Doctor%20Record%20Search%20e586aa341d634aa5a219c56cb9c2d839.md) and [importing](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Doctor%20Record%20Importing%204d01dfa880b343c19ba5d9f58f6306c0.md) the doctor record using the “**Search Doctor**” feature.
6. Associate center information by [searching](../Home%20Screen%20Data%20Search%20Tests%20807995878b7c4f7e8c0edf055e821cbd/Center%20Record%20Search%203a8c605f0d4b48259ff3ee8423052c79.md) and [importing](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Center%20Record%20Importing%20a641413fa7e14c96a1d99ac0de93e5b3.md) the center record using the “**Search Center**” feature.
7. Click on the "**Save**" button.

**Expected Results**:

1. The application should open without errors.
2. The user should be able to fill in the sample information without encountering any errors.
3. The user should be able to import all of the [patient](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Patient%20Record%20Importing%2065ad0b523f8b40d0b680c8e3726e3747.md), [doctor](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Doctor%20Record%20Importing%204d01dfa880b343c19ba5d9f58f6306c0.md), and [center](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Center%20Record%20Importing%20a641413fa7e14c96a1d99ac0de93e5b3.md) records without encountering any errors.
4. After clicking on the “**Save**” button, the sample record should be added to the database.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The sample information is added successfully.
3. The patient, doctor, and center records are imported successfully.
4. The sample record is registered successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully completes the sample registration procedure and receives a confirmation message through a dialog box.

**Severity:** High
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---