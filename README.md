# 🚗 Vehicle Rental System Database

The Vehicle Rental System Database manages customers, vehicles, bookings, payments, maintenance records, and staff in a structured relational model.

## Use Case

This system is designed for vehicle rental businesses to track:

- Customer registrations
- Vehicle categories and availability
- Bookings and rental periods
- Payment transactions
- Maintenance history
- Staff responsibilities

---

## Database Structure

### Entity Overview

| Entity           | Description |
|------------------|-------------|
| `VehicleCategory`| Defines vehicle types (e.g., Car, Van, Bike) and daily rental rates |
| `Vehicle`        | Stores information about each vehicle, including category and availability |
| `Customer`       | Holds customer details including license number |
| `Staff`          | Employees who manage bookings and maintenance |
| `Booking`        | Rental transactions between customers and vehicles |
| `Payment`        | Payments made for bookings |
| `Maintenance`    | Maintenance records for vehicles, handled by staff |

### Entity-Relation Diagram
![Rental-Vehicle-ERD](https://github.com/user-attachments/assets/ab337f49-69b5-4626-b188-a1c80c6efae6)

---

## Getting Started

### Requirements
- MySQL 5.7+ or compatible
- MySQL client or GUI tool (e.g., MySQL Workbench, phpMyAdmin)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/senuadev/Vehicle-Rental-DB-System.git
   cd Vehicle-Rental-DB-System
   ```
2. Import the SQL schema:
   ```sql
   SOURCE vehicle-rental-db.sql;
   ```

---

## Files

| File                        | Description                                       |
| --------------------------- | ------------------------------------------------- |
| `vehicle-rental-db.sql` | SQL script to create all tables and relationships |
| `README.md`                 | The documentation file                           |
