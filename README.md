# Airline-Management-System
It's an C++ code for Airline Management System
The Airline Management System is a C++ program that organizes flight schedules and
passenger bookings. It uses an intuitive menu system to provide separate panels for
administrators and passengers. Administrators can manage flights by adding, updating, or
deleting records, while passengers can view flights, book tickets, and manage their
reservations. The system employs structured programming, input validation, and automated ID
generation for efficient data handling.

**Pseudo Code:**
1. Start
2. Display Main Menu:
 a. Enter 1 for Admin Panel
 b. Enter 2 for Passenger Operations
 c. Enter 3 to Exit
3. If user enters 1 (Admin Panel):
 a. Ask for the admin password.
 b. If password is correct:
 Display Admin Menu:
 1. Add Flight
 -Ask admin to enter flight details flight ID, destination, and departure time.
 - Store the details
 2. Update Flight
 - Ask admin for flight ID to update.
 - If flight exists, allow admin to modify details.
 - Store the updated details.
 3. Delete Flight
 - Ask admin for flight ID to delete.
 - If flight exists, delete the flight.
 4. View Flights
 - Display all available flights.
 ii. Return to Admin Menu after each operation or allow exit to Main Menu.
 c. If password is incorrect
 - Ask user to renter the password
4. If user enters 2 (Passenger Operations):
 a. Display Passenger Menu:
 1. View Available Flights
 - Display a list of all flights with their details (flight ID, destination, and departure
time.)

 2. Book a Ticket
 - Ask passenger for flight ID to book.
 - Check if the flight exists.
 - If flight exists, ask for passenger details (name, age, contact info).
 - Save the booking.
 3. Cancel a Ticket
 - Ask passenger for their booking ID.
 - Check if the booking exists.
 - If booking exists, remove it.
 4. View Bookings
 - Ask passenger for their name or booking ID.
 - Display all bookings made by the passenger.
 b. After each operation, return to Passenger Menu or allow exit to Main Menu.
5. If user enters 3:
 - Terminate the program.
6. If user enters an invalid option:
 a. Display "Invalid input! Please try again."
 b. Return to Main Menu.
7. End
