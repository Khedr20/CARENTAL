# Car Reservation System

## Problem Statement
Managing car reservations efficiently is crucial for organizations or individuals offering car rental services. Our Car Reservation System aims to streamline the process by providing a user-friendly interface to view available cars, make reservations, and manage existing bookings. The system ensures a seamless experience for users while optimizing the utilization of the available car fleet.

## System Overview
The Car Reservation System is a PHP-based web application that utilizes a MySQL database for data storage. It comprises three main components: the database interaction layer, the user authentication module, and the dashboard for users to interact with the reservation system.

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

Feel free to customize the system to meet your specific requirements or add additional features. If you encounter any issues, refer to the error logs and ensure that your environment meets the necessary requirements.
