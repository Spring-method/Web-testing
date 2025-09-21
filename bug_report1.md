# Bug Report: Error Logging in with Incorrect Password

ID: BUG-001
Title: No error message when entering an incorrect password
Priority: High
Severity: Major
Status: New
Environment:
- OS: Windows 11 Pro x64
- Browser: Google Chrome 129.0
- Tested app version: v1.3.5

---

## Reproduction Steps:
1. Go to the login page: https://www.saucedemo.com
2. Enter the correct login: error_user
3. Enter the incorrect password: wrong123
4. Click the "Login" button

---

## Actual Result:
- Page reloads
- User remains on the login page
- No error message is displayed

---

## Expected result:
- Authorization fails
- An error message appears below the form: *"Incorrect login or password"*

---

## Additional:
- The error is reproducible in all browsers
- A login attempt is recorded in the server logs
- Screenshot: *bug001_screenshot.png*
