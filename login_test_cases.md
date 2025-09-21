# Test Cases: Authorization

## TC-01: Successful login with valid data
Preconditions:
- User is registered in the system
- Correct login and password are known

Steps:
1. Go to the authorization page
2. Enter a valid login
3. Enter a valid password
4. Click "Login"

Expected result:
- User is redirected to the main page
- A welcome message with the username is displayed

---

## TC-02: Error entering an incorrect password
Preconditions:
- User is registered in the system
- Correct login is known

Steps:
1. Go to the authorization page
2. Enter a correct login
3. Enter an incorrect password
4. Click "Login"

Expected result:
- Authorization does not occur
- An error message is displayed: *"Incorrect login or password"*

---

## TC-03: Empty login and password fields
Steps:

1. Go to the authorization page
2. Leave the "Login" and "Password" fields empty
3. Click the "Login" button

Expected result:
- Authorization does not occur
- Hints about the need to enter a password are displayed below the fields

