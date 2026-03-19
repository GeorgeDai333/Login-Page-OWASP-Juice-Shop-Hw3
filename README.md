# Login Page Homework 3

## Description

This project implements a basic HTML and JavaScript login form that mimics Juice Shop's login page. It was developed as part of a homework assignment to demonstrate and simulate fundamental security practices for handling email and password inputs in web forms.

## Features

- **Email Input Field**: Accepts user email addresses with placeholder text
- **Password Input Field**: Secure password input with placeholder text
- **Client-Side Validation**:
  - Prevents submission of empty fields
  - Checks that email contains the "@" symbol
  - Ensures password is at least 8 characters long
- **User Feedback**: Displays error messages below input fields for validation failures
- **Responsive Design**: Clean, centered login form with basic styling

## Security Practices Simulated

This homework assignment focuses on simulating the following security practices:

1. **Input Validation**: Client-side checks to ensure data meets basic requirements before processing
2. **Email Format Verification**: Simple check for the presence of "@" symbol in email addresses
3. **Password Strength Requirements**: Minimum length requirement of 8 characters
4. **Empty Field Prevention**: Blocks form submission when required fields are not filled
5. **User-Friendly Error Messages**: Provides clear feedback to users about validation failures

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

## How to Run

1. Clone or download the project files
2. Open `index.html` in any modern web browser
3. Enter an email address and password in the respective fields
4. Click the "Log in" button to trigger validation
5. Observe the validation messages and success alert

## Notes

- This is a client-side only implementation for demonstration purposes
- No actual authentication or server communication is implemented
- The form prevents submission and shows alerts for successful validation
- Styling is kept minimal to focus on functionality and security concepts

## Course Information

This project was completed for CSCE 477