# Student Admission Management System | Salesforce

## Overview
This project implements a Student Admission Management System on the Salesforce platform to automate and manage the end-to-end admission workflow using Salesforce CRM capabilities.

The system focuses on structured data modeling and declarative automation using Salesforce Flows, with minimal Apex usage.

---

## Problem Statement
Manual student admission processes are time-consuming, error-prone, and difficult to track. This project aims to digitize and automate the admission lifecycle, ensuring consistent status management and centralized data handling.

---

## Key Features
- Custom Salesforce objects for Student, Application, and Course
- Lookup relationships to model real-world admission data
- Automated application status initialization using record-triggered Flows
- Conditional status transitions based on document submission
- Designed for scalability and future enhancements

---

## Data Model
- **Student**: Stores student personal and academic details
- **Application**: Tracks admission applications and their lifecycle
- **Course**: Maintains course information

Relationships:
- One Student can have multiple Applications
- Each Application is associated with one Course

---

## Automation Logic
- **Before-save Flow**: Automatically sets Application status to *Submitted* when a new application is created
- **After-save Flow**: Moves Application status to *Under Review* when documents are submitted

---

## Technology Stack
- Salesforce CRM
- Salesforce Flows (Record-Triggered Flows)
- Apex (SOQL)
- Custom Objects & Relationships

---

## Project Status
This project is currently under active development.

Planned enhancements include:
- Approval Process for application acceptance/rejection
- Course seat capacity management
- Reports and dashboards for admission analytics

---

## Author
**Yamini Sharma**  
B.E. Final Year Student  
Salesforce Developer Intern Aspirant

This project is currently under active development.
Upcoming enhancements include approval processes, seat allocation automation, and reporting dashboards.

## Author
Yamini Sharma
