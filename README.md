# Oracle Parking Spot Management System

## 📌 Project Overview
The **Oracle Parking Spot Management System** is a comprehensive database application designed to efficiently manage parking operations.  
It tracks employees, managers, parking spots, spaces, customers, and fines, providing a structured and secure system for day-to-day parking management.

---

## 🛠 Features
- **Employee & Manager Management**:  
  - Multiple employees supervised by managers.  
  - Unique IDs for employees and managers.  
  - Stores personal information: first and last names, hire date, phone numbers, and salary.  

- **Parking Spot Management**:  
  - Each parking spot is identified by a **Spot ID** and has a physical address.  
  - Managed by assigned managers.  

- **Parking Spaces**:  
  - Each spot contains several spaces with unique **Space IDs** and types.  
  - Space type determines the **cost rate** (hourly or daily).  
  - Each space type has a unique **Rate ID**.  

- **Customer & Parking Slip Management**:  
  - Customers assigned a **parking slip** upon hiring a space.  
  - Slip includes **Slip ID, issue date, expire date, and type**.  
  - Customer information stored with unique ID, names, email, phone numbers, license plate numbers, and address.  

- **Rules & Fines**:  
  - Managers can enforce rules and issue fines for violations.  
  - Fines include **ID, issue date, amount, and paid date**.  

---

## 🗄 Database Design
- **Tables**: Employees, Managers, ParkingSpots, ParkingSpaces, SpaceTypes, Rates, Customers, ParkingSlips, Fines  
- **Relationships**:
  - One manager supervises multiple employees.  
  - Each parking spot contains multiple spaces.  
  - Customers can hire multiple spaces over time.  
  - Fines are linked to customers and managed by managers.  

---

## 💻 Technologies Used
- **Database:** Oracle Database 19c/21c  
- **Languages:** SQL & PL/SQL  
- **Tools:** Oracle SQL Developer, Oracle APEX (optional)  

---

## 📄 Project Documentation
The full project report is available [here](./docs/Project_Report.pdf).  

---

## 📂 Folder Structure
