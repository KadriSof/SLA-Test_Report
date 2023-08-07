# Doctor Record Search

**Test Case ID:** TC004
**Test Case Title:** Search for a doctor's record in the software’s database.
**Test Objective:** To verify that a user can successfully search an already registered doctor record using the “**Search Doctor**” feature tools.

---

**Captions:**

![**Search Doctor Popup:** feature for retrieving and displaying doctor records and providing extra functionalities like filtered keyword search, import, edition, and deletion procedures.](Doctor%20Record%20Search%20e586aa341d634aa5a219c56cb9c2d839/Untitled.png)

**Search Doctor Popup:** feature for retrieving and displaying doctor records and providing extra functionalities like filtered keyword search, import, edition, and deletion procedures.

---

**Preconditions**:

1. The user must be registered in the database.
2. The doctors’ table in the database must not be empty.
3. The search keywords must be either correct or close to the desired match.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Click on the “**Search**” button in the doctor information section.
4. Choose desired filtering option.
5. Type in the search keyword.
6. Inspect the displayed items.
7. [Import](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Doctor%20Record%20Importing%204d01dfa880b343c19ba5d9f58f6306c0.md), [Edit](../Home%20Screen%20Data%20Editing%20Tests%200a77a45c064b4c68aff35958df412ba7/Doctor%20Record%20Editing%20a33499a4d45b49f8a8b021671bc72062.md), or [Delete](../Home%20Screen%20Data%20Deletion%20Tests%20b8f06a0d7d754de49c2ee4d6a36a80e6/Doctor%20Record%20Deletion%20d532eeb7264d4bc79d97dbd2a05366aa.md) doctor record item.

**Expected Results**:

1. The application should open without errors.
2. The user must be able to find and click on the “**Search**” button in the doctor information section.
3. The user should be able to select any filtering option and input any search keyword without encountering any issues.
4. The displayed items must match the search option that the user specified.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The “[Search Doctor](Doctor%20Record%20Search%20e586aa341d634aa5a219c56cb9c2d839.md)” popup opened successfully.
3. The search procedure was conducted successfully.
4. The patient records were retrieved successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully retrieves a correct search result.

**Severity:** High 
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---