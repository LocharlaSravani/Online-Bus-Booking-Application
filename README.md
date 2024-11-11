
# Online Bus Booking Application

# Description:
An Online Bus Booking Application that allows users to search and book bus tickets for various destinations. The application supports features such as user authentication, bus seat selection, payment processing, and ticket generation. The backend is built using PHP and MySQL, providing a user-friendly interface for booking tickets for AC buses, managing seat availability, and generating printable tickets.

# Key Features:
User Authentication:

New User Registration: Users can sign up with a validated form.
Login System: Existing users can log in securely with a validated form.
Bus Ticket Booking:

Bus Selection: Users can browse available buses, including AC buses.
Seat Selection: Users can choose the number of seats they want, based on the available seats for the selected bus.
Automatic Seat Update: The system automatically updates seat availability in the database after booking.
Payment Integration:

Payment Form: A fully validated payment form with:
16-digit card number validation.
3-digit CVV validation.
Expiry date must be at least two weeks from the current date.
Ticket Generation:

Users can generate and print tickets containing all relevant passenger and bus details.
Databases:

Two separate databases:
User Database: Stores user login details.
Bus Database: Stores bus details, including available seats and routes.
# Technologies Used:
PHP: Backend development for user authentication, booking logic, and ticket generation.
MySQL: Database management for storing user and bus data.
JavaScript: Client-side validation for forms and dynamic seat selection.
HTML & CSS: Responsive frontend design for easy navigation and booking.
# Installation:
Upload Files:
Upload the online_bus directory to your chosen server or local directory.
Set Up Database:
Open PhpMyAdmin (or a similar MySQL database tool).
Create a new database and import the provided SQL file to set up the database schema.
Configure Database Connection:
Open the PHP files and configure your database connection settings (username, password, database name).
Access the Application:
Open a browser and navigate to the application:
Example: http://localhost/online_bus
System Ready:
The system is now ready to handle bus bookings and payments!
Future Enhancements:
User Profile Management:

Allow users to view their booking history and update personal information.
Admin Panel:

Implement an admin panel for managing buses, users, and bookings.
Bus Schedule Management:

Add functionality for bus schedule updates and cancellations.
Email & SMS Notifications:

Integrate email and SMS notifications for booking confirmations and reminders.
Payment Gateway Integration:

Integrate with payment gateways like PayPal, Stripe, etc., for secure payments.
Benefits:
Convenience: Users can easily browse, book, and pay for bus tickets online.
Security: Validated payment forms ensure secure transactions.
Real-time Updates: Seat availability is automatically updated after each booking.
Printable Tickets: Users can generate and print their tickets with all relevant details.
This online bus booking system provides a seamless experience for both bus operators and passengers, with robust backend and frontend functionality.
