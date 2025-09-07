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
<img width="1440" height="884" alt="Screen Shot 2025-09-07 at 23 25 11" src="https://github.com/user-attachments/assets/4a157bdd-a4c6-4201-a864-953aa7870f0f" />


### 2. MySQL Workbench Output  
### 1.1 
<img width="1440" height="857" alt="Screen Shot 2025-09-07 at 23 15 16" src="https://github.com/user-attachments/assets/94580403-32f5-4966-a010-fb48fde73801" />

### 1.2 
<img width="1330" height="798" alt="Screen Shot 2025-09-07 at 23 15 39" src="https://github.com/user-attachments/assets/979cb596-ce73-46f6-88c5-6958449d6fe7" />

### 1.3 
<img width="1440" height="857" alt="Screen Shot 2025-09-07 at 23 15 46" src="https://github.com/user-attachments/assets/2fd4e676-c91c-40c9-9f58-70c10cb5d763" />

### 1.4 
<img width="1440" height="857" alt="Screen Shot 2025-09-07 at 23 15 50" src="https://github.com/user-attachments/assets/3f7b8e56-ffdd-4bc6-be9f-fb03598182ab" />



---

##  Reflections

This schema was designed with emotional clarity and survivor safety in mind. Each table reflects a real-world relationship, and constraints ensure the integrity of sensitive data. The structure is scalable for future modules like prescriptions, billing, or trauma notes.

---

## Final Checklist

- [x] `.sql` file includes CREATE DATABASE and all table definitions  
- [x] Relationships and constraints are clearly defined  
- [x] README includes setup, objectives, and screenshots  
- [x] GitHub repo is public and ready for submission



