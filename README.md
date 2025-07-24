# 🏝️ Tourism Agency Database System

This project is a comprehensive **database system for a tourism agency**, developed as part of the Pure_CS_AMMA course. The system manages key entities such as employees, customers, tours, transportation, and site visits — aiming to improve service quality, operational efficiency, and decision-making in the tourism industry.

## 👥 Team Members

- Mohamed Tamer Morsi  
- Mariam Ayman Ismail  
- Ahmed Mohamed Elsayed  
- Abdalla Ahmed Wahba

## 📌 Problem Statement

> “In the tourism industry, service quality is a very important element that can determine the success of the organizations in this industry.”

This database project is designed to:
- Help hospitality businesses achieve goals
- Improve customer service
- Enhance operational efficiency
- Support better decision-making

---

## 📋 Features & Requirements

### Tracked Data Includes:
- **Employees**: SSN, name, birth date, gender, phone, salary, address, department, job title
- **Roles**: Tour guides (languages, nationality), admins (rank), drivers (license), reservation executives (monthly target)
- **Departments**: Name, unique number, manager info
- **Dependents**: Name, gender, relationship to employee
- **Customers**: Name, ID, phone, tours, payment method, reservation date, credit card info
- **Tours**: Unique code, type (abroad/local), price, schedule, admin, guide, transport, hotel
- **Events & Sites**: Associated with each tour
- **Transportation**: Bus details, driver
- **Hotels & Airports**: Based on tour type

---

## 🧠 Conceptual & Logical Design

- **Conceptual Model**: EER Diagram
- **Relational Model**: Fully normalized schema
- **Implementation Tool**: MySQL Workbench

---

## 🗃️ Project Structure

tourism-agency-db/
├── schema/ # SQL scripts (CREATE TABLE, constraints)
├── data/ # INSERT statements with sample data
├── queries/ # Useful SELECT queries from the project
├── diagrams/ # EER & relational diagrams (optional)
└── README.md


---

## 🛠️ Setup Instructions

1. Open MySQL Workbench
2. Create and Use the Database
  CREATE DATABASE TOURISM_COMPANY;
  USE TOURISM_COMPANY;
3. Run Schema and Data Scripts
   -- Run schema
SOURCE schema/create_tables.sql;

-- Insert sample data
SOURCE data/insert_data.sql;

## 📊 Technologies Used
Database: MySQL

Modeling Tool: MySQL Workbench

Language: SQL
