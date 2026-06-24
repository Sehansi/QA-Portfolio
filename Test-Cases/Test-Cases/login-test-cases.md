# Test Cases - Login Functionality

## TC-001
**Test Case:** Valid Login  
**Steps:**
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click Login button  
**Expected Result:** User should login successfully

---

## TC-002
**Test Case:** Invalid Password  
**Steps:**
1. Enter valid username
2. Enter wrong password
3. Click Login  
**Expected:** Error message should appear

---

## TC-003
**Test Case:** Empty Fields  
**Steps:**
1. Leave username and password empty
2. Click Login  
**Expected:** Validation message shown

---

## TC-004
**Test Case:** SQL Injection Attempt  
**Steps:**
1. Enter `' OR '1'='1` in username
2. Enter any password
3. Click Login  
**Expected:** Login should fail

---

## TC-005
**Test Case:** Case Sensitivity  
**Steps:**
1. Enter username in different case
2. Enter correct password  
**Expected:** System should handle case sensitivity correctly
