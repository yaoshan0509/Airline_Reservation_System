# Airline Reservation System
Course: Programming Concepts and Practices

# Overview
This C++ console application serves as a basic flight booking system with the following core features:
- Flight Listings: Displays available flights by reading from the `flight.txt` file, including flight ID, destination, and departure time.
- User Account System: Allows users to sign up and log in, with credentials stored in the `user.txt` file.
- Flight Booking: Logged-in users can book flights by selecting a destination, choosing a flight, and picking a seat type (standard or premium). Booking details are saved in `reserved.txt` after a mock payment step.
- Booking History: Users can view and modify their previous bookings.

Admin Functions (default login: `admin`):
- Manage users: View all registered users.
- Manage flights: Add or delete flights in `flight.txt`.
- Generate reports: Create a basic summary of flight bookings.

# Technical Details
- Built using standard C++ libraries (`<iostream>`, `<fstream>`, `<string>`, etc.).
- Uses Windows-specific API (`<windows.h>`) for console handling and window maximization.
- Data persistence via plain text files:
  <br>- `flight.txt` for flight schedules
  <br>- `user.txt` for account credentials
  <br>- `reserved.txt` for booked tickets

# Usage
1. Build the program using a C++ compiler compatible with Windows.
2. Launch the executable; the console window will automatically open in maximized mode.
3. Follow the on-screen instructions to access either the user or admin menu.

