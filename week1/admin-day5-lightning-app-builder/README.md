# Admin Day 5 - Lightning App Builder

# What is Lightning Experience?

Lightning Experience is the modern user interface of Salesforce.

It provides:

- Better design
- Faster navigation
- Improved productivity
- Customizable pages
- Modern user experience

### My Understanding

As a beginner, I understood that Lightning Experience is the interface users interact with while using Salesforce.

---

# What is Lightning App Builder?

Lightning App Builder is a drag-and-drop tool used to create and customize pages in Salesforce without coding.

Using Lightning App Builder, we can create:

- App Pages
- Home Pages
- Record Pages

### Benefits

- Easy to use
- No coding required
- Customizable layouts
- Reusable components

### My Understanding

Lightning App Builder helps administrators create user-friendly pages for different users.

---

# Student Record Page Design

The Student Record Page should display important student information.

### Components

- Student Details
- Contact Information
- Course Details
- Attendance Information
- Fee Status

### Layout

```text
+---------------------------+
| Student Information       |
+---------------------------+

Name
Email
Phone Number

+---------------------------+
| Course Information        |
+---------------------------+

Course Name
Faculty Name

+---------------------------+
| Attendance & Fees         |
+---------------------------+

Attendance %
Fee Status
```

---

# Faculty Dashboard Design

The Faculty Dashboard should help faculty manage their daily work.

### Components

- Assigned Courses
- Student Count
- Attendance Summary
- Upcoming Classes

### Layout

```text
+---------------------------+
| Faculty Dashboard         |
+---------------------------+

Assigned Courses

Student Count

Attendance Summary

Upcoming Classes
```

---

# Placement Dashboard Design

The Placement Dashboard helps track placement activities.

### Components

- Eligible Students
- Placed Students
- Companies Visiting
- Placement Percentage

### Layout

```text
+---------------------------+
| Placement Dashboard       |
+---------------------------+

Eligible Students

Placed Students

Companies Visiting

Placement Percentage
```

---

# Placement Tracker App Design

The Placement Tracker App helps manage placement activities.

### Features

- Student Placement Records
- Company Information
- Interview Status
- Placement Results

### Objects Used

- Student
- Company
- Placement
- Interview

### Workflow

```text
Student Eligible
       |
       v
Company Registration
       |
       v
Interview Scheduled
       |
       v
Interview Result
       |
       v
Placement Status Updated
```

### My Understanding

This app helps track the complete placement process from eligibility to final placement.

---

# Reflection

Today I learned about Lightning Experience and Lightning App Builder. I understood how Salesforce pages can be customized for different users without writing code. I also learned how dashboards and applications can be designed for students, faculty, and placement teams. As a beginner, I realized that user interface design is important because it helps users access the information they need quickly and efficiently.

---

# Why Should Different Users Have Different User Interfaces?

Different users perform different tasks in a system. Students need access to their records, faculty need attendance and course information, and administrators need reports and management tools. Providing the same interface to everyone can make the system confusing and less efficient. Different user interfaces help users focus on the information and actions relevant to their responsibilities. As a beginner, I understood that customized interfaces improve productivity and user experience.

---
