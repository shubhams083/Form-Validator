Project: Secure Form Validator
This project provides a client-side solution for a secure and user-friendly login and registration system. It's built with vanilla HTML, CSS, and JavaScript, using Tailwind CSS for modern styling.

Features
Registration Page (register.html):

Live Validation: Users receive immediate feedback as they type.

Email Validation: Ensures the email address is in a correct format.

Strong Password Enforcement: A clear checklist guides users to create a secure password that meets specific criteria:

Minimum of 8 characters

At least one uppercase letter

At least one lowercase letter

At least one number

At least one special character (!@#$%)

Password Confirmation: Verifies that the "Confirm Password" field matches the "Password" field.

Password Visibility Toggle: An eye icon allows users to show or hide the password to prevent typos.

Accessible Design: Uses ARIA attributes to ensure usability for screen reader users.

Login Page (login.html):

A clean and simple form for returning users.

Includes email and password fields.

Features the same password visibility toggle for user convenience.

Tech Stack
HTML5: For the structure and semantics of the forms.

Tailwind CSS: For a utility-first, responsive, and modern design.

Vanilla JavaScript: For all client-side validation logic and DOM manipulation. No external libraries are needed.

File Structure
A recommended folder structure for this project would be:

/
|-- login.html
|-- register.html
|-- README.md
|-- assets/ (optional folder for CSS, JS, or images if you split them out)

How to Use
Clone or download the repository.

Open register.html or login.html in your web browser.

No build process or dependencies are required.

Future Development (Backend)
This project focuses solely on the client-side user interface and validation. A complete implementation would require a backend service (e.g., using Node.js, PHP, Python) to handle:

Securely hashing and storing user passwords.

Verifying user credentials during login.

Managing user sessions.

Connecting to a database (e.g., MySQL, PostgreSQL, MongoDB).
