# Login Test Cases

## TC001 - Valid Login

Steps:

1. Navigate to the login page
2. Enter a valid username
3. Enter a valid password
4. Click the login button

Expected Result:
User is successfully logged in and redirected to the dashboard

---

## TC002 - Invalid Password

Steps:

1. Navigate to the login page
2. Enter a valid username
3. Enter an incorrect password
4. Click the login button

Expected Result:
An error message is displayed indicating invalid credentials

---

## TC003 - Empty Fields

Steps:

1. Navigate to the login page
2. Leave username and password fields empty
3. Click the login button

Expected Result:
Validation messages are displayed for required fields

---

## TC004 - Password Case Sensitivity

Steps:

1. Navigate to the login page
2. Enter a valid username
3. Enter the correct password with incorrect casing
4. Click the login button

Expected Result:
Login fails and an error message is displayed
