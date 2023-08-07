# User Record Search

**Test Case ID:** TC002
**Test Case Title:** Search for a user record in the software’s database.
**Test Objective:** To verify that a user can successfully search an already registered user record using the “**Search User**” feature tools.

---

**Captions:**

![**Search User Popup:** feature for retrieving and displaying user records and providing extra functionalities like filtered keyword search, edition and deletion procedures. ](User%20Record%20Search%203a1c0b8966c14ab4b77b6697beefac66/Untitled.png)

**Search User Popup:** feature for retrieving and displaying user records and providing extra functionalities like filtered keyword search, edition and deletion procedures. 

---

**Preconditions**:

1. The user must be registered in the database.
2. The users’ table in the database must not be empty.
3. The search keywords must be either correct or close to the desired match.

**Test Steps**:

1. Launch the application.
2. Login and access the home screen.
3. Click on the “**Settings**” button in the settings bar at the top.
4. Click on the “**Search User**” button.
5. Choose desired filtering option.
6. Type in the search keyword.
7. Inspect the displayed items.
8. [Edit](../Home%20Screen%20Data%20Editing%20Tests%200a77a45c064b4c68aff35958df412ba7/User%20Record%20Editing%20eedef63268794eb8b52a7c6629329ce2.md) or [Delete](../Home%20Screen%20Data%20Deletion%20Tests%20b8f06a0d7d754de49c2ee4d6a36a80e6/User%20Record%20Deletion%207ef7a4c862d340878cf31979ed75fad4.md) user record item.

**Expected Results**:

1. The application should open without errors.
2. The user must be able to find and click on the “**Search User**” button.
3. The user should be able to select any filtering option and input any search keyword without encountering any issues.
4. The displayed items must match the search option that the user specified.

**Actual Results**:

*(The actual outcome observed during the test execution. Please fill in this after running the test.)*

1. The application opened successfully.
2. The “[Search User](User%20Record%20Search%203a1c0b8966c14ab4b77b6697beefac66.md)” popup opened successfully.
3. The search procedure was conducted successfully.
4. The user records were retrieved successfully.

**Pass/Fail Criteria**:
The test case passes if the user successfully retrieves a correct search result.

**Severity:** High 
**Priority:** High
**Status:** **Passed**

**Notes**: *(fill in with any additional information or comments related to the test case)*

---