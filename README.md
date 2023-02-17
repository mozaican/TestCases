# Test Case Samples

Below are some Test Case samples that I wrote.

------------------------------

**Title:**
Test login with correct credentials

**Description:**
Check if the login functionality works with correct credentials (user & pass).

**Steps to reproduce:**
1. Go to http://site.com/login
2. Add correct user & pass
3. Observe if user can login

**Expected result:**
User should be able to login and he/she is taken to his/her profile page.

**Test Data:**
User: oana & Pass: 123abc

---------------------------------

**Title:**
Test login with incorrect credentials

**Description:**
Test the login functionality with incorrect credentials (user & pass).

**Steps to reproduce:**
1. Go to http://site.com/login
2. Add incorrect user & pass
3. Observe if user can login and if any error message appears

**Expected result:**
User should not be able to login and an error message should appear that lets the user know that his/her credentials are incorrect.

**Test Data:**
User: dsfadf & Pass: 4353454464ghf

---------------------------------

**Title:**
Test login without credentials

**Description:**
Test the login functionality without input credentials (user & pass).

**Steps to reproduce:**
1. Go to http://site.com/login
2. Let user & pass fields empty
3. Observe if user can login and if any error message appears

**Expected result:**
User should not be able to login and an error message should appear that lets the user know that his/her credentials are incorrect.

**Test Data:**
User:  Pass:

---------------------------------

**Title:**
Test forget password functionality

**Description:**
Check if forget password functionality works as expected and an email with a reset password link is sent.

**Steps to reproduce:**
1. Go to http://site.com/login
2. Click on "Forget password" link
3. Add an email address
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link which should allow the user to create a new password.

**Test Data:**
User: oana@gmail.com

**Note:**
Check the login again after running this test case.

--------------------------------

**Title:**
Test "Remember Me" functionality

**Description:**
Test the "Remember Me" functionality by using correct credentials and by checking the "Remember Me" checkbox.

**Steps to reproduce:**
1. Go to http://site.com/login
2. Add correct user & pass
3. Check the "Remember Me" checkbox
4. Observe if user can login
5. Try to login again and see if the credentials are saved

**Expected result:**
User's credentials should be saved for the next login attempts.

**Test Data:**
User: oana & Pass: 123abc

------------------------------

**Title:**
Test eMag search functionality using an existing category

**Description:**
Test eMag search functionality using an existing category.

**Steps to reproduce:**
1. Go to https://www.emag.ro/
2. Insert an existing category inside the search box
3. Press the search button
3. Observe if the correct items are displayed as results

**Expected result:**
The correct items from the searched category should be listed on the page.

**Test Data:**
Type "smartphone" inside the search box

-------------------------------

**Title:**
Test eMag search functionality using an unexisting category

**Description:**
Test eMag search functionality using an unexisting category.

**Steps to reproduce:**
1. Go to https://www.emag.ro/
2. Insert an unexisting category inside the search box
3. Press the search button
3. Observe if a custom page is displayed which informs the user that the searched item does not exist

**Expected result:**
A custom page should be displayed which informs the user that the searched item does not exist.

**Test Data:**
Type "hgndfgdfgdsd" inside the search box

-------------------------------

**Title:**
Test eMag search autocomplete

**Description:**
Test eMag search autocomplete functionality by typing the first 3 letters of a word.

**Steps to reproduce:**
1. Go to https://www.emag.ro/
2. Type the first 3 letters of a word inside the search box
3. Observe if a suggestion list with words that complete the first 3 letters inserted is displayed 

**Expected result:**
A list with words that start with the first 3 letters that were inserted in the search box should be displayed. 

**Test Data:**
Type "sma" inside the search box
