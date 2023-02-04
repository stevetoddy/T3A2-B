# T3A2-B - Full Stack App (Part B)  

#### Oli Wong, Stevan Todorovic, Kane Campbell  

---

## Githut Repositories  

Front End - https://github.com/stevetoddy/Physio_FRONT

Back End - https://github.com/stevetoddy/Physio_App_API

---

## Trello Board

https://trello.com/b/kK33sqyD/physio-full-stack-app

---
## T3A2 - A README Documentation  

https://github.com/OliWongDev/T3-A2

---

## Development Testing

## **Front End** 
### **TEST 1 - Login**

Scope of Testing:  
-  Test the login feature   
-  Test in Firefox browser  
-  Test using valid and invalid login credentials  

Test Plan:  
-  Objectives: To verify that the login feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 2 (1 for successful login and 1 for unsuccessful login)  
 
Test Case 1: Successful Login  

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
   
Expected Result:  
-  User should be redirected to the home page  
-  A message should display: "Welcome to Physio App"  

Test Case 2: Unsuccessful Login  

Steps:
    1. Launch the web application in Firefox  
    2. Enter an invalid email and password  
    3. Click on the login button  

Expected Result:  
-  User should be redirected to the bad login page with and error message "Login Details are wrong!", and a link to return to the login page  
-  User should not be redirected to the home page  

Test Data:  

First Test (Valid Credentials):  

Email – s@email.com  
Password – password1  
Result – Success  

Second Test (Inalid Credentials):  

Email – wrong@email.com  
Password – notpassword1  
Result – Failure  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Failure

Results:
- All test cases passed successfully
- No defects found  


### **TEST 2 - Programs List**

Scope of Testing:  
-  Test the programs list feature  
-  Test in Firefox browser  
-  Test using valid credentials  

Test Plan:  
-  Objectives: To verify that the program list feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 1 (1 for successful production of program list)  
 
Test Case 1: Successful Production of Program List  

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
    4. Click on the Programs List link in the Navbar
   
Expected Result:  
-  User should be redirected to the Home page  
-  User should be redirected to the Programs List page  
-  All user programs should be listed as links    

Test Data:  

First Test (Using Valid Credentials):  

Email – s@email.com  
Password – password1  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful

Results:
- All test cases passed successfully
- No defects found

### **TEST 3 - Create Program**

Scope of Testing:  
-  Test the create program feature   
-  Test in Firefox browser  
-  Test using valid login credentials  

Test Plan:  
-  Objectives: To verify that the create program feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 2 (1 for successful creation of a new program with one exercise under a specific user, 1 for successful creation of a new program with two exercises under a specific user)  
 
Test Case 1: Successful Program Creation with One Exercise   

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
    4. Click the Create Program link in the Navbar
    5. Enter Program Name and click Submit button
    6. Enter Exercise Name and Exercise Details and click Submit button
    7. Click Save Test Program to your Programs List link
   
Expected Result:  
-  User should be redirected to the Program Name page
-  User should then be redirected to the Exercise Name and Details page
-  User should be redirected to the Exercise Added To Test Program page
-  User should be redirected to the Home page
-  The new program should be listed in the Programs List page  

Test Case 2: Successful Program Creation with More Than One Exercise  

Steps:
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
    4. Click the Create Program link in the Navbar
    5. Enter Program Name and click Submit button
    6. Enter Exercise Name and Exercise Details and click Submit button
    7. Click Add Another Exercise to 'Program Name' link
    8. Repeat step 6 again then click Save Test Program to your Programs List link

Expected Result:  
-  User should be redirected to the Home page
-  User should be redirected to the Program Name page
-  User should then be redirected to the Exercise Name and Details page
-  User should be redirected to the Exercise Added To Test Program page
-  User should then be redirected to the Exercise Name and Details page again
-  User should be redirected to the Exercise Added To Test Program page again
-  User should be redirected to the Home page
-  The two new program should be listed in the Programs List page  

Test Data:  

First Test (Program with One Exercise):  

Email – s@email.com  
Password – password1  
Program Name - Test Program
Exercise Name - Exercise 1
Exercise Details - Test Details
Result – Success  

Second Test (Program with Two Exercises):  

Email – s@email.com  
Password – password1  
Program Name - Test Program
Exercise 1 Name - Exercise 1
Exercise 1 Details - Test Details
Exercise 2 Name - Exercise 2
Exercise 2 Details - Test Details
Result – Success  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Successful

Results:
- All test cases passed successfully
- No defects found  

### **TEST 4 - Update Metrics Charts**

Scope of Testing:  
-  Test the Metrics Charts feature   
-  Test in Firefox browser  
-  Test using valid login credentials  

Test Plan:  
-  Objectives: To verify that the Metrics Charts feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 1 (1 for successfully updating the Metrics Charts after completing a program)  
 
Test Case 1: Successful Updating the Metrics Charts after Completing a Program   

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
    4. Click the Program List link in the Navbar
    5. Click the Program link in the list provided
    6. Fill in the metrics details on each exercise and click the complete checkbox
    7. Click Submit button at bottom of page
   
Expected Result:  
-  User should be redirected to the Home page
-  User should be redirected to the Program List page
-  User should be redirected to the Exercise List page
-  User should be redirected to the Progress page
-  The updated metrics should be displayed on the programs chart 

Test Data:  

First Test:  

Email – s@email.com  
Password – password1  
Metrics entered - 5 for Pain, 5 for Difficulty and clicking the Complete Check box  
Result – Success  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful

Results:
- All test cases passed successfully
- No defects found  

### **TEST 5 - Logout**

Scope of Testing:  
-  Test the Logout feature  
-  Test in Firefox browser  
-  Test using valid login credentials  

Test Plan:  
-  Objectives: To verify that the Logout feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 1 (1 for successful logout and redirect of user)  
 
Test Case 1: Successful Logout and Redirect of User  

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
    4. Click the LOGOUT link in the Navbar
   
Expected Result:  
-  User should be redirected to the Home page
-  User should then be redirected to the Login page 

Test Data:  

First Test:  

Email – s@email.com  
Password – password1  
Result – Success  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful

Results:
- All test cases passed successfully
- No defects found  

## **Back End** 
### **TEST 1 - Login**

Scope of Testing:  
-  Test the login feature   
-  Test in Firefox browser  
-  Test using valid and invalid login credentials  

Test Plan:  
-  Objectives: To verify that the login feature is working as expected  
-  Resources: One tester, Firefox browser, test data  
-  Test Cases: 2 (1 for successful login and 1 for unsuccessful login)  
 
Test Case 1: Successful Login  

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
   
Expected Result:  
-  User should be redirected to the home page  
-  A message should display: "Welcome to Physio App"  

Test Case 2: Unsuccessful Login  

Steps:
    1. Launch the web application in Firefox  
    2. Enter an invalid email and password  
    3. Click on the login button  

Expected Result:  
-  User should be redirected to the bad login page with and error message "Login Details are wrong!", and a link to return to the login page  
-  User should not be redirected to the home page  

Test Data:  

First Test (Valid Credentials):  

Email – s@email.com  
Password – password1  
Result – Success  

Second Test (Inalid Credentials):  

Email – wrong@email.com  
Password – notpassword1  
Result – Failure  

Test Environment:  
- Firefox browser version 109.0 (64-bit) Mozilla Firefox for Ubuntu  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Failure

Results:
- All test cases passed successfully
- No defects found  
























---

## Libraries Used

### **Front End**

blueprintjs
- Treat generic objects with class
- Link: https://www.npmjs.com/package/blueprintjs

chart.js
- Simple HTML5 charts using the canvas element.
- Link: https://www.npmjs.com/package/chart.js

cors
- Node.js CORS middleware
- Link: https://www.npmjs.com/package/cors

jsonwebtoken
- JSON Web Token implementation (symmetric and asymmetric)
- Link: https://www.npmjs.com/package/jsonwebtoken

jwt-decode
- Decode JWT tokens, mostly useful for browser applications.
- Link: https://www.npmjs.com/package/jwt-decode

react
- React is a JavaScript library for building user interfaces.
- Link: https://www.npmjs.com/package/react

react-chartjs-2
- React components for Chart.js
- Link: https://www.npmjs.com/package/react-chartjs-2

react-dom
- React package for working with the DOM.
- Link: https://www.npmjs.com/package/react-dom

react-router-dom
- Declarative routing for React web applications
- Link: https://www.npmjs.com/package/react-router-dom

### **Back End**

bcrypt
- A bcrypt library for NodeJS.
- Link: https://www.npmjs.com/package/bcrypt

cors
- Node.js CORS middleware
- Link: https://www.npmjs.com/package/cors

dotenv
- Loads environment variables from .env file
- Link: https://www.npmjs.com/package/dotenv

express
- Fast, unopinionated, minimalist web framework
- Link: https://www.npmjs.com/package/express

express-validator
- Express middleware for the validator module.
- Link: https://www.npmjs.com/package/express-validator

jsonwebtoken
- JSON Web Token implementation (symmetric and asymmetric)
- Link: https://www.npmjs.com/package/jsonwebtoken

jwt-decode
- Decode JWT tokens, mostly useful for browser applications.
- Link: https://www.npmjs.com/package/jwt-decode

mongoose
- Mongoose MongoDB ODM
- Link: https://www.npmjs.com/package/mongoose

nodemon
- Simple monitor script for use during development of a Node.js app.
- Link: https://www.npmjs.com/package/nodemon
