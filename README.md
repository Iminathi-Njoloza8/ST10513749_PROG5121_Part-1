# Chat Application Part 1

## Student Information
      - Name: Iminathi Njoloza
      - Student Number: ST10513749
      - Module: PROG5121

---

## Project Infromation
For this assignment I used NetBeans, as it is required of us as students to use while moving forward with this project. I created a project named ChatAppPart1 and created two java classes under a folder named com.mycompany.chatapppart1. These two java classes are named "Login" and "MainApp" which actually link with each other because in order for the "MainApp" class to run it need to be able to call the methods that are in the "Login" class. After I was done working with the two classes I created another java class under test packages which also has a folder named "com.mycompany.chatapppart1" because it will be used to test the methods in the "Login" class if the they work or not. The name of this new java class is "LoginTest".

---
## Features
### Username Validation
In the "Login" class we have a username validation which makes sure that the username entered is no more than five characters in length and makes sure that the username has a unserscore("_").
### Password Validation
Also in the "Login" class we have a password validation which makes sure that the password created is atleast eight characters in length, has a capital letter, has a number, and has a special character(!,@,#,$,%,&).
### Cellphone Number validation
This is also in the "Login" class and it makes sure that the cell phone number has the correct international code (+27...) and is 12 characters in length.

---
### Registration Section
In the "MainApp" class the registration section is where the programs allows the user to enter their username, password, and cellphone number. If one of these are entered incorrectly the system will output a message that states that the information enterd is incorrectly formatted please enter the correct format.
### Login Section
This is also in the "MainApp" class and it allows the user to enter their login information and if the login infromation is incorrect the system will output a message that states that "the username or password is incorrect ;please enter again".

---
