# Day 4 - Flow Builder

# What is Flow Builder?

Flow Builder is an automation tool in Salesforce.

It helps us automate tasks and business processes without writing code.

Using Flow Builder, we can:
- Create forms
- Update records automatically
- Send emails
- Automate repetitive work

As a beginner, I understood that Flow Builder helps reduce manual work and saves time.

---

# Types of Flows

There are different types of flows in Salesforce.

## 1. Screen Flow

Screen Flow is used when user interaction is needed.

It shows screens where users can enter data.

### Example

Student Admission Form:
- Student enters name
- Course details are filled
- Data gets stored automatically

### My Understanding

Screen Flow works like a form or application screen.

---

## 2. Record Triggered Flow

Record Triggered Flow runs automatically when a record is created, updated, or deleted.

No user interaction is needed.

### Example

When a new student record is created:
- Welcome email is automatically sent

### My Understanding

This flow works automatically in the background.

---

# My Automation Ideas

## 1. Student Admission Automation
When a student record is created:
- Send confirmation email automatically

---

## 2. Attendance Alert
If attendance is below 75%:
- Send warning notification to student

---

## 3. Fee Payment Reminder
Before due date:
- Automatically send payment reminder

---

## 4. Course Enrollment Automation
When student selects a course:
- Automatically assign faculty details

---

## 5. Library Due Date Alert
If book return date is near:
- Send reminder message automatically

---

# My Flow Diagram

## Simple Flow Diagram

```text
Start
  |
  v
Student Record Created
  |
  v
Check Student Details
  |
  v
Send Welcome Email
  |
  v
Update Status
  |
  v
End
```

---

# Manual vs Automated Process

| Manual Process | Automated Process |
|----------------|------------------|
| Human work is needed | System works automatically |
| Takes more time | Saves time |
| More chances of errors | Fewer errors |
| Repetitive work | Faster process |
| Difficult to manage large data | Easy to manage |

---

# Reflection

## Why Automation Matters in Enterprise Systems

Automation is important because large organizations handle huge amounts of data and repetitive tasks daily.

Benefits of automation:
- Saves time
- Reduces human errors
- Improves productivity
- Makes work faster
- Helps employees focus on important tasks

In Salesforce, Flow Builder helps companies automate business processes easily without coding.

As a beginner, I understood that automation is very useful in real-world enterprise systems because it makes work simple and efficient.

---
