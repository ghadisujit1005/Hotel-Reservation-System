# 🏨 Hotel Reservation System

##  Project Overview :
The **Hotel Reservation System** is a database-driven application designed to automate and manage hotel bookings efficiently.  
This project uses **SQL** to handle hotel data such as rooms, customers, reservations, staff, and payments.

It eliminates manual booking errors, prevents overbooking, and provides real-time availability and reporting.

--- code --

##  Objectives :
- Automate hotel room reservations and management
- Track room availability in real time
- Maintain customer, staff, and payment records
- Improve booking accuracy and efficiency
- Generate useful business reports

---

##  Technologies Used:
- **Database:** MySQL / PostgreSQL / SQLite  
- **Language:** SQL  
- **Tools:** MySQL Workbench / pgAdmin / SQLiteStudio  

---

##  Database Schema:
### Main Tables:
- **Hotels** – Hotel details  
- **Rooms** – Room information and pricing  
- **Customers** – Guest details  
- **Reservations** – Booking records  
- **Payments** – Payment transactions  
- **Staff** – Hotel staff information  

---

##  Key Features:
- Room booking and cancellation
- Real-time room availability
- Customer and staff management
- Payment tracking
- Revenue and occupancy analysis
- Prevents double booking

---

## Sample SQL Queries:
```sql
-- List all rooms in a hotel
SELECT r.room_number, r.room_type, r.price_per_night
FROM Rooms r
JOIN Hotels h ON r.ho

```

Reports Generated :
Total revenue per hotel
Monthly booking trends
Occupancy rates
Customer booking history
Staff allocation per hotel


How to Run the Project :-
Create a database in your SQL environment
Run the provided SQL scripts to create tables
Insert sample data
Execute queries for analysis and reporting


Future Enhancements:
Web interface using HTML/CSS/JavaScript
User authentication & roles
Online payment gateway integration
Advanced analytics dashboard


Author
Name: Sujit Ghadi
GitHub: 
