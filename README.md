*🚀 Neumorphic Sign Up & Sign In Forms with Advanced Client-Side Validation*


This project fulfills Module End Assignment: 02, focusing on building a responsive Sign Up form with robust client-side validation, enhanced with a modern Neumorphism (Soft UI) design. The project also includes a companion Sign In page for a complete user experience.

🌟 Features & Technologies
Category	Description
Design	Neumorphism (Soft UI): Utilizes subtle shadows to create a modern, embossed, and soft interface look, mirroring the provided design inspiration.
Layout	HTML5 & Bootstrap 5: Used for semantic structure and a fully mobile-responsive layout. The forms scale perfectly on any device size.
Validation	Advanced JavaScript: Implements real-time and on-submit validation checks. Error messages (red readings) are only displayed after a submission attempt to avoid overwhelming the user.
Security	Strong Password Policy: Uses Regular Expressions (Regex) to enforce minimum length (8 characters), and inclusion of uppercase, lowercase, number, and special character.
Usability	Password Visibility Toggles: Dedicated toggle buttons allow users to securely view and hide their passwords.
Modularity	Separate, dedicated JavaScript files for each page (signup-validation.js and signin-functionality.js) to ensure efficiency and prevent code conflicts.
Compliance	Correct placement of the Terms and Conditions invalid feedback, appearing correctly below the checkbox group.

<img width="752" height="830" alt="Screenshot 2025-11-10 034958" src="https://github.com/user-attachments/assets/92b46157-0e53-421d-8132-61bd251b5eeb" />
<img width="964" height="929" alt="Screenshot 2025-11-10 035022" src="https://github.com/user-attachments/assets/96297f2e-2b63-424a-92b3-66a6fe7e5689" />

📁 Project Structure
The project follows the standard modular structure defined in the assignment brief:

neumorphic-forms/
├── signup.html           # Main Sign Up page with full validation logic.
├── signin.html           # Companion Sign In page with basic validation.
├── css/
│   └── styles.css        # Custom Neumorphism and responsiveness styles.
└── js/
    ├── signup-validation.js   # JavaScript for Sign Up validation and toggles.
    └── signin-functionality.js # JavaScript for Sign In validation and toggles.
📋 Sign Up Form Validation Requirements
The signup.html form strictly adheres to the following client-side validation rules, enforced by a combination of HTML5 attributes and js/signup-validation.js:

Full Name: Must be present and contain only letters and spaces (min 3 characters).

Email Address: Must be present and in a valid email format.

Password: Must be present and meet strong criteria (min 8 characters, 1 uppercase, 1 lowercase, 1 number, 1 symbol).

Confirm Password: Must be present and exactly match the value in the Password field.

Terms and Conditions: The checkbox must be checked before submission is allowed.

💻 Setup and Viewing
Clone the Repository:


git clone :https://github.com/Anirudhpdines44/module-assignment-2/tree/main

🔗 Working External Links
The social media icons at the bottom of both forms are implemented as working external links, opening in a new tab:

Facebook: https://www.facebook.com

Twitter: https://www.twitter.com

Google: https://www.google.com

contact us :

https://github.com/Anirudhpdines44
