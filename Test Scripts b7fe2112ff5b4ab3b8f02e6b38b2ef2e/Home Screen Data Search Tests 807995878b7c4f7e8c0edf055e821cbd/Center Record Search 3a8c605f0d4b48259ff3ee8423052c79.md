# Center Record Search

**Test Case ID:** TC005
**Test Case Title:** Search for a center's record in the software’s database.
**Test Objective:** To verify that a user can successfully search an already registered center record using the “**Search Center**” feature tools.

---

**Captions:**

![**Search Center Popup:** feature for retrieving and displaying center records and providing extra functionalities like filtered keyword search, import, edition, and deletion procedures.](Center%20Record%20Search%203a8c605f0d4b48259ff3ee8423052c79/Untitled.png)

**Search Center Popup:** feature for retrieving and displaying center records and providing extra functionalities like filtered keyword search, import, edition, and deletion procedures.

---

**Preconditions**:

1. The user must be registered in the database.
2. The centers’ table in the database must not be empty.
3. The search keywords must be either correct or close to the desired match.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Click on the “**Search**” button in the center information section.
4. Choose desired filtering option.
5. Type in the search keyword.
6. Inspect the displayed items.
7. [Import](../Home%20Screen%20Data%20Importing%20Tests%20723887868852425a9ec9269198ecdfd2/Center%20Record%20Importing%20a641413fa7e14c96a1d99ac0de93e5b3.md), [Edit](../Home%20Screen%20Data%20Editing%20Tests%200a77a45c064b4c68aff35958df412ba7/Center%20Record%20Editing%20567ad8014cd84b1d9529156b1e35f973.md), or [Delete](../Home%20Screen%20Data%20Deletion%20Tests%20b8f06a0d7d754de49c2ee4d6a36a80e6/Center%20Record%20Deletion%205ca6573999e743a6b311195e1823f6ea.md) center record item.

**Expected Results**:

1. The application should open without errors.
2. The user must be able to find and click on the “**Search**” button in the center information section.
3. The user should be able to select any filtering option and input any search keyword without encountering any issues.
4. The displayed items must match the search option that the user specified.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The “[Search Center](Center%20Record%20Search%203a8c605f0d4b48259ff3ee8423052c79.md)” popup opened successfully.
3. The search procedure was conducted successfully.
4. The center records were retrieved successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully retrieves a correct search result.

**Severity:** High 
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---