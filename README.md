# Form-Validation-Javascript

This repository contains a simple HTML, CSS, and JavaScript code for performing form validation. The code ensures that the user provides valid input for the username, email, and password fields before submitting the form.

How to Use
Clone the repository or download the files (HTML, CSS, and JavaScript) to your local machine.

Open the index.html file in your web browser. The form will be displayed, which includes fields for entering the username, email, and password.

To test the form validation, try submitting the form without filling in any of the fields. You will see error messages below the respective fields, indicating that they cannot be left blank.

As you start typing in the fields, the error messages will disappear, and if the input is valid, you will see a green checkmark icon next to the field. If the input is invalid, a red exclamation mark icon will be displayed.

The form also provides two social media sign-up buttons (Google and Facebook), but they are not functional in this code and serve as placeholders.

Code Explanation
The code uses JavaScript to handle form validation. It defines event listeners for the form submission and checks the values of the username, email, and password fields. If any of these fields are left blank, appropriate error messages are displayed, and the border of the input field turns red. If the fields are filled correctly, a green checkmark icon is displayed.

Files
index.html: This file contains the HTML code for the form and the required elements.

style.css: This file contains the CSS code for styling the form elements and icons.

main.js: This file contains the JavaScript code for handling form validation and defining the necessary event listeners.

Images: This folder contains the logo image used in the form.

Dependencies
The form uses Font Awesome version 6.4.2 for displaying icons. It is linked in the HTML file using a CDN.

This code is a basic example of form validation and does not include server-side validation or real form submission. In a real-world application, you would need to perform server-side validation as well to ensure data integrity and security.

The social media sign-up buttons are placeholders and not functional.
