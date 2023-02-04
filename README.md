# T3A2-B - Full Stack App (Part B)  

#### Oli Wong, Stevan Todorovic, Kane Campbell  

---
## Webapp Link

https://physiofront-production.up.railway.app/login

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
 
**Test Case 1: Successful Login**  

Steps:  
    1. Launch the web application in Firefox  
    2. Enter a valid email and password  
    3. Click on the login button  
   
Expected Result:  
-  User should be redirected to the home page  
-  A message should display: "Welcome to Physio App"  

**Test Case 2: Unsuccessful Login**  

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
 
**Test Case 1: Successful Production of Program List**  

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
 
**Test Case 1: Successful Program Creation with One Exercise**   

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

**Test Case 2: Successful Program Creation with More Than One Exercise**  

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
 
**Test Case 1: Successful Updating the Metrics Charts after Completing a Program**   

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
 
**Test Case 1: Successful Logout and Redirect of User**  

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
### **TEST 1 - Sign Up Route**

Scope of Testing:  
-  Test the sign up route on the API  
-  Test in Postman  
-  Test using valid and invalid sign up details  

Test Plan:  
-  Objectives: To verify that the sign up route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 2 (1 for successful sign up and 1 for unsuccessful sign up)  
 
**Test Case 1: Successful Sign Up**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4002/auth/signup'  
    3. Set as a POST Request  
    4. Enter the sign up details into the body as raw JSON as follows:  

    {
        "username": "Testname",
        "email": "test@email.com",
        "password": "password1"
    }  

Expected Result:  
-  '201 Created' status returned  
-  A JSON return as follows:
```
{
    "username": "Testname",
    "email": "test@email.com",
    "password": "$2b$10$1RgmKyStgfsasJiTTVmQJ.IOqa23mIPlVUcwT8/kKd4Y.vkA9n14u",
    "_id": "63dded06b9053cd66b7f2498",
    "__v": 0
}
```
**Test Case 2: Unsuccessful Sign Up**  

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/auth/signup'  
    3. Set as a POST Request  
    4. Enter the sign up invalid details into the body as raw JSON as follows:  

    {
        "username": "Testname",
        "email": "test.com",
        "password": "short"
    }  

Expected Result:  
-  '400 Bad Request' status returned  
-  A JSON return as follows:
```
{
    "errors": [
        {
            "value": "test.com",
            "msg": "Please provide a valid email",
            "param": "email",
            "location": "body"
        },
        {
            "value": "short",
            "msg": "Please provide a password that is greater than 5 characters.",
            "param": "password",
            "location": "body"
        }
    ]
}
```

Test Data:  

First Test (Valid Details):  

Result – Success  

Second Test (Invalid Details):  
 
Result – Failure  

Test Environment:  
- Postman for Linux Version 9.31.0  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Failure

Results:
- All test cases passed successfully
- No defects found  

### **TEST 2 - Login Route**

Scope of Testing:  
-  Test the login route on the API  
-  Test in Postman  
-  Test using valid and invalid login details  

Test Plan:  
-  Objectives: To verify that the login route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 2 (1 for successful login and 1 for unsuccessful login)  
 
**Test Case 1: Successful Login**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/auth/login'  
    3. Set as a POST Request  
    4. Enter the login details into the body as raw JSON as follows:  

    {
        "email": "s@email.com",
        "password": "password1"
    }

Expected Result:  
-  '200 OK' status returned  
-  A JWT string return as follows (example below):
```
"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjb21wYXJlZFVzZXIiOlt7Il9pZCI6IjYzZGRlOGJmMjIyODEzZTBiMmRjODc2YiIsInVzZXJuYW1lIjoiU3RldmVfMTAwMCIsImVtYWlsIjoic0BlbWFpbC5jb20iLCJwYXNzd29yZCI6IiQyYiQxMCRTZ0hORDBLVElBWDhJLy5OQzhaV291c0NBVU1rSGpPU3JBdHQzODJaYjBUdDNHOUNHZ0gvTyIsIl9fdiI6MH1dLCJpYXQiOjE2NzU0ODkwMjYsImV4cCI6MTY3NTg0OTAyNn0.CgYXR-kCeLk4IbsUejF6YGKlSyImYbAKmxtJg9WTHKE"
```
**Test Case 2: Unsuccessful Login** 

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4002/auth/login'  
    3. Set as a POST Request  
    4. Enter the login invalid details into the body as follows:  

    {
        "email": "wrong@email.com",
        "password": "wrongpassword"
    }  

Expected Result:  
-  '422 Unprocessable Entity' status returned  
-  A JSON return as follows:
```
{
    "errors": "Invalid Details. Please check email and password are correct"
}
```

Test Data:  

First Test (Valid Details):  

Result – Success  

Second Test (Invalid Details):  
 
Result – Failure  

Test Environment:  
- Postman for Linux Version 9.31.0  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Failure

Results:
- All test cases passed successfully
- No defects found  

### **TEST 3 - All Programs Assigned to One User Route**

Scope of Testing:  
-  Test the 'All Programs Assigned to One User' route on the API  
-  Test in Postman  
-  Test using valid and invalid user id  

Test Plan:  
-  Objectives: To verify that the 'All Programs Assigned to One User' route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 2 (1 for correct user id and 1 for incorrect user id)  
 
**Test Case 1: Correct User Id**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/users/63dde8bf222813e0b2dc876b'  
    3. Set as a GET Request  

Expected Result:  
-  '200 OK' status returned  
-  A JSON return as follows (partial):
```
[
    {
        "_id": "63dde8bf222813e0b2dc8771",
        "name": "Knee Strength Rebuild",
        "exercises": [
            {
                "name": "Calf Raise",
                "image": "IMAGE LINK",
                "info": "3 x 30 reps",
                "_id": "63dde8bf222813e0b2dc8772"
            },
            {
                "name": "Alternating Lunges",
                "image": "IMAGE LINK",
                "info": "4 x 25 reps, alternating",
                "_id": "63dde8bf222813e0b2dc8773"
            },
            {
                "name": "Air Squat",
                "image": "IMAGE LINK",
                "info": "5 x 30 reps",
                "_id": "63dde8bf222813e0b2dc8774"
            }
        ],
        "metrics": [
            {
                "complete": 0.67,
                "pain": 8.3,
                "diff": 5.6,
                "date": "21/11/22",
                "_id": "63dde8bf222813e0b2dc8775"
            }
        ],
        "userID": "63dde8bf222813e0b2dc876b",
        "__v": 0
    },
```
**Test Case 2: Incorrect User Id** 

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/users/555'  
    3. Set as a GET Request  

Expected Result:  
-  '200 OK' status returned  
-  A JSON return as follows:
```
[]
```

Test Data:  

First Test (Valid User Id):  

Result – Success  

Second Test (Invalid User Id):  
 
Result – Success  

Test Environment:  
- Postman for Linux Version 9.31.0  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Successful

Results:
- All test cases passed successfully
- No defects found  

### **TEST 4 - One Program by Program Id Route**

Scope of Testing:  
-  Test the 'One Program by Program Id' route on the API  
-  Test in Postman  
-  Test using valid and invalid program id  

Test Plan:  
-  Objectives: To verify that the 'One Program by Program Id' route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 2 (1 for correct program id and 1 for incorrect program id)  
 
**Test Case 1: Correct Program Id**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/63dde8bf222813e0b2dc8771'  
    3. Set as a GET Request  

Expected Result:  
-  '200 OK' status returned  
-  A JSON return as follows:  
```
{
    "_id": "63dde8bf222813e0b2dc8771",
    "name": "Knee Strength Rebuild",
    "exercises": [
        {
            "name": "Calf Raise",
            "image": "IMAGE LINK",
            "info": "3 x 30 reps",
            "_id": "63dde8bf222813e0b2dc8772"
        },
        {
            "name": "Alternating Lunges",
            "image": "IMAGE LINK",
            "info": "4 x 25 reps, alternating",
            "_id": "63dde8bf222813e0b2dc8773"
        },
        {
            "name": "Air Squat",
            "image": "IMAGE LINK",
            "info": "5 x 30 reps",
            "_id": "63dde8bf222813e0b2dc8774"
        }
    ],
    "metrics": [
        {
            "complete": 0.67,
            "pain": 8.3,
            "diff": 5.6,
            "date": "21/11/22",
            "_id": "63dde8bf222813e0b2dc8775"
        }
    ],
    "userID": "63dde8bf222813e0b2dc876b",
    "__v": 0
}
```
**Test Case 2: Incorrect Program Id** 

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/555'  
    3. Set as a GET Request  

Expected Result:  
-  '404 Not Found' status returned  
-  A JSON return as follows:
```
{
    "error": "Program was not found"
}
```

Test Data:  

First Test (Valid Program Id):  

Result – Success  

Second Test (Invalid Program Id):  
 
Result – Failure  

Test Environment:  
- Postman for Linux Version 9.31.0  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful
- Test Case 2: Failure

Results:
- All test cases passed successfully
- No defects found  

### **TEST 5 - Create Program Route**

Scope of Testing:  
-  Test the 'Create Program Route' route on the API  
-  Test in Postman  
-  Test using valid program details  

Test Plan:  
-  Objectives: To verify that the 'Create Program Route' route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 1 (1 for valid program details)  
 
**Test Case 1: Valid Program Details**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/'  
    3. Set as a POST Request  
    4. Enter the login details into the body as raw JSON as follows:  

    { 
    "name": "New Program",
    "userID": "63dde8bf222813e0b2dc876b" 
    }

Expected Result:  
-  '201 Created' status returned  
-  A JSON return as follows:  
```
{
    "name": "New Program",
    "exercises": [],
    "metrics": [],
    "userID": "63dde8bf222813e0b2dc876b",
    "_id": "63ddf6d72191b31417bbc01a",
    "__v": 0
}
```

Test Data:  

First Test (Valid Program Details):  

Result – Success  


Test Environment:  
- Postman for Linux Version 9.31.0  
- Ubuntu 20.04.5 LTS Operating System  

Test Execution:
- Test Case 1: Successful

Results:
- All test cases passed successfully
- No defects found  

### **TEST 6 - Update Exercise Route**

Scope of Testing:  
-  Test the 'Update Exercise Route' route on the API  
-  Test in Postman  
-  Test using valid program id and invalid program id  

Test Plan:  
-  Objectives: To verify that the 'Update Exercise Route' route is working as expected  
-  Resources: One tester, Postman client, test data  
-  Test Cases: 2 (1 for valid program id and 1 for invalid program id)  
 
**Test Case 1: Valid Program Id**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/exercise/63dde8bf222813e0b2dc8771'  
    3. Set as a PUT Request  
    4. Enter the login details into the body as raw JSON as follows:  
    
    {
    "exercises": [
        {"name": "Pistol Squats", "image": "Link", "info": "3 x 10 reps"},
        {"name": "Wall Sit", "image": "Link", "info": "4 x 2 minute intervals, 30 second rest"}
    ]
    }

Expected Result:  
-  '200 OK' status returned  
-  A JSON return as follows:  
```
{
    "_id": "63dde8bf222813e0b2dc8771",
    "name": "Knee Strength Rebuild",
    "exercises": [
        {
            "name": "Calf Raise",
            "image": "IMAGE LINK",
            "info": "3 x 30 reps",
            "_id": "63dde8bf222813e0b2dc8772"
        },
        {
            "name": "Alternating Lunges",
            "image": "IMAGE LINK",
            "info": "4 x 25 reps, alternating",
            "_id": "63dde8bf222813e0b2dc8773"
        },
        {
            "name": "Air Squat",
            "image": "IMAGE LINK",
            "info": "5 x 30 reps",
            "_id": "63dde8bf222813e0b2dc8774"
        },
        {
            "name": "Pistol Squats",
            "image": "Link",
            "info": "3 x 10 reps",
            "_id": "63ddf9ab2191b31417bbc021"
        },
        {
            "name": "Wall Sit",
            "image": "Link",
            "info": "4 x 2 minute intervals, 30 second rest",
            "_id": "63ddf9ab2191b31417bbc022"
        }
    ],
    "metrics": [
        {
            "complete": 0.67,
            "pain": 8.3,
            "diff": 5.6,
            "date": "21/11/22",
            "_id": "63dde8bf222813e0b2dc8775"
        }
    ],
    "userID": "63dde8bf222813e0b2dc876b",
    "__v": 0
}
```

**Test Case 2: Invalid Program Id**

Steps:  
    1. Launch the Postman client  
    2. Enter the route URL 'localhost:4001/programs/exercise/555'  
    3. Set as a PUT Request  
    4. Enter the login details into the body as raw JSON as follows:  

    {
    "exercises": [
        {"name": "Pistol Squats", "image": "Link", "info": "3 x 10 reps"},
        {"name": "Wall Sit", "image": "Link", "info": "4 x 2 minute intervals, 30 second rest"}
    ]
    }

Expected Result:  
-  '404 Not Found' status returned  
-  A JSON return as follows:  
```
{
    "error": "Exercise could not be found"
}
```

Test Data:  

First Test (Valid Program Id):  

Result – Success  

Second Test (Invalid Program Id):  

Result – Failure  

Test Environment:  
- Postman for Linux Version 9.31.0  
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
