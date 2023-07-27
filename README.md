# WebJournal

## Description

WebJournal is a web application built with Flask, a Python web framework, that allows users to create and manage their journal entries. The application follows the Model-View-Controller (MVC) pattern, with the back-end written in Python using Flask and the front-end utilizing HTML, CSS, and JavaScript. In this project, the frontend is used only to test the backend

The application includes the following features:

- User registration and login: Users can sign up for an account with a unique username and email. Passwords are securely hashed before being stored in the database. Users can log in to their accounts to access their journal.

- User account management: Once logged in, users can update their account information, such as their username, email, and profile picture. They can also change their password if needed.

- Journal entries: Logged-in users can create new journal entries with a title and content. The application records the date and time of each entry automatically.

- Journal entry management: Users can view their journal entries on the home page, and they have the option to edit or delete existing entries.

- Pagination: The home page displays journal entries in paginated form, showing a limited number of entries per page for better user experience.

- Password reset: Users who forget their passwords can request a password reset via email. The application sends a reset link to the registered email, allowing users to create a new password.
