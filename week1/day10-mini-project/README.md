# Day 10 - Mini Project

# College Management System

## System Overview

The College Management System is a Salesforce-based application used to manage student information, courses, faculty details, attendance, and fee records.

The main goal of this system is to organize college data and automate important processes using Salesforce features such as CRM, Objects, Validation Rules, Flows, Apex, and Lightning Web Components (LWC).

As a beginner, I understood that Salesforce helps manage all college-related information in a structured and efficient way.

---

# CRM Concepts

## Account
College Department

Example:
- Computer Science Department

## Contact
Student

Example:
- Chandana Sai Sree

## Lead
Student interested in admission

Example:
- Student submits admission inquiry form

## Opportunity
Potential admission process

Example:
- Student application under review

---

# Data Model

## Objects Used

### Student
Stores student information.

### Course
Stores course details.

### Faculty
Stores faculty information.

### Attendance
Stores attendance records.

### Fees
Stores fee payment details.

---

## Relationships

```text
Student --> Course

Faculty --> Course

Student --> Attendance

Student --> Fees
```

---

# Validation Rules

## Rule 1

Phone number must contain exactly 10 digits.

### Error Message

```text
Please enter a valid 10-digit phone number.
```

---

## Rule 2

Student age should not be less than 16.

### Error Message

```text
Student age must be greater than or equal to 16.
```

---

# Flows

## Flow 1 - Welcome Email

When a new student record is created:
- Send welcome email automatically.

---

## Flow 2 - Attendance Alert

If attendance falls below 75%:
- Send notification to student.

---

## Flow 3 - Fee Reminder

Before fee due date:
- Send payment reminder automatically.

---

# Apex Logic

## Scholarship Calculation

```text
IF marks > 90
THEN scholarship = Eligible
ELSE scholarship = Not Eligible
```

---

## Course Capacity Check

```text
IF course seats are full
THEN prevent new enrollment
```

---

## External Payment Integration

Apex can be used to connect Salesforce with external payment systems for fee collection.

---

# UI Screens

## Student Registration Screen

- Student Name
- Email
- Phone Number
- Course Selection

---

## Student Dashboard

- Student Details
- Attendance Percentage
- Fee Status

---

## Course Management Screen

- Course Information
- Faculty Details

---

## Fee Management Screen

- Payment Status
- Due Date
- Fee Amount

---

# Complete Data Flow

```text
Student Applies
       |
       v
Lead Created
       |
       v
Lead Converted to Contact
       |
       v
Student Record Created
       |
       v
Validation Rules Check Data
       |
       v
Flow Sends Welcome Email
       |
       v
Course Assigned
       |
       v
Attendance and Fees Managed
       |
       v
Apex Executes Advanced Logic
       |
       v
Information Displayed in LWC Screens
```

---

# Reflection

Over the past 10 days, I learned the basic concepts of Salesforce including CRM, Objects, Relationships, Validation Rules, Flows, Apex, SOQL, Triggers, Salesforce DX, and Lightning Web Components. Through this mini project, I understood how all these concepts work together to build a complete enterprise application. As a beginner, I found that Salesforce provides both no-code and coding solutions to manage business processes efficiently. This project helped me understand the overall workflow of a real-world College Management System.

---
