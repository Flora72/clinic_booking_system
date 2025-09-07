# Clinic Booking System – Relational Database Design

This project implements a full-featured relational database for a clinic booking system using MySQL. It is designed to support trauma-informed care and survivor-centered workflows.

---

## Objectives

- Design a normalized schema with meaningful relationships
- Implement constraints to ensure data integrity
- Support appointment scheduling, patient records, and department management

---

## Tools Used

- MySQL Workbench
- SQL (DDL statements)
- GitHub for version control

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Flora72/clinic_booking_system.git
   cd clinic-db
   ```

2. Open `clinic_db.sql` in MySQL Workbench

3. Run the script to create the database and tables

---

## Relationships

- One-to-Many: Doctors → Appointments  
- One-to-Many: Patients → Appointments  
- One-to-One: Patients → MedicalRecords  
- Many-to-One: Doctors → Departments

---

## Screenshots

### 1. Database Schema Diagram  
`[Insert ERD screenshot here]`

### 2. MySQL Workbench Output  
`[Insert terminal or execution screenshot here]`

---

##  Reflections

This schema was designed with emotional clarity and survivor safety in mind. Each table reflects a real-world relationship, and constraints ensure the integrity of sensitive data. The structure is scalable for future modules like prescriptions, billing, or trauma notes.

---

## Final Checklist

- [x] `.sql` file includes CREATE DATABASE and all table definitions  
- [x] Relationships and constraints are clearly defined  
- [x] README includes setup, objectives, and screenshots  
- [x] GitHub repo is public and ready for submission



