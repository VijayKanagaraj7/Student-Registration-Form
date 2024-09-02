# Student-Registration-Form
This Student Registration Form is an HTML-based web form designed for collecting detailed information from students during registration.

Below is a description of its structure and functionality:

# HTML Structure
Document Setup:

The document uses HTML5 (<!DOCTYPE html>), with English as the language (lang="en").
It includes meta tags for character set (UTF-8), compatibility with Internet Explorer (IE=edge), and viewport settings for responsive design.
Head Section:
Title: The title of the webpage is "Student Registration Form."

# Stylesheets:
External CSS (style.css) is linked for custom styling.
FontAwesome is included for adding icons (https://use.fontawesome.com/releases/v5.7.0/css/all.css).

# JavaScript:
A script (script.js) is included for additional functionality, like password validation.
Body Section:

Wrapper Div: The main content is wrapped inside a div with a class wrapper.
Title: A heading is provided inside a div with a class title for displaying the form's title.
Form Element:

The form is defined with the method POST and includes the data-netlify="true" attribute for Netlify form handling.

# Form Fields:

First Name & Last Name:
Text inputs for first and last names with attributes for placeholder text, pattern matching (alphabets only), and length restrictions.
Gender:
Radio buttons for selecting gender (Male or Female).
Age:
Text input for age, restricted to two digits with a numeric pattern.
Date of Birth:
Date input for selecting the birth date.
Email Address:
Email input with a pattern for valid email format.
Password & Confirm Password:
Password inputs with criteria for a strong password (uppercase, lowercase, numbers, and minimum 8 characters).
A script checks if the password and confirm password fields match.
Phone Number:
A dropdown for the phone code (+91) and a text input for the phone number, restricted to 10 digits.
Address:
A textarea for the address with a pattern for valid characters and length restrictions.
State:
A dropdown menu for selecting the state from a predefined list of Indian states.
Pin Code:
Text input for the pin code, restricted to 6 digits.
Hobbies:
Checkboxes for selecting hobbies (Music, Movies, Sports, Travel).
Upload Photo:
File input for uploading a photo with a maximum file size of 100KB.
Terms and Conditions:
A checkbox to declare that the provided information is true and correct.
reCAPTCHA:
A field for reCAPTCHA to prevent spam submissions.
Buttons:

# Register Button:
A submit button to register the form, with an onclick event to validate the password.
Reset Button:
A reset button to clear all fields.
Key Functionalities:
Validation:
Input fields include validation patterns for correct data entry (e.g., name, email, phone number).
Password Matching:
JavaScript is used to ensure the password and confirm password fields match before submission.
Responsive Design:
The form is designed to be responsive, ensuring usability across different devices.
Security:
Includes a reCAPTCHA for spam protection.
File Upload:
Users can upload a photo, with a specified maximum file size for validation.
External Dependencies:
FontAwesome: For adding icons if needed.
Netlify: For form handling and reCAPTCHA integration.
