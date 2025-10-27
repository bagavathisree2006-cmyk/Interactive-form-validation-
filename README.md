Interactive Form Validation

Author:Bagavathi Sree. M. S

Repository:https://bagavathisree2006-cmyk.github.io/Interactive-form-validation-/

Description

This project is a web‐based registration form implementing client-side validation. It includes fields such as Name, Email, Password, Phone Number, and a Submit button. The aim is to provide instant feedback when the user enters invalid data, enforcing correct input format and improving user experience.

Features

Validates required fields before allowing submission.

Checks that email is in correct format.

Checks password strength or required criteria (e.g., minimum length) [if implemented].

Validates phone number format.

Provides feedback (error messages) when data is invalid.

Responsive layout so it works across devices.

Technologies

HTML5 for structure.

CSS3 for styling and layout.

JavaScript for validation logic.

Usage / How to run locally

1. Clone or download the repository.



git clone <repository-url>

2. Navigate to the project folder.



cd Interactive-Form-Validation

3. Open index.html (or equivalent) in your browser.


4. Use the form: fill in values, observe validation messages, then submit.



Validation Rules (example)

Here are typical rules applied in this project:

Name: Must not be empty; may require minimum number of characters.

Email: Must follow format user@example.com.

Password: Must meet criteria (e.g., minimum 8 characters, include a number or special character) [adjust according to your implementation].

Phone Number: Must be numeric and meet required number of digits (e.g., 10).

Submit button: Only enabled when all fields are valid.

Project Structure

/
index.html         ← the main HTML file
style.css          ← CSS styling
script.js          ← JavaScript for validation
assets/            ← images, icons (if any)

Customisation / Extension Ideas

Add more input types: e.g., dropdown, checkboxes, radio buttons.

Use regex patterns for more robust validation (e.g., phone with country code).

Add visual cues for valid/invalid input (icon or color change).

Add password strength meter.

Add multi-step form (wizard style).

Add server-side validation as backup.

Use a library/framework (e.g., React, Vue) for more dynamic forms.

Contribution

Contributions are welcome! If you find a bug or have an idea for improvement:

1. Fork the repository


2. Create a new branch (git checkout -b feature/YourFeature)


3. Make changes and commit (git commit -m 'Add some feature')


4. Push to the branch (git push origin feature/YourFeature)


5. Submit a Pull Request.



