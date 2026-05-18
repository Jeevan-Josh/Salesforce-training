# Day 5 – Apex Introduction

## What is Apex?

Apex is Salesforce's programming language used to implement custom business logic that cannot be handled using only clicks, flows, or configuration.

It allows developers to:

- write custom logic
- integrate external systems
- perform complex calculations
- automate advanced processes

---

# Why Apex Exists

Salesforce provides no-code tools such as:

- Flow
- Validation Rules
- Formula Fields

These are useful for common tasks.

However some business requirements become complex and need programming.

That is where Apex is used.

---

# Difference: Flow vs Apex

| Flow | Apex |
|---|---|
| No-code | Programming |
| Faster to build | More flexible |
| Good for simple logic | Good for complex logic |
| Visual development | Code development |

---

# Difference: Configuration vs Coding

Configuration:

Uses built-in Salesforce tools.

Examples:

- Validation Rules
- Flows
- Formula Fields

Coding:

Uses Apex for advanced logic.

Examples:

- Integrations
- Custom processing
- Complex business rules

---

# Real Examples Where Apex Is Needed

### Complex Fee Calculation

Different students may have scholarships, category discounts and additional charges.

Reason:
Flow becomes difficult to maintain.

---

### External Payment Gateway Integration

Connecting Salesforce with external payment systems.

Reason:
Requires API calls and programming.

---

### Advanced Eligibility Logic

Determine whether students qualify for placements based on multiple conditions.

Reason:
Complex conditions become easier in Apex.

---

# Integrated College Management System

## CRM

Student admission process pipeline.

---

## Objects

- Student
- Faculty
- Course
- Department

---

## Relationships

Student ↔ Course

Faculty → Course

Department → Faculty

---

## Validation

Email cannot be empty.

---

## Formula

Remaining Seats:

Total Seats − Filled Seats

---

## Flow

Automatically notify faculty when course becomes full.

---

## Apex

Custom placement eligibility logic.

---

# Pseudocode Examples

Example 1:

IF seats are full

THEN block registration

---

Example 2:

IF attendance < 75%

THEN notify student

---

Example 3:

IF fee not paid before deadline

THEN send reminder

---

# Reflection

Enterprise systems eventually need programming because not every business process can be handled using clicks and configurations.

Programming gives flexibility and allows developers to solve complex problems.