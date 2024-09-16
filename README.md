Hotel Room Booking System
A command-line Hotel Room Booking system built using Python and MySQL. This application allows hotel administrators to manage rooms and bookings, while customers can register, log in, and book rooms based on availability.

Features
Admin Module
Admin Login: Admins can log in with predefined credentials.
Room Management:
Create rooms with different categories (Single, Double, Suite, Convention Halls, Ballrooms).
View a list of all rooms with details like room number, category, rate, and occupancy status.
View occupied rooms for the next two days.
Update rooms to "Unoccupied" status.
Export all booking records to a text file.
Booking Search: Search for a booking by booking ID to get details of the customer and room.
Customer Module
Customer Registration and Login: Customers can register with their details and securely log in using their credentials.
View Available Rooms: View a list of unoccupied rooms, categorized by type and rate.
Room Booking: Book rooms for a specified number of days, pay an advance, and receive booking details including total amount due.
Database Structure
The system uses a MySQL database named Hotelbooking with three main tables:

Customers: Stores customer information including user ID and password.
Rooms: Stores room details such as room number, category, rates, and occupancy status.
Bookings: Stores booking details including customer and room references, occupancy duration, and billing information.
Prerequisites
Python 3.x
MySQL Server
MySQL Connector for Python: mysql-connector-python (Install via pip)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/hotel-booking-system.git
cd hotel-booking-system
Install MySQL Connector for Python:

bash
Copy code
pip install mysql-connector-python
Configure MySQL database:

Ensure that MySQL is running and create a user with the required privileges.
Update the db_connection configuration in the script to match your MySQL credentials (host, user, password).
Run the application:

bash
Copy code
python hotel_booking_system.py
Usage
On startup, choose whether to log in as an Admin or a Customer.
Admins can manage room inventory, view reports, and update room statuses.
Customers can register, log in, view available rooms, and make bookings.
Admin Credentials
Predefined admin credentials:

User ID: admin
Password: admin123@
Screenshots (Optional)

Future Enhancements
Password Hashing: Implement password hashing for better security.
Room Filtering: Add search and filtering options for customers when viewing rooms.
Payment Gateway Integration: Extend the system to handle online payments.
Enhanced UI: Consider developing a GUI for better user experience.
License
This project is licensed under the MIT License - see the LICENSE file for details.
