# Login_Page-JavaScript-Bootstarp-
Description :

This repository contains a login page built using Bootstrap CDN for the front-end design and JavaScript for implementing two types of form validations. 
The main goal of this project is to demonstrate how to use Bootstrap classes and custom JavaScript code to create a simple login form with client-side validation.
I have also used an external CSS file  and added media queries.

Implementation Details

1. Bootstrap's d-none class vs. JavaScript style.display="none":
   
The main difference between d-none and style.display="none" lies in how they achieve hiding elements.

d-none is a class provided by Bootstrap that sets the display property of an element to none. 
This class is useful for conveniently hiding elements using Bootstrap's CSS framework.
It is particularly beneficial when working with Bootstrap-based projects, as it keeps the HTML markup clean and separates 
style-related classes from the business logic.

On the other hand, style.display="none" is a direct JavaScript property used to manipulate an element's style and hide it from the user.
This method is not tied to any specific framework, providing more control over when and how an element is hidden.
It can be used for custom JavaScript code or projects that do not utilize Bootstrap.

2. Form Validations:
   
i. Blank Username and Password Validation:
When the user clicks the login button without providing a username and password, the form validation JavaScript code triggers.
 It checks if the input fields for the username and password are empty.
 If either field is empty, an alert is displayed using Bootstrap's d-none class with a warning message stating that both the username and password cannot be blank.

ii. Successful Login Validation:
Upon entering both the username and password, the user clicks the login button again. 
The validation JavaScript code checks if the input values match a pre-defined username and password combination. 
For this demonstration, we've set a simple static username and password for validation purposes. If the entered values match,
a success alert is displayed using Bootstrap's d-none class, indicating a successful login.
Additionally, the username of the logged-in user is printed to the console using console.log().
