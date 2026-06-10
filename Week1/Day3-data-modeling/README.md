# Day 3 – Data Modeling

## Difference Between App, Object, Record and Field

### App
An App is a collection of tabs, objects and tools built for a specific purpose.

Example:
College Management App

---

### Object
Object is similar to a database table used to store data.

Example:
Student Object

---

### Record
A Record is a single entry inside an object.

Example:
Student Name: Rahul

---

### Field
Field stores specific information inside records.

Example:
Student Email

---

# Standard vs Custom Objects

Standard Objects:
Already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

Custom Objects:
Created by users according to business requirements.

Examples:
- Student
- Course
- Faculty

---

# College Management System Data Model

Objects:

- Student
- Faculty
- Course
- Department

Relationships:

Department → Faculty
(One Department has many Faculty)

Department → Course
(One Department has many Courses)

Faculty → Course
(One Faculty teaches many Courses)

Course → Student
(Many Students enroll in Courses)

---

## Simple Relationship Diagram

Department
     ↓
Faculty
     ↓
Course
     ↓
Student

---

# Formula Fields

### Percentage

Marks Obtained / Total Marks ×100

Reason:
Calculated automatically to avoid manual calculations.

---

### Remaining Seats

Total Seats - Filled Seats

Reason:
Shows live seat availability.

---

### Full Name

First Name + Last Name

Reason:
Avoids entering repeated data.

---

# Validation Rules

### Email cannot be empty

Reason:
Prevents incomplete records.

---

### Student age cannot be negative

Reason:
Blocks incorrect information.

---

### Course seats cannot exceed limit

Reason:
Prevents overbooking.

---

# Reflection

Companies cannot manage huge data using spreadsheets because data becomes difficult to organize and maintain.

Structured systems create relationships, avoid duplicate data and improve management efficiency.
