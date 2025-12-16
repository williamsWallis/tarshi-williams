This mini-project outlines the creation and deployment of a simple, one-page online student registration form for Vishi Higher Institute.


Here is a breakdown of the tasks and requirements, designed to guide you through the process of building, styling, integrating, and deploying the website.

💻 Project Overview & Objectives
The goal is to design and build a small, real-world registration form website using standard web technologies.

Learning Outcomes
By completing this project, you will gain experience in:

Structuring a clean HTML5 page for a web form.

Creating a neat, responsive layout using Bootstrap and custom CSS.

Connecting a form to Formspree for email submissions.


Storing code and managing versions using GitHub.

Deploying a static website using Netlify.

✅ Step-by-Step Requirements
1. Page Layout and Content (index.html)
You must create a single index.html file with the following structure:

Header Area:

Vishi Higher Institute logo placeholder (text is acceptable).

Page title (e.g., "New Student Registration").

Short paragraph explaining the form's purpose.


Main Section: Contains the registration form.

Footer:

"Vishi Higher Institute".

Your name and matricule.

Current year.


Styling Note: Use a responsive Bootstrap container to ensure the layout is functional on desktop, tablet, and mobile screens.

2. Registration Form Fields
The form must collect at least the following required information:

First name

Last name

Email address (must use type="email")

Phone number

Date of birth

Gender (radio buttons)

Faculty or School (select dropdown)

Program of study (select dropdown)

Level (e.g., HND 1, BTech 1)

Mode of study (full time or part time, radio buttons)

Address (textarea)

Password and Confirm password

A confirmation checkbox: "I confirm that the information provided is correct" (must be required)


Validation: All important fields must use appropriate HTML5 validation attributes (e.g., required, type="email"). Guidance: Use proper <label> tags and placeholder attributes to assist the user.


3. Styling with Bootstrap and Custom CSS

Bootstrap: Use Bootstrap 4 or 5 (CDN link is allowed).

Center the form on the page using a Bootstrap grid.

Wrap the form in a Bootstrap card or panel.

Use form-group or appropriate spacing classes.

Use form-control for input fields.

Use a primary-styled submit button.

Custom CSS (styles.css):

Set a simple background color or gradient for the page.

Add spacing around the form.

Customize the button hover effect.

Ensure all fonts and colors are consistent and readable.


4. Formspree Integration
You will use Formspree to process the form submissions and send them to an email address.


Steps:

Create a free Formspree account and a new form.

Copy the unique form endpoint URL.

Set the form's action and method attributes in your HTML:
