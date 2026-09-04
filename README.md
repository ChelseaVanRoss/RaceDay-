# RaceDay – Event Management System

This is my Part 1 submission for the RaceDay project.  
RaceDay is a web-based system for managing road running, walking, and cycling events in South Africa.

---

## What I Did for Part 1

For this part, I planned the system before writing any code.  
I created:

- An **ERD** (Entity Relationship Diagram)  
- A **SQL script** to create the database  
- An **API endpoint plan**  

All of this is saved in this repository.

---

## The Two User Roles

The system has two roles:

**Organiser**  
- Can create, edit, and delete events  
- Can add categories to events  
- Can capture results for participants  

**Participant**  
- Can browse events  
- Can enter events by choosing a category  
- Can view their own enrolments and results  

---

## My Files

| File | What it is |
|------|------------|
| `RaceDay_Database.sql` | SQL script that creates the RaceDay database and adds sample data |
| `ERD.drawio.png` | My ERD showing the 6 tables and how they relate |
| `RaceDay API Endpoint Plan.txt` | A table showing all the API routes I plan to build in Part 2 |


## CI/CD Status

I set up a GitHub Actions workflow to check that my files are in the right place.

![CI Status](https://github.com/ChelseaVanRoss/RaceDay-/actions/workflows/ci.yml/badge.svg)


## How to Run My SQL Script

1. Open SQL Server Management Studio  
2. Connect to your SQL Server  
3. Open the `RaceDay_Database.sql` file  
4. Run the script  

This creates the RaceDay database and adds sample data.


## GitHub Repository

[https://github.com/ChelseaVanRoss/RaceDay-](https://github.com/ChelseaVanRoss/RaceDay-)


## Author

Chelsea Van Ross
