# Amazon_Clone_Java
Amazon Clone
Welcome to the Amazon Clone project! This repository contains a full-stack web application that mimics the core functionalities of the popular e-commerce platform, Amazon.

Technologies Used
Frontend
HTML: For structuring the web pages.
CSS: For styling and layout.
JavaScript: For interactive elements and dynamic content.
Bootstrap: For responsive design and UI components.
Backend
JDBC (Java Database Connectivity): For connecting and executing SQL queries in Java.
Oracle SQL: For database management and data persistence.
Features
User Authentication: Sign up, log in, and manage user accounts.
Product Listings: Browse and search through a catalog of products with detailed information.
Shopping Cart: Add, update, and remove items from the shopping cart.
Order Management: Place orders and view order history.
Admin Panel: Manage products, users, and orders.
Getting Started
Prerequisites
Java Development Kit (JDK)
Oracle Database
Apache Tomcat or any other Java EE server
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/amazon_clone.git
Set up the Oracle database and configure JDBC connection details in the config file.
Deploy the application on your Java EE server.
Access the application at http://localhost:8080/amazon_clone.

Login Page Explanation

This HTML document represents a basic login page for an Amazon-like website. Here’s a breakdown of its key components and functionality:

Structure and Styling
The document is structured using standard HTML5 elements. The <head> section includes metadata, the title of the page, and a link to an external CSS file (login.css) for styling.
The <body> contains the main content of the page, including a form for user input and a footer for additional information and links.
Form Section
The form is set to submit data to a server-side script (login2) using the POST method.
An Amazon logo, which is also a clickable link to the homepage (index.html), is displayed at the top.
The main container (login-container) houses the form elements:
A title "Sign in".
A label and input field for the user’s email or mobile phone number.
A submit button styled with a yellow background, matching Amazon's branding, and other styling attributes to enhance its appearance.
Additional Information and Links
Below the submit button, there are terms of service links (Conditions of Use and Privacy Notice) and a "Need help" option.
A section for business customers encourages users to shop on Amazon Business.
The "New to Amazon?" section prompts new users to create an account, providing a styled button that links to the signup page (signup.html).
Footer
The footer includes three links: Conditions of Use, Privacy Notice, and Help, providing users with quick access to important information.
A copyright notice indicates the website’s affiliation with Amazon.
Accessibility and Usability
The page is designed to be responsive, ensuring it looks good on various devices by including the meta viewport tag.
Clear labels and button text enhance usability, ensuring users understand what actions they can take.
This login page is straightforward and user-friendly, designed to provide a seamless sign-in experience while adhering to Amazon’s familiar styling and layout conventions.

![Sign-in](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/b66c0046-6c14-4f71-b79b-f9b673ed6bb5)

Sign-Up Page Explanation

This HTML document represents a basic sign-up page for an Amazon-like website. Here’s a breakdown of its key components and functionality:

Structure and Styling
The document is structured using standard HTML5 elements. The <head> section includes metadata, the title of the page, and a link to an external CSS file (login.css) for styling.
The <body> contains the main content of the page, including a form for user input and a footer for additional information and links.
Form Section
The form is set to submit data to a server-side script (signup) using the POST method.
An Amazon logo, which is also a clickable link to the homepage (index.html), is displayed at the top.
The main container (login-container) houses the form elements:
A title "Sign up".
A label and input field for the user’s name.
A label and input field for the user’s mobile number or email.
A label and input field for the user’s password, with a placeholder indicating the password should be at least 6 characters.
A submit button styled with a yellow background, matching Amazon's branding, and other styling attributes to enhance its appearance.
Additional Information and Links
Below the submit button, there are terms of service links (Conditions of Use and Privacy Notice) and a "Need help" option.
A section for business customers encourages users to shop on Amazon Business.
The "Have an account?" section prompts existing users to log in, providing a styled button that links to the login page (login.html).
Footer
The footer includes three links: Conditions of Use, Privacy Notice, and Help, providing users with quick access to important information.
A copyright notice indicates the website’s affiliation with Amazon.
Accessibility and Usability
The page is designed to be responsive, ensuring it looks good on various devices by including the meta viewport tag.
Clear labels and button text enhance usability, ensuring users understand what actions they can take.
This sign-up page is designed to provide a straightforward and user-friendly registration experience while adhering to Amazon’s familiar styling and layout conventions.

![Sign-Up](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/74a8aa80-fb8d-410c-8046-20016e948648)

Amazon Clone Home Page Explanation

This HTML document represents the home page of an Amazon-like website clone. Here’s a breakdown of its key components and functionality:

Structure and Styling
The document begins with a <head> section that includes metadata, the title of the page ("Amazon Clone"), and a link to an external CSS file (style.css) for styling.
The <body> section contains the main content of the page, including navigation, sliders, product sections, and a footer.
Navigation
The <nav> element contains:
An Amazon logo that links to the home page (index.html).
A section displaying the delivery location with an icon and location name.
A search bar with a dropdown for selecting search categories.
Language selection and account-related links such as "Hello, sign in" and "Account & Lists".
Icons for user profile (hidden on mobile) and shopping cart (cart.html).
Bottom Navigation
The <div class="nav-bottom"> section includes links to various sections:
"All", "Today's Deals", "Customer Services", "Become Seller", "Gift Cards", and "Prime".
Header Slider
<div class="header-slider"> contains a carousel of images (<ul> and <li> elements) for promotional headers with navigation controls.
Header Boxes
<div class="header-box box-row"> and subsequent <div class="box-row"> sections display boxes with images and links to different product categories like "Free international returns", "Lunar New Year", "Toy under $25", and "Deals in PCs".
Product Sliders
<div class="products-slider"> sections display lists of product images with headings like "Best Sellers in Sports & Outdoors".
Products with Prices
<div class="products-slider-with-price"> shows product cards with images, discounts, prices, and descriptions under "$25 deals".
Footer
The <footer> includes:
An Amazon logo that links to the home page.
Copyright information indicating the website’s affiliation with Amazon.
Script
The <script> tag includes a reference to an external JavaScript file (script.js) for additional functionality.
Accessibility and Usability
The page is designed to be responsive (meta viewport tag included) and provides clear navigation and categorized product displays to enhance user experience.
This home page replicates the layout and functionality of Amazon's main page, providing a familiar browsing experience for users.

![Home-1](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/5b3eaf76-5de6-4d53-a29d-c8087b3d3c28)


