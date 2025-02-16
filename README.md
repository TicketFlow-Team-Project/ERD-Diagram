# ERD-Diagram
This repository contain the ERD diagram for the Box Office Management System at Lancaster’s Music Hall.

📂 Repository Description:
This repository contains the Entity-Relationship Diagram (ERD) for the Box Office Management System at Lancaster’s Music Hall. The system is designed to manage customer bookings, ticket sales, seating arrangements, and payments efficiently while ensuring smooth operations between different teams (Box Office, Operations, and Marketing).

The ERD visually represents the database structure that supports ticket reservations, show scheduling, customer management, and transaction tracking. It helps in designing a robust system that minimizes manual processing and improves automation.

🎯 Basic Functionality
This Box Office System will enable the following functionalities:

Customer Management:

Store customer details (Name, Email, Contact).
Track customer booking history.
Apply special discounts (NHS, Military, Local Residents).
Show & Venue Management:

Store details about shows, films, and events.
Assign shows to different venues and manage seating layouts.
Prevent booking of restricted-view or inaccessible seats.
Ticket & Booking Management:

Allow single and group bookings for shows.
Prevent double-booking of seats.
Ensure wheelchair-accessible seats are correctly assigned.
Payment Processing:

Record ticket sales transactions.
Handle refunds (by authorized staff only).
Store payment methods and statuses (Paid, Pending, Cancelled).
Online Booking Integration:

Sync with an online ticketing platform via an API.
Automate seat allocation to reduce manual work.
Keep real-time updates on available seats.
🛠️ ERD Structure Overview
Customer → Stores customer details.
Order (Booking) → Tracks tickets purchased by customers.
Show → Stores event details.
Venue → Manages halls and seating configurations.
Seat → Tracks available and booked seats.
Ticket → Links customers to show seats.
Payment → Records transactions for ticket purchases.
