README.md for CISC3003-Individual-Project
Overview:
The Rental Property Management System is a web-based application aimed at simplifying the process of landlords uploading their properties for potential tenants to view. The system facilitates landlords in registering, logging in, and releasing their vacant properties with detailed information. Tenants can then search for available properties based on various criteria like location, rent, type, etc. This walkthrough example brief will provide an overview of the project's functionalities, architecture, technologies used, and potential future enhancements.

Functionalities:
User Authentication:
Landlords can register and log in securely to the system.
Sessions are managed to keep users logged in until they manually log out.
Landlord Dashboard:
Upon logging in, landlords are greeted with a dashboard displaying essential information like their profile picture, username, and options to navigate.
They can upload details of their vacant properties including title, location, rent, type, room configuration, area, decoration style, and additional details.
Property Search:
Tenants can search for properties based on various criteria such as location, rent range, type (joint, entire, flat, loft), room configuration, area, and decoration style.
Search results are displayed in a user-friendly format with detailed property descriptions.
Responsive Design:
The application is designed to be responsive, ensuring optimal user experience across various devices including desktops, tablets, and smartphones.
Dynamic Forms:
Forms for releasing properties and searching for properties are dynamic, providing a seamless user experience.

Architecture:
The Rental Property Management System follows a client-server architecture. The server-side scripting is implemented using PHP with a MySQL database to store user information and property details. The client-side interface is developed using HTML, CSS, and JavaScript for interactive elements such as search functionality and form validations. The system communicates with the server using AJAX for asynchronous data retrieval and submission.

Technologies Used:
Backend:
PHP: Server-side scripting language for dynamic content generation.
MySQL: Relational database management system for storing user and property data.
AJAX: Asynchronous JavaScript and XML for seamless data exchange between the client and server.
Frontend:
HTML: Markup language for structuring web pages.
CSS3: Stylesheet language for enhancing the presentation of web pages.
JavaScript: Programming language for implementing client-side interactivity and validation.
Future Enhancements:
User Reviews and Ratings:
Implement a feature for tenants to leave reviews and ratings for properties they have rented, providing valuable feedback for landlords and assisting future tenants in their decision-making process.
Advanced Search Filters:
Enhance the property search functionality with advanced filters such as proximity search, amenities, pet-friendliness, and accessibility features.
Online Payment Integration:
Integrate secure online payment methods for rental transactions, providing convenience and security for both landlords and tenants.

How to run:
First you need to start Apache and MySQL server by XAMPP. Put the folder into XAMPP/htdocs. Then open phpmyadmin and write in the sql file. Make sure the user name is 'root' and passworrd is '1223456'. Now the website will be able to work. The index website should be home.html.

Conclusion:
The Rental Property Management System aims to streamline the process of property management for landlords while providing an efficient and user-friendly platform for tenants to find their ideal rental properties. With its intuitive interface, dynamic features, and potential for future enhancements, the system stands to revolutionize the rental property market by bridging the gap between landlords and tenants in a digital era.
