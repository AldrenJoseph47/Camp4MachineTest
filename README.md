# Hotel Room Booking System

A Hotel Room Booking System built using Python and MySQL. This system allows admins to manage rooms and bookings, while customers can register, log in, view available rooms, and make bookings. 

## Features

### Admin Module
- **Admin Login**: Admin can log in using predefined credentials.
- **Create Room**: Admin can create rooms by selecting categories such as Single, Double, Suite, Convention Halls, and Ballrooms.
- **View Rooms**: Displays all rooms sorted by category and rate per day.
- **View Occupied Rooms**: Lists rooms that will be occupied for the next two days.
- **Search by Booking ID**: Allows admin to search for customer details using a booking ID.
- **View Unoccupied Rooms**: Displays rooms that are currently unoccupied.
- **Update Room Status**: Admin can update room status to 'Unoccupied' after checkout.
- **Store Records to File**: All booking records can be saved to a file.

### Customer Module
- **Registration**: New customers can register by providing their details (name, phone, email, user ID, password).
- **Login**: Customers can log in using their user ID and password.
- **View Available Rooms**: Customers can see unoccupied rooms.
- **Room Booking**: Customers can book rooms, selecting their preferred category.
- **Payment**: Handles booking payment calculation including taxes and miscellaneous charges.

## Prerequisites

- Python 3.x
- MySQL
- MySQL Connector Python library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hotel-room-booking-system.git

Password Hashing: Implement password hashing for better security.
Room Filtering: Add search and filtering options for customers when viewing rooms.
Payment Gateway Integration: Extend the system to handle online payments.
Enhanced UI: Consider developing a GUI for better user experience.

#License

This project is licensed under the MIT License - see the LICENSE file for details.
