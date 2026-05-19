# Day 6 – SOQL and Apex Triggers

## What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects. It is similar to SQL but designed specifically for Salesforce.

Example:
Find all students enrolled in Course A.

---

# What is an Apex Trigger?

Apex Trigger is code that runs automatically when certain events happen in Salesforce.

Examples:
- before insert
- after update
- after delete

Triggers help systems react automatically to data changes.

---

# Flow vs Trigger

Flow:
- no-code
- simple automation
- easy to maintain

Trigger:
- code-based
- handles complex logic
- more flexibility

---

# Before vs After Trigger

Before Trigger:
Runs before saving records.

Example:
Validate student age.

After Trigger:
Runs after records are saved.

Example:
Send notification after registration.

---

# Trigger Use Cases

1. After student registration → send welcome email

Trigger:
Student record created

---

2. After attendance drops below 75%

Trigger:
Attendance updated

---

3. After course becomes full

Trigger:
Seat count reaches maximum

---

4. After fee payment completed

Trigger:
Fee record updated

---

5. After student placed

Trigger:
Placement status changed

---

# Query Examples

Find all students in Course A

Find all courses handled by Faculty X

Find students with attendance below 75%

Find all students from Department CSE

Find students whose fee is pending

---

# Reflection

Enterprise systems need event-driven behavior because actions should happen automatically when data changes.

Automation saves time and improves user experience. 