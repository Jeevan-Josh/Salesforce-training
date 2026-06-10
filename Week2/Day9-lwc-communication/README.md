# Day 9 - LWC Communication and Data Flow

## Component Communication

In Lightning Web Components, components often need to exchange information with each other. Communication allows different components to work together and create dynamic applications.

There are two common communication methods:

* Parent to Child Communication
* Child to Parent Communication

This helps create modular and reusable applications.

---

## Parent to Child Communication

A parent component can pass data to a child component using properties.

Example:

Faculty Dashboard passes faculty information to the Faculty Details Component.

Benefits:

* Easy data sharing
* Better component organization
* Reusable design

---

## Child to Parent Communication

A child component can send information back to its parent using custom events.

Example:

Attendance Component sends updated attendance information to Student Dashboard.

Benefits:

* Interactive applications
* Dynamic updates
* Better user experience

---

## Dashboard Design

### Student Dashboard

Components:

* Header
* Student Profile
* Attendance View
* Course List
* Notifications

### Faculty Dashboard

Components:

* Header
* Faculty Profile
* Course Management
* Student Attendance
* Notifications

### Admin Dashboard

Components:

* Header
* Student Management
* Faculty Management
* Department Management
* Reports and Analytics

---

## Data Flow Example

### Student Registration Process

1. Student fills registration form.
2. UI validates basic input.
3. Validation Rules check required fields.
4. Flow sends confirmation message.
5. Apex processes registration logic.
6. Database stores student information.
7. Notification is sent to student.

This creates a complete end-to-end workflow.

---

## Aura vs LWC

### Aura Components

* Older Salesforce UI framework
* More complex development
* Lower performance compared to LWC

### Lightning Web Components

* Modern framework
* Better performance
* Uses web standards
* Easier maintenance

Salesforce moved toward LWC because it provides a faster and more efficient development experience.

---

## Reflection

Enterprise applications require modular architecture because large systems contain many features. Modular components make development easier, improve maintainability, and allow teams to work independently on different parts of the application.

