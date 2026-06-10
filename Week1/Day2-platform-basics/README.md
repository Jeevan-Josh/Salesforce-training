# Day 2 - Salesforce Platform Basics

## What is Salesforce Platform?

Salesforce Platform is a cloud-based platform used to build CRM applications and business solutions.

It provides:
- database management,
- automation,
- security,
- APIs,
- UI tools,
- development tools.

Developers and admins use Salesforce Platform to create and customize applications for businesses.

---

# Salesforce Platform Structure

Salesforce Platform is made of:
- Apps
- Objects
- Tabs
- Records
- Fields
- Automation tools
- Development tools

---

# What is an App in Salesforce?

An App in Salesforce is a collection of tools, objects, tabs, and features designed for a specific business purpose.

Example:
- Sales App
- Service App
- College Management App

Apps help users work in one organized environment.

---

# What is an Object?

An Object is like a database table used to store information.

Objects contain:
- fields,
- records,
- relationships.

Examples:
- Account
- Contact
- Opportunity
- Student
- Course

---

# What is a Tab?

A Tab is the user interface used to access objects and records.

Tabs help users:
- open objects,
- view records,
- navigate applications.

Example:
- Accounts Tab
- Students Tab
- Courses Tab

---

# CRM Concepts inside Salesforce Platform

CRM concepts like:
- Account,
- Contact,
- Opportunity

are implemented as Salesforce Objects.

These objects are placed inside Apps and accessed using Tabs.

Example:
Sales App
│
├── Accounts Tab
├── Contacts Tab
└── Opportunities Tab

---

# Configuration vs Coding

## Configuration (No Code)

Configuration means customizing Salesforce using built-in tools without programming.

Examples:
1. Creating fields using UI
2. Building workflows using Flow Builder

Advantages:
- Fast
- Easy
- No programming required

---

## Coding (Apex)

Coding is used when advanced logic or customization is needed.

Salesforce uses Apex programming language.

Examples:
1. Custom business logic
2. API integrations

Advantages:
- Powerful
- Flexible
- Advanced automation

---

# Difference Between Configuration and Coding

| Configuration | Coding |
|---|---|
| No programming | Requires programming |
| Faster setup | More flexible |
| Uses built-in tools | Uses Apex and APIs |
| Good for simple tasks | Good for complex tasks |

---

# What is Multi-Tenant Architecture?

Salesforce uses multi-tenant architecture.

This means:
- multiple companies share the same infrastructure,
- but their data remains secure and separated.

It helps Salesforce:
- reduce costs,
- improve scalability,
- provide cloud services efficiently.

---

# How Developers Extend Salesforce

Developers extend Salesforce by:
- creating custom objects,
- writing Apex code,
- building Lightning components,
- integrating APIs,
- automating workflows.

---

# System Design Example (College Management System)

## App Name
College Management App

---

## Objects Inside App

- Student
- Faculty
- Course
- Attendance
- Fees
- Placement

---

## User Interaction

### Admin
- manages students and courses

### Faculty
- updates attendance and marks

### Students
- view courses and attendance

---

# Trailhead Modules Completed

- Agentforce 360 Platform Basics
- Agentforce 360 Platform Development Basics

---

# What I Learned Today

- Salesforce platform structure
- Apps, Objects, and Tabs
- Difference between configuration and coding
- Multi-tenant architecture
- How developers extend Salesforce

---

# Doubts / Questions

- How does Salesforce internally manage millions of users?
- How are APIs integrated with Salesforce?

---


