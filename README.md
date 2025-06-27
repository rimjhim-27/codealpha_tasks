# Hotel Reservation System

## Overview
This is a simple **Hotel Reservation System** built using Java. It allows users to:

- Search available rooms by category (Standard, Deluxe, Suite)
- Book and cancel room reservations
- View all current bookings
- Simulate payment confirmation
- Persist data using file-based storage (bookings.txt)

## Features
- Object-Oriented Design (OOP)
- Room categorization and availability management
- Reservation management
- Payment status simulation
- File I/O to store and retrieve reservation data

## Technologies Used
- Java (OOP)
- File I/O (bookings.txt)

## How to Run

### Requirements
- JDK 8 or higher
- Any Java IDE (IntelliJ, Eclipse, etc.) or command-line compiler

### Steps
1. Unzip the project folder `HotelReservationSystem.zip`.
2. Open the project in your Java IDE or navigate via terminal.
3. Compile all `.java` files.
4. Run the `ReservationSystem.java` file to start the program.

### Example CLI Menu
```
1. Search Rooms
2. Book Room
3. Cancel Booking
4. View Bookings
5. Exit
```

## Project Structure
```
HotelReservationSystem/
├── Hotel.java
├── Room.java
├── Reservation.java
├── ReservationSystem.java
└── bookings.txt (created on run)
```

## Notes
- When a booking is made, it is marked as "Paid".
- Cancelled bookings will update availability.
- All booking data is stored in a text file for simplicity.

## Future Enhancements
- GUI interface using Java Swing or JavaFX
- Database integration (MySQL or SQLite)
- Email/SMS notifications

---
Developed as part of a basic hotel management system project.
