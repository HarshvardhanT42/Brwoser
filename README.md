Overview
This project is a basic web application built using HTML, CSS, and Python with Flask. The site includes a home page and a contact page, allowing users to navigate between these sections and submit contact information through a form.

Features
Home Page (index.html)

Header: Contains the site title and navigation links.
Main Content: Provides an introduction or welcome message for the site.
Footer: Includes copyright information.
Contact Page (contact.html)

Header: Similar to the home page, with navigation links.
Contact Form: Allows users to submit their name, email address, and a message. This form uses the POST method to send data to the server.
Footer: Consistent with the home page footer.
Styling (style.css)

Layout and Design: Basic styles to enhance the visual presentation of the site. This includes header and footer styling, form layout, and general page design.
Flask Application (app.py)

Routing: Defines routes for the home page (/) and the contact page (/contact).
Form Handling: Processes form submissions from the contact page. For simplicity, this example redirects users back to the home page upon form submission.
Technologies Used
HTML: For structuring the content of the web pages.
CSS: For styling the web pages and ensuring a consistent look and feel.
Python with Flask: For serving the web pages and handling form submissions.
How It Works
Server Setup: The Flask application (app.py) is run to start a local web server.
Page Rendering: Users visit the home page or contact page, which are rendered by Flask using HTML templates.
Form Submission: When a user submits the contact form, the Flask application processes the form data and redirects the user back to the home page.
Potential Enhancements
Database Integration: Store form submissions in a database.
Email Notifications: Send an email notification upon form submission.
Additional Pages: Add more pages or features, such as an about page or a blog section.
Advanced Styling: Implement a more sophisticated design using frameworks like Bootstrap or custom CSS.
