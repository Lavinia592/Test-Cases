# Test Cases Samples
Below there are some Test Cases that I used on previous projects.

-----------

**Test Title** :
Login with right credentials

**Description**:
Check if the login button works with the right credentials.

**Steps to reproduce**:
1. Access the website: https://www.website.com
2. Add a correct user/password
3. Press Login button

**Expected result**:
User should be able to login and taken to his profile page.

**Test data**:
user: user1 & password: 123456

-----------

**Test title**:
Login with wrong credentials

**Description**:
Check if the login button works with wrong credentials.

**Steps to reproduce**:
1. Access the website https://www.website.com
2. Add wrong user and password
3. Press login button
   
**Expected result**:
User should not be able to login into his account.

-----------

**Test title**: Verify Forgot Password functionability and reset password

**Description**: Check if "forgot password" works properly and allows user to reset password using email address.

**Precondition**:
1.User have a valid account and email address registeres with the application.
2.User knows the registred email address.

**Steps to reproduce**

1. Go to the website https://website.com
2. Click on login button
3. Click on forgot password
4. Enter registered email address
5. Click an "Send Link" button
6. Check email inbox or spam if link not found in inbox.
7. Click on reset password
8. Enter new password
9. Submit new password
10. Verify if message succes reset is printed.
11.Login with new password.

**Expected results**

1. A succes message should be printed after the email has been introduced.
2. User should receive an email with a link to reset password.
3. The password reset link should redirect user to a page for changing password. 
4. User should be able to reset password and login using new password.


**Test data**
1. Registered email address: 'user@example.com'
2. New password: 'newpass2024'



---------------
