# Login Test Cases

## TC-001 Valid Login

**Precondition:** User account exists

**Steps:**

1. Open Login Page
2. Enter valid email
3. Enter valid password
4. Click Login

**Expected Result:**
User should be redirected to Dashboard

---

## TC-002 Invalid Password

**Steps:**

1. Open Login Page
2. Enter valid email
3. Enter wrong password
4. Click Login

**Expected Result:**
Error message should be displayed

---

## TC-003 Empty Email

**Steps:**

1. Open Login Page
2. Leave email empty
3. Enter password
4. Click Login

**Expected Result:**
Validation message should appear

---

## TC-004 Empty Password

**Steps:**

1. Open Login Page
2. Enter email
3. Leave password empty
4. Click Login

**Expected Result:**
Validation message should appear

---

## TC-005 Invalid Email Format

**Steps:**

1. Open Login Page
2. Enter email as abc123
3. Enter password
4. Click Login

**Expected Result:**
Invalid email format error should appear
