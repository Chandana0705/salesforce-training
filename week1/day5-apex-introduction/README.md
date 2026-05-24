# Day 5 - Apex Introduction

# 1. What is Apex?

Apex is a programming language in Salesforce.

It is used to add custom logic and advanced automation inside Salesforce.

Apex is similar to Java language.

Using Apex, developers can:
- Write custom business logic
- Automate complex processes
- Create triggers
- Connect external systems

As a beginner, I understood that Apex is used when normal Salesforce tools are not enough.

---

# 2. Difference Between

## Flow vs Apex

| Flow | Apex |
|------|------|
| No coding needed | Coding is needed |
| Easy for beginners | Used by developers |
| Drag-and-drop automation | Written using code |
| Best for simple automation | Best for complex logic |
| Faster to build | More flexible |

### My Understanding

- Flow is easier and mostly configuration based.
- Apex is used for advanced requirements.

---

## Configuration vs Coding

| Configuration | Coding |
|---------------|--------|
| Uses clicks and settings | Uses programming language |
| Easy to maintain | More powerful |
| No technical knowledge needed | Requires coding skills |
| Faster for small tasks | Better for complex systems |

### Example

- Configuration → Create Flow
- Coding → Write Apex Trigger

---

# 3. Real Examples Where Apex Is Needed

## 1. Automatic Scholarship Calculation

If student marks are above certain percentage:
- System calculates scholarship amount automatically.

This may need complex logic, so Apex is useful.

---

## 2. Integration with External Payment System

When fees are paid:
- Salesforce connects with payment gateway.

External integrations usually require Apex.

---

## 3. Bulk Student Data Processing

If thousands of student records are uploaded:
- Apex can process data efficiently.

---

# 4. Integrated College Management System Design

## CRM in My System

CRM helps manage:
- Student information
- Faculty details
- Courses
- Attendance
- Fee management

---

# Objects Used

| Object | Purpose |
|--------|---------|
| Student | Stores student details |
| Course | Stores course information |
| Faculty | Stores faculty details |
| Attendance | Stores attendance records |
| Fees | Stores fee payment details |

---

# Relationships

| Parent Object | Relationship | Child Object |
|---------------|-------------|--------------|
| Student | Enrolled In | Course |
| Faculty | Teaches | Course |
| Student | Has | Attendance |
| Student | Pays | Fees |

---

# Validation Examples

## Example 1

Phone number must contain 10 digits.

---

## Example 2

Student age should not be less than 16.

---

# Flow Examples

## Example 1

When student record is created:
- Welcome email is automatically sent.

---

## Example 2

If attendance is below 75%:
- Warning notification is sent.

---

# Apex Examples

## Example 1

Calculate scholarship amount based on marks.

---

## Example 2

Connect fee payment system with Salesforce.

---

# Simple System Diagram

```text
+-----------+
| Student   |
+-----------+
      |
      v
+-----------+
| Course    |
+-----------+
      |
      v
+-----------+
| Faculty   |
+-----------+

Student
   |
   v
+-------------+
| Attendance  |
+-------------+

Student
   |
   v
+--------+
| Fees   |
+--------+
```

---

# 5. Pseudocode Examples

## Example 1: Attendance Alert

```text
IF attendance < 75%
THEN send warning message
```

---

## Example 2: Scholarship Logic

```text
IF marks > 90
THEN scholarship = 5000
ELSE scholarship = 0
```

---

## Example 3: Fee Reminder

```text
IF due date is near
THEN send reminder email
```

---

# 6. Reflection

## Why Enterprise Systems Eventually Need Programming

Large enterprise systems become more complex over time.

Simple configuration tools are useful in the beginning, but advanced business requirements need programming.

Programming helps to:
- Handle complex logic
- Integrate external systems
- Process large amounts of data
- Build customized features

In Salesforce, Apex helps organizations create advanced enterprise solutions.

As a beginner, I understood that both configuration and coding are important in real-world systems.

Configuration makes work easier, while programming gives more flexibility and control.

---
