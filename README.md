# Test case samples
Below are some test case samples that I wrote while working on previous projects.

**1. Description:** Check if the login works when a user enters the correct credentials.

**Steps to reproduce:** 
1. Open website.com/login
2. Add correct user/pass
3. Click ”Login” button
   
**Expected result:** User should be able to login and is redirected to his profile page.

**Test data:** User: georgiana & password: 1234

**2. Description:** Check if the login fails when a person uses wrong credentials.

**Steps to reproduce:** 
1. Open https://auth.emag.ro/user/login
2. Add a wrong e-mail address
3. Click on ”Continue”
   
**Expected result:** The user cannot log in because the account does not exist, but the application suggests that they can create an account by entering their name and an account password.

**Test data:** User: georgiana & password: 1234

**3. Description:** Check if the login works without introducing any credentials.

**Steps to reproduce:** 
1. Open https://auth.emag.ro/user/login
2. Leave the e-mail address field empty
3. Click on ”Continue”
   
**Expected result:** An appropriate error message should be displayed indicating that the e-mail address field is a required field.

**Test data:** User: georgiana & password: 1234

**4. Description:** Check if the login fails when a person enters correct e-mail, but wrong password.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct e-mail address
3. Click on ”Continue”
4. Add wrong password
5. Click on ”Continue”
   
**Expected result:** An appropriate error message should be displayed indicating that the introduced password or e-mail address is incorrect and asking the user to introduce his password again.

**Test data:** User: georgiana & password: 1234

**5. Description:** Check if the search functionality returns relevant results that match the entered query.

**Steps to reproduce:** 
1. Open https://www.emag.ro/
2. Click on the search bar
3. Enter your query
4. Press the ”Enter” key or click on ”Search” button
   
**Expected result:** The application should return relevant results that match the entered search query. The displayed results include 20 results for Iphone 13 in different colors and with different memories.

**Test data:** Iphone 13
