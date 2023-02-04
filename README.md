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

### **TEST 1 - Login**

Scope of Testing:  
-  Test the login feature of a web application  
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
    4. 
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


### **TEST 2 - Signup**

Scope of Testing:  
-  Test the login feature of a web application  
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
    4. 
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
