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

![Home-2](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/db528285-1a9a-49ce-919a-135b486b9f5d)

![Home-3](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/db9567ec-deae-417d-b5cf-8bf90676f0d1)

![Home-4](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/50e7967b-a2ff-4975-8ff9-8f3246510f1d)

Product' Page Explanation

 Here's an explanation of its structure and functionality:

Header Section:

Includes the Amazon logo, country selector, search bar, language selector, sign-in link, and cart icon.
Navigation links for various sections like Today's Deals, Customer Services, and Become Seller are also included.
Breadcrumb:

Displays the navigation path for the current page, indicating the category hierarchy of the product.
Product Display Section:

Divided into two main parts:
Product Images: Displays a set of thumbnail images and a larger main image of the product.
Product Details: Provides information such as product title, seller information, ratings, pricing details (discounted price, list price, shipping options), color selection, and detailed product description.
Purchase Section:

Includes details on pricing, shipping options (free shipping, Prime eligibility), delivery dates, stock availability, quantity selector, and buttons for adding to cart or buying now.
Seller information, return policy, and payment security details are also provided.
Products Slider:

Displays a slider with multiple products under a specific price range, each featuring an image, discount information, price, and a brief description.
Footer:

Contains the Amazon logo and copyright information.
Script:

Implements JavaScript to enable horizontal scrolling on the product slider when the user scrolls vertically within the slider container.
Overall Functionality:
Navigation: Allows users to navigate through different sections of the website using the header links.
Product Display: Presents detailed information about a specific product, including images, descriptions, ratings, and pricing.
Interaction: Enables users to interact with the page through actions like adding items to the cart, selecting quantities, and viewing related products in a slider format.
Responsive Design: Designed to be responsive with mobile-friendly elements like collapsible navigation and responsive images.
This structure and functionality aim to replicate the user experience found on e-commerce platforms like Amazon, providing comprehensive product information and intuitive navigation.

![Product-1](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/8a2ab78d-ec3d-444f-ac22-533dfa673daa)

![Product-2](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/30ce5ffb-206d-455b-9307-661be8a29298)

Cart Page Explanation

Header Section:

Contains the Amazon logo and navigational elements such as delivery location, search bar, language selection, and sign-in options.
Includes links to other pages like the home page, login page, and cart page.
Navigation Bar:

Provides links to various sections like Today's Deals, Customer Service, Registry, Gift Cards, and a Sell link.
Responsive design with a collapsible menu icon for mobile devices.
Cart Section:

Displays a list of products added to the cart.
Each product includes an image, title, price, bestseller tag, stock availability, delivery options, returns policy, gift options, and product specifications.
Provides actions for each item such as quantity selection, delete, save for later, compare with similar items, and share.
Cart Summary:

Shows subtotal for all items in the cart.
Prompts for potential free shipping eligibility and allows marking an order as a gift.
Provides a button to proceed to checkout.
Products Slider Section:

Displays a slider of recommended products.
Each product card includes an image, discounted price, original price, and a short description.
Footer:

Contains the Amazon logo and copyright notice.
Script Section:

Includes JavaScript to enable horizontal scrolling for the products slider when the user scrolls within it.
This product page is designed with a clear layout, detailed product information, and user-friendly navigation, aiming to enhance the shopping experience by providing essential details and easy access to various sections of the Amazon platform.

![Cart-1](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/ecb28ba6-22b8-4ef9-9515-5a7c961ee881)

![Cart-2](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/80ec45e7-853a-40d9-a560-7e4d6c5231b5)

Today's Deal's Page Explanation

Header Section:

Includes the Amazon logo, delivery location, search bar, language selector, and sign-in/account details.
Responsive design with elements adjusting based on screen size.
Navigation Bar:

Contains links to different sections like Today's Deals, Customer Services, Become Seller, Gift Cards, and Prime.
Mobile-friendly layout with a collapsible menu icon for smaller screens.
Today's Deals Carousel:

Displays various deal categories like Deal of the Day, Lightning Deals, Mobiles, Electronics, etc., in a carousel format.
Each category includes an icon and title.
Best Sellers Section:

Lists best-selling products with images, names, discount information, prices, and color options.
Designed in a grid layout with responsive columns for different screen sizes.
New Releases Section:

Features newly released products with similar details as the Best Sellers section.
Organized into rows and columns, maintaining consistency with the overall layout.
Styling and Responsiveness:

Uses Bootstrap classes for grid system, responsive navigation, carousel controls, and image scaling.
Custom CSS for styling elements like deal items, prices, discounts, and color options.
JavaScript Libraries:

Includes jQuery and Popper.js for enhancing interactivity and Bootstrap functionality.
Ensures smooth carousel sliding and dropdown menu behaviors.
This structure ensures that the Amazon clone product page is visually appealing, functional across different devices, and provides a seamless user experience similar to the original Amazon site.

![Today's Deals](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/13b4a008-95f1-406a-bdea-6a007facf5d6)

![Today's Deals-2](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/b04b33e3-6112-48a5-bae4-2f26200e5d01)

Selle'r Page Explanation 

Header:

The Amazon logo is at the top left.
There's a delivery location set to "Wagholi, Pune".
Navigation options include "Today's Deals", "Customer Services", "Become Seller", "Gift Cards", and "Prime".
There is a search bar for finding products on Amazon.
Options for "Account & Lists", "Returns & Orders", and "Cart" are on the right side of the header.
Main Section:

A large heading that says "Become a seller on Amazon.in".
A subheading encouraging users to sell on Amazon.in, described as India's most visited shopping destination. It mentions an opportunity to get benefits worth ₹25,000.
There is a "Start Selling" button, prompting users to begin the registration process to become a seller.
A note indicating that terms and conditions apply ("T&C Apply*").
Visual Element:

An image of a person holding a sign that reads "OPPORTUNITY TO GET BENEFITS WORTH ₹25,000*".
This page aims to attract new sellers to join the Amazon.in marketplace by highlighting potential benefits and providing a straightforward call-to-action button to start the selling process.

![For-Seller's](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/a0c5e2a9-577d-47c5-b0e3-e6b980ce0df7)

Customer Service Page Explanation

Structure Overview:
HTML Document Setup:

The page is set up with basic HTML structure including meta tags for character set and viewport settings.
Title of the page is set to "Amazon Clone".
A link to an external CSS stylesheet is included.
Styles:

Inline CSS defines styles for body font, layout flex properties, margins, card styles, search box styles, and other elements to control the appearance and layout of the page content.
Navigation Bar:

The navigation bar includes elements such as the Amazon logo, delivery location (Wagholi, Pune), a search bar, language selection, account options, returns and orders link, and a cart link.
Additional navigation links for "Today's Deals", "Customer Services", "Become Seller", "Gift Cards", and "Prime" are included in a secondary navigation bar.
Main Content:

The main content area contains a centered welcome message with a horizontal rule below it.
There is a section titled "Some things you can do here" that lists various help topics in a card format. Each card includes an icon, title, and brief description.
Additional sections include a search box for finding more solutions and a "Browse Help Topics" section with categorized help topics.
Help Cards:

Help cards are used to provide quick access to common help topics such as tracking orders, returns and refunds, managing addresses, payment settings, account settings, and digital services support.
Search Box:

A search input box is provided for users to type in their queries to find more specific help topics or solutions.
Help Topics Section:

This section is divided into columns with headings like "Recommended Topics", "Learn how to...", and "Try it Yourself". Each column contains a list of related help topics.
Scripts:

At the end of the body, external scripts for jQuery, Popper.js, and Bootstrap are included to add functionality and interactivity to the page.
This HTML structure and content aim to provide a user-friendly interface for Amazon customers to find help and support for various issues they may encounter while using Amazon's services.

![Customer-Service-1](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/4493e676-b526-4beb-9aba-8accf46cdc6d)

![Customer-Service-2](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/21bc2fad-6747-4cee-9cc5-6980baebe3c3)

### JavaScript Code Overview:

This JavaScript code is designed to handle a simple image slider and horizontal scrolling functionality for product containers. Here's a detailed explanation:

### Variables and Element Selection:

1. **Image Slider Elements**:
    ```javascript
    const imgs = document.querySelectorAll('#slider ul img');
    const prev_btn = document.querySelector('.control_prev');
    const next_btn = document.querySelector('.control_next');
    ```
    - `imgs`: Selects all the image elements within a `ul` element that is inside an element with the `id` `slider`.
    - `prev_btn`: Selects the button with the class `control_prev` (used to move to the previous image).
    - `next_btn`: Selects the button with the class `control_next` (used to move to the next image).

2. **Initial Index**:
    ```javascript
    let n = 0;
    ```
    - `n`: A variable to keep track of the current image index being displayed.

### Functions:

1. **changeSlide Function**:
    ```javascript
    function changeSlide() {
        for (let i = 0; i < imgs.length; i++) { // reset
            imgs[i].style.display = "none";
        }
        imgs[n].style.display = "block";
    }
    ```
    - This function hides all images by setting their `display` style to `none`.
    - Then, it sets the `display` style of the current image (indexed by `n`) to `block` to make it visible.

2. **Initial Slide Setup**:
    ```javascript
    changeSlide();
    ```
    - Calls the `changeSlide` function initially to set the first image to be visible when the page loads.

### Event Listeners for Navigation Buttons:

1. **Previous Button Click Event**:
    ```javascript
    prev_btn.addEventListener("click", (e) => {
        if (n > 0) {
            n--;
        } else {
            n = imgs.length - 1;
        }
        changeSlide();
    });
    ```
    - When the previous button is clicked, the event listener checks if `n` is greater than `0`.
    - If true, it decrements `n` to show the previous image.
    - If `n` is `0`, it sets `n` to the index of the last image (`imgs.length - 1`).
    - Calls `changeSlide` to update the visible image.

2. **Next Button Click Event**:
    ```javascript
    next_btn.addEventListener("click", (e) => {
        if (n < imgs.length - 1) {
            n++;
        } else {
            n = 0;
        }
        changeSlide();
    });
    ```
    - When the next button is clicked, the event listener checks if `n` is less than the index of the last image.
    - If true, it increments `n` to show the next image.
    - If `n` is already at the last image, it sets `n` to `0` to cycle back to the first image.
    - Calls `changeSlide` to update the visible image.

### Horizontal Scrolling Functionality:

1. **Scroll Event for Product Containers**:
    ```javascript
    const scrollContainer = document.querySelectorAll(".products");
    for (const item of scrollContainer) {
        item.addEventListener("wheel", (evt) => {
            evt.preventDefault();
            item.scrollLeft += evt.deltaY;
        });
    }
    ```
    - `scrollContainer`: Selects all elements with the class `products`.
    - For each product container, it adds an event listener for the `wheel` event.
    - When the user scrolls vertically (using the mouse wheel), the event listener prevents the default vertical scroll behavior.
    - Instead, it scrolls the container horizontally by setting the `scrollLeft` property based on the vertical scroll amount (`evt.deltaY`).

### Summary:

- The code sets up an image slider with navigation buttons to move between images.
- It ensures only one image is visible at a time.
- It allows horizontal scrolling within product containers using the mouse wheel.

This creates an interactive user experience where users can navigate through images and scroll through products smoothly.




### Back-End Code Overview Part-1 :

This Java servlet, named `login2`, handles a login request by verifying the user's credentials against a database. Here's a detailed explanation of its functionality:

### Overview:

- **Package Declaration and Imports**: 
  - The servlet is part of the `amazonPro` package.
  - It imports necessary classes for handling HTTP requests, managing database connections, and dispatching requests.

### Class and Method Definitions:

1. **Class Declaration**:
    ```java
    public class login2 extends HttpServlet {
        private static final long serialVersionUID = 1L;
    ```
    - `login2` extends `HttpServlet`, allowing it to handle HTTP requests.
    - `serialVersionUID` is a unique identifier for Serializable classes.

2. **doPost Method**:
    ```java
    protected void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
    ```
    - This method is invoked when the servlet receives a POST request.

### Main Logic:

1. **PrintWriter Initialization**:
    ```java
    PrintWriter pw = response.getWriter();
    ```
    - This creates a `PrintWriter` object to send text responses to the client.

2. **Getting Request Parameters**:
    ```java
    String u = request.getParameter("mob");
    ```
    - Retrieves the value of the "mob" parameter from the HTTP request.

3. **Database Connection Setup**:
    ```java
    Class.forName("oracle.jdbc.driver.OracleDriver");
    Connection c = DriverManager.getConnection("jdbc:oracle:thin:@localhost:1521:xe", "system", "system");
    ```
    - Loads the Oracle JDBC driver.
    - Establishes a connection to the Oracle database using the specified URL, username ("system"), and password ("system").

4. **SQL Query Preparation and Execution**:
    ```java
    PreparedStatement ps = c.prepareStatement("select * from signup where name=?");
    ps.setString(1, u);
    ps.execute();
    ResultSet rs = ps.executeQuery();
    ```
    - Prepares a SQL query to select records from the `signup` table where the `name` matches the value of the "mob" parameter.
    - Sets the value of the first parameter in the query to the retrieved username.
    - Executes the query and stores the result in a `ResultSet`.

5. **Processing the ResultSet**:
    ```java
    if(rs.next()) {
        RequestDispatcher rd = request.getRequestDispatcher("index.html");
        rd.forward(request, response);
    }
    else {
        pw.print("Sorry username and password is incorrect");
        RequestDispatcher rd = request.getRequestDispatcher("signup.html");
        rd.include(request, response);
    }
    ```
    - Checks if the `ResultSet` contains any records.
    - If a record is found (user exists), forwards the request to `index.html`.
    - If no record is found (user does not exist), prints an error message and includes the content of `signup.html` in the response.

6. **Closing the Connection**:
    ```java
    c.close();
    ```
    - Closes the database connection.

7. **Exception Handling**:
    ```java
    catch (Exception e) {
        System.out.println(e);
    }
    ```
    - Catches and prints any exceptions that occur during the process.

### Summary:

- The servlet retrieves the "mob" parameter from the request.
- It connects to an Oracle database and checks if a user with the provided name exists in the `signup` table.
- If the user exists, it forwards the request to `index.html`.
- If the user does not exist, it displays an error message and includes `signup.html` in the response.
- It handles exceptions and ensures the database connection is closed after the operation.




### Back-End Code Overview Part-2 :


This Java servlet, named `signup`, handles user registration by inserting new user data into a database. Here's a detailed explanation of its functionality:

### Overview:

- **Package Declaration and Imports**: 
  - The servlet is part of the `amazonPro` package.
  - It imports necessary classes for handling HTTP requests, managing database connections, and dispatching requests.

### Class and Method Definitions:

1. **Class Declaration**:
    ```java
    public class signup extends HttpServlet {
        private static final long serialVersionUID = 1L;
    ```
    - `signup` extends `HttpServlet`, allowing it to handle HTTP requests.
    - `serialVersionUID` is a unique identifier for Serializable classes.

2. **doPost Method**:
    ```java
    protected void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
    ```
    - This method is invoked when the servlet receives a POST request.

### Main Logic:

1. **PrintWriter Initialization**:
    ```java
    PrintWriter pw = response.getWriter();
    ```
    - This creates a `PrintWriter` object to send text responses to the client.

2. **Getting Request Parameters**:
    ```java
    String n = request.getParameter("Fname");
    String m = request.getParameter("No");
    String p = request.getParameter("Pass");
    ```
    - Retrieves the values of the "Fname", "No", and "Pass" parameters from the HTTP request, which correspond to the user's name, phone number, and password, respectively.

3. **Database Connection Setup**:
    ```java
    Class.forName("oracle.jdbc.driver.OracleDriver");
    Connection c = DriverManager.getConnection("jdbc:oracle:thin:@localhost:1521:xe", "system", "system");
    ```
    - Loads the Oracle JDBC driver.
    - Establishes a connection to the Oracle database using the specified URL, username ("system"), and password ("system").

4. **SQL Query Preparation and Execution**:
    ```java
    PreparedStatement ps = c.prepareStatement("insert into signup values (?,?,?)");
    ps.setString(1, n);
    ps.setString(2, m);
    ps.setString(3, p);
    ps.execute();
    ResultSet rs = ps.executeQuery();
    ```
    - Prepares a SQL query to insert a new record into the `signup` table with the provided name, phone number, and password.
    - Sets the values of the parameters in the query to the retrieved user details.
    - Executes the query to insert the new user data into the database.

5. **Update Check and Request Forwarding**:
    ```java
    int b = ps.executeUpdate();
    if(b > 0) {
        RequestDispatcher rd = request.getRequestDispatcher("login.html");
        rd.forward(request, response);
    }
    ```
    - Executes the `executeUpdate` method, which returns the number of rows affected by the insert operation.
    - If the insertion is successful (i.e., `b > 0`), forwards the request to `login.html` for the user to log in.

6. **Exception Handling**:
    ```java
    catch (Exception e) {
        e.printStackTrace(); // Log the exception stack trace
        System.out.println("Something went wrong!!!!!!! " + e.getMessage());
    }
    ```
    - Catches and logs any exceptions that occur during the process.
    - Prints the exception message to the console for debugging purposes.

### Summary:

- The servlet retrieves user registration details from the request.
- It connects to an Oracle database and inserts the new user data into the `signup` table.
- If the insertion is successful, it forwards the request to `login.html`.
- It handles exceptions by logging the stack trace and printing an error message.



### SQL Code Overview :

The provided SQL statement creates a table named `signup` with three columns. Here's a detailed explanation of the code:

```sql
CREATE TABLE signup (
    name VARCHAR(100),
    mobile VARCHAR(100),
    pass VARCHAR(100)
);
```

### Explanation:

1. **CREATE TABLE signup**:
    - This command creates a new table called `signup` in the database.

2. **Columns**:
    - `name VARCHAR(100)`: 
        - `name` is the column name.
        - `VARCHAR(100)` specifies that this column can store variable-length character strings up to 100 characters long.
    
    - `mobile VARCHAR(100)`:
        - `mobile` is the column name.
        - `VARCHAR(100)` specifies that this column can store variable-length character strings up to 100 characters long.

    - `pass VARCHAR(100)`:
        - `pass` is the column name.
        - `VARCHAR(100)` specifies that this column can store variable-length character strings up to 100 characters long. 

### Summary:
The SQL statement creates a table named `signup` with three columns (`name`, `mobile`, and `pass`), all of which can store strings up to 100 characters in length.


![SQL-Data](https://github.com/Avishkar709/Amazon_Clone_Java/assets/165990602/e1f18fb5-61c8-43c3-9b75-5dd0f846a303)



