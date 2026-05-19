# Day 4 – Flow Builder & Automation

## What is Flow Builder?

Flow Builder is a no-code automation tool in Salesforce used to automate business processes. It helps companies reduce manual work and improve efficiency.

Using Flow Builder we can:
- create workflows
- update records automatically
- send notifications
- create decisions and conditions
- automate business logic

---

# Why Businesses Need Automation

Companies perform many repetitive tasks daily.

Examples:
- sending emails
- updating records
- assigning tasks
- notifications

Doing these manually takes time and can create mistakes.

Automation:
- saves time
- reduces errors
- increases productivity
- keeps processes consistent

---

# Types of Flows

## Screen Flow

Screen Flow interacts with users.

Examples:
- student registration form
- feedback form
- application form

Users provide input through screens.

---

## Record Triggered Flow

Runs automatically whenever a record is created or updated.

Examples:
- send email after registration
- update course seats automatically
- notify faculty

No user interaction needed.

---

# Automation Ideas for College Management System

### 1. Generate Student ID Automatically

Why:
Avoid manual creation and duplicate IDs.

---

### 2. Send Welcome Email After Registration

Why:
Instant communication with students.

---

### 3. Notify Faculty When Course Is Full

Why:
Faculty immediately knows seat status.

---

### 4. Auto Update Remaining Seats

Why:
Prevents manual calculations.

---

### 5. Fee Payment Reminder

Why:
Students receive reminders before deadlines.

---

# Flow Design Example

Automation Selected:

Send Welcome Email after Student Registration

Trigger:

Student record created

↓

Check:
Is email available?

↓

Decision:

Yes / No

↓

If Yes:

Send email

↓

Update student status

↓

End

---

# Manual vs Automated Process

Example:
Student Registration

Manual Process:

- Student submits form
- Admin checks details
- Admin sends confirmation manually
- Admin creates ID manually

Problems:

- Time consuming
- Human errors
- Delay

Automated Process:

Salesforce Flow automatically:

- checks records
- generates ID
- sends email
- updates database

Benefits:

- faster
- accurate
- less manual work

---

# Reflection

Companies should automate repetitive processes because manual work takes time and causes mistakes.

Automation improves productivity, consistency and efficiency.

---

# Reflective Answers

1. Companies automate workflows to save time and reduce manual effort.

2. Manual processes create delays and human errors.

3. Screen Flow interacts with users while Record Triggered Flow runs automatically.

4. No-code automation allows faster development.

5. Automation should be avoided when processes frequently change.

6. Automation improves consistency and productivity by reducing errors. 