# Car Reservation System

# Introduction
Our project aims to achieve multiple objectives in light of the changing car rental industry. We will focus on developing a user-friendly system that includes efficient calculations and seamless integration with a strong database. The primary aim is to redefine the car rental experience, eliminating traditional hassles and introducing a modern, digitalized approach that prioritizes user convenience and system efficiency.

## Problem Statement
Managing car reservations efficiently is crucial for organizations or individuals offering car rental services. Our Car Reservation System aims to streamline the process by providing a user-friendly interface to view available cars, make reservations, and manage existing bookings. The system ensures a seamless experience for users while optimizing the utilization of the available car fleet.

# Requirments
1.	To install XAMPP as a local server.
2.	To create the database on XAMPP server using MySQL.
3.	To code the dashboard, signup and login pages with any language. In our case we use PHP and HTML.
4.	To display the car rental amount on the dashboard after selecting the car and duration on the backend.
5.	To develop the GUI of the system and have some friendly animation. 

## System Overview
The Car Reservation System is a PHP-based web application that utilizes a MySQL database for data storage. It comprises three main components: the database interaction layer, the user authentication module, and the dashboard for users to interact with the reservation system.

# Desing Procedure 
This part outlines the design techniques that influenced the development of the "CARENTAL" project. The methods are categorized into four primary sections, each focusing on a crucial element of our growth process.

In the initial phase of the "CARENTAL" project, we focused on setting up the environment and database. This involved the use of XAMPP to create a robust development environment that integrates Apache, MySQL, PHP, and Perl. The database setup was pivotal, as we established a MySQL database to manage crucial data related to users, cars, and bookings. Points within this part include "Environment Setup" and "Database Setup," both of which laid the foundation for the project's development and data management.

The second phase focused on Security and user authentication were paramount in ensuring the trustworthiness of the "CARENTAL" system. To achieve this, we implemented a comprehensive set of procedures. "Signup and Login Setup" was instrumental, where a hashing function was introduced to encrypt user passwords and enhance security. Additionally, "User Data Hashing" was a crucial step in safeguarding sensitive information. These measures collectively ensured that user data remained secure and protected from unauthorized access.

Then we started with the user interface and overall system functionality that were key aspects of delivering good user experience. Within this part, "Dashboard Setup" played a central role, as we developed the primary interface using PHP. A visually appealing and user-friendly "GUI Implementation" was crucial to make the system easy to navigate. The "Implementation of OOP Classes" ensured a structured and maintainable codebase, allowing for efficient management of user interactions and data. The "Booking System" was another vital component in this phase, allowing users to reserve cars seamlessly.

Efficient data management and catering to user preferences were addressed in this part. We initiated "Database Initialization on XAMPP Server" to ensure the smooth storage and retrieval of user data. To manage user and car data effectively, "Creation of 'users' and 'cars' Tables" was implemented, providing structured data organization. Lastly, "Offering Various Car Categories" was integrated into the system to offer users a diverse selection of vehicles to choose from, enhancing their overall experience.

## Components

### Database Interaction
The `Database.php` file handles database connections and queries. It facilitates communication with the MySQL database, ensuring that relevant data is retrieved and updated accurately.

### Car Operations
The `Car.php` class manages car-related operations, such as retrieving a list of all available cars, making reservations, releasing reservations, and processing returns. It interacts with the MySQL database to maintain accurate information about car reservations.

### User Management
The `User.php` class is responsible for user-related operations, including user authentication. It ensures that only authenticated users can access the dashboard and perform reservation-related actions.

### Dashboard
The `dashboard.php` file serves as the main user interface, displaying available cars, their details, and reservation statuses. Users can make new reservations, return cars, and view their existing bookings.

## Usage

1. Ensure that your PHP environment supports sessions.
2. Set up a MySQL database and update the `Database.php` file with your database credentials.
3. Access the `login.php` page to log in or create a new account.
4. Upon successful login, you will be redirected to the dashboard (`dashboard.php`).
5. View available cars, make reservations, and manage existing bookings.
6. Logout using the "Logout" button in the top right corner.

## File Structure

- `Database.php`: Manages database connections and queries.
- `Car.php`: Handles car-related operations and interactions with the database.
- `User.php`: Manages user-related operations and authentication.
- `dashboard.php`: Main dashboard displaying available cars and reservation functionality.
- `login.php`: User login and registration page.
- `logout.php`: Handles user logout.
- `styles.css`: External CSS file for styling.
- `animate.min.css`: External CSS library for animations.

## Dependencies

- [Animate.css](https://animate.style/): CSS library for animations.

## Notes

- Ensure proper database configuration in `Database.php`.
- User authentication is implemented to restrict access to authenticated users.
- Reservation actions are processed through the `Car.php` class.

# Conclusion
The CARENTAL project lays the groundwork for a dependable and highly efficient system with its strong OOP design. This architectural strategy guarantees smooth performance and functionality, which adds to the project's overall success.

With a focus on protecting user privacy, CARENTAL has implemented a secure database and advanced data hashing algorithms to ensure the highest level of protection for user data. By placing a strong emphasis on data security, CARENTAL is positioned as a reliable and responsible solution in line with industry standards.

With an innovative price calculating capability and an easy graphical user interface, CARENTAL prioritizes user-friendliness over technical prowess. The project is an exceptional example of software engineering innovation in the cutthroat automobile rental industry since it not only demonstrates technological prowess but also strives to improve the whole customer experience.


Feel free to customize the system to meet your specific requirements or add additional features. If you encounter any issues, refer to the error logs and ensure that your environment meets the necessary requirements.
