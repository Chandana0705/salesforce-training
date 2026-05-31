# Day 9 - LWC Communication

# Component Communication

Component Communication is the process of sharing data between Lightning Web Components (LWC).

Sometimes one component needs information from another component. Salesforce provides ways for components to communicate with each other.

### Example

In a College Management System:

- Student Registration Component collects student details.
- Student Dashboard Component displays those details.

The data entered in one component can be passed to another component.

### My Understanding

As a beginner, I understood that component communication helps different parts of an application work together and share information.

---

# Dashboard Design

## College Management Dashboard

The dashboard can contain:

### Student Information
- Student Name
- Roll Number
- Course

### Attendance Details
- Attendance Percentage
- Attendance Status

### Fee Details
- Fee Amount
- Payment Status

### Course Information
- Course Name
- Faculty Name

---

## Simple Dashboard Layout

```text
+----------------------------------+
| College Management Dashboard     |
+----------------------------------+

+------------+   +--------------+
| Student    |   | Attendance   |
| Details    |   | Details      |
+------------+   +--------------+

+------------+   +--------------+
| Fee        |   | Course       |
| Details    |   | Details      |
+------------+   +--------------+
```

---

# Data Flow Explanation

In my College Management System, data flows from the user interface to Salesforce and back to the user.

### Flow of Data

```text
User
  |
  v
LWC Component
  |
  v
Apex Controller
  |
  v
Salesforce Database
  |
  v
LWC Component
  |
  v
User
```

### Example

1. Student enters admission details.
2. LWC sends data to Apex.
3. Apex saves data into Salesforce.
4. Data is retrieved from Salesforce.
5. LWC displays the updated information.

---

# Aura vs LWC

| Aura | LWC |
|--------|--------|
| Older framework | Modern framework |
| More complex | Easier to learn |
| Uses Aura components | Uses web standards |
| Slower performance | Better performance |
| More code required | Less code required |

### My Understanding

Aura was used earlier for building Salesforce applications. LWC is the newer technology and provides better performance, simpler development, and improved user experience.

---

# Reflection

Today I learned how Lightning Web Components communicate with each other and how data moves between the user interface and Salesforce database. I also understood the difference between Aura and LWC. As a beginner, I found LWC easier to understand because it uses familiar web technologies like HTML, CSS, and JavaScript. Learning component communication helped me understand how different parts of an enterprise application work together.

---
