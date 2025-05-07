
# Travel & Tourism Management System

A full-stack Python application with a robust SQL backend to manage travel packages, customer bookings, and itinerary generation.

---

## 🔍 Project Overview

This project simulates a travel-and-tourism platform by providing:

- *Relational Database*: Designed a normalized SQL schema for customers, destinations, packages, and bookings.  
- *Data Automation*: Parameterized SQL scripts to bulk-load 500+ sample records in seconds.  
- *Python Front End*: Interactive CLI/GUI that connects to the database, retrieves 20+ packages dynamically, processes 50+ bookings per session, and generates personalized itineraries.

---

## 🚀 Key Features

- *Database Provisioning*  
  - Automated creation of all tables and constraints via SQL scripts  
  - Bulk ingestion of 500+ records, reducing setup time by 80%  
- *Dynamic Package Retrieval*  
  - List, filter, and sort 20+ travel packages on demand  
  - Detailed package views with pricing and availability  
- *Real-Time Booking Management*  
  - Create, update, and cancel 50+ bookings per session  
  - Ensures referential integrity and prevents overbooking  
- *Itinerary Generation*  
  - Auto-generate day-by-day plans based on user selections  

---

## 📦 Installation

1. Set up the database

psql -U <DB_USER> -d <DB_NAME> -f sql/schema.sql
psql -U <DB_USER> -d <DB_NAME> -f sql/data_load.sql

2. Install Python dependencies

pip install -r requirements.txt

3. Configure connection

Edit config.py with your database credentials.

4. Run the application

python app.py



---

🛠️ Technologies Used

Database: MySQL

Backend: Python 

Libraries:

mysql-connector-python (DB connector)
