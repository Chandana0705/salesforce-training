# Day 8 - LWC Basics

# What is LWC?

LWC stands for Lightning Web Components.

It is a modern UI framework used in Salesforce to build fast and reusable user interfaces.

LWC is based on web technologies such as:
- HTML
- CSS
- JavaScript

Using LWC, developers can create attractive and interactive Salesforce applications.

### My Understanding

As a beginner, I understood that LWC helps us build the frontend (screens) that users interact with in Salesforce.

---

# Why Salesforce Uses LWC

Salesforce uses LWC because it:

- Improves performance
- Creates modern user interfaces
- Uses standard web technologies
- Supports reusable components
- Provides better user experience

### My Understanding

Instead of creating everything from scratch, developers can build reusable components and use them in multiple places.

---

# My UI Screens

For my College Management System, I would create the following screens:

## 1. Student Registration Screen

- Student Name
- Phone Number
- Email
- Course Selection

---

## 2. Student Dashboard

- Student Details
- Attendance Percentage
- Fee Status

---

## 3. Course Management Screen

- Course Name
- Course Duration
- Faculty Assigned

---

## 4. Fee Management Screen

- Fee Amount
- Payment Status
- Due Date

---

# Component Breakdown

## Student Registration Component

Purpose:
- Collect student information

---

## Student Dashboard Component

Purpose:
- Display student details and attendance

---

## Course Component

Purpose:
- Display course information

---

## Fee Component

Purpose:
- Show fee details and payment status

---

### Simple Component Structure

```text
College Management App
        |
        +-- Student Registration Component
        |
        +-- Student Dashboard Component
        |
        +-- Course Component
        |
        +-- Fee Component
```

---

# Frontend vs Backend Logic

| Frontend | Backend |
|-----------|----------|
| User interface | Business logic |
| Built using LWC | Built using Apex |
| Displays information | Processes information |
| Handles user interaction | Handles database operations |

### Example

Frontend:
- Student enters admission details in form.

Backend:
- Salesforce saves data and performs validations.

---

# Reflection

LWC made me understand how Salesforce applications display information to users. Earlier I learned about objects, flows, validation rules, SOQL, and Apex, which mainly work in the backend. Today I learned that LWC is responsible for creating the user interface that users see and interact with. As a beginner, I understood that enterprise applications need both frontend and backend components to work together and provide a complete solution.

---
