# Day 14 Notes

## What is Flow Logic?

Flow Logic allows Salesforce to automate business processes using:

- Decisions
- Variables
- Loops
- Conditions
- Branching paths

A single flow can perform different actions based on data values.

Example:

IF Attendance < 75%
→ Send Warning

IF Attendance < 60%
→ Notify Parent

IF Attendance < 50%
→ Escalate To Admin

---

## What are Approval Processes?

Approval Processes allow records to be reviewed and approved before changes become final.

Benefits:

- Prevent unauthorized actions
- Maintain governance
- Improve accountability
- Create audit trails

---

## Multi-Level Approval Example

Scholarship Request

Student
↓
Scholarship Committee
↓
Finance Department
↓
Approved

Each level validates the request before moving forward.

---

## Governance

Governance means controlling who can perform important business actions.

Examples:

- Creating courses
- Approving budgets
- Processing scholarships
- Granting permissions

Without governance:

- Data errors increase
- Security risks increase
- Compliance issues occur

---

## Key Learning

Enterprise systems require structured workflows, approval chains, and governance controls to ensure security, reliability, and accountability.