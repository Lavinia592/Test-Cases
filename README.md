# QA documentation
The most important rule to write clean documentation is that someone else must be able to understand. Below are some examples of a test case and a bug report.

-----------
## Test case
Test Case ID: TC-LOGIN-001

Title: User can log in with valid credentials

**Preconditions:**
- User has an active account
- User is on the login page

**Steps:**
1. Enter valid email in the Email field
2. Enter valid password in the Password field
3. Click the Login button

**Test Data:**
- Email: user@test.com
- Password: ValidPassword123

**Expected Result:**
- User is redirected to the dashboard
- Dashboard username is displayed


---------------

## Bug report
Bug ID: BUG-LOGIN-004

Title: Login button inactive after entering valid credentials

**Environment:**
- Web app
- Chrome v120
- Windows 10

**Steps to Reproduce:**
1. Open the login page
2. Enter valid username and password
3. Observe the Login button

**Expected Result:**
- Login button should be clickable

**Actual Result:**
- Login button remains inactive

**Severity:**
- High

**Priority:**
- High

**Attachments:**
- Screenshot attached

**Notes:**
- Issue occurs consistently

