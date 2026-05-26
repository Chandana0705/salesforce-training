# Day 6 - Triggers and SOQL

# 1. What is SOQL?

SOQL stands for Salesforce Object Query Language.

It is used to get data from Salesforce objects.

SOQL is similar to SQL, but it is specially designed for Salesforce.

Using SOQL, we can:
- Read records
- Search data
- Filter information
- Retrieve required fields

### Example Understanding

If we want to see all student names from Student object:
- SOQL helps us fetch that data.

As a beginner, I understood that SOQL is mainly used to read and search data from Salesforce.

---

# 2. What is an Apex Trigger?

An Apex Trigger is a piece of code that runs automatically when data changes in Salesforce.

Triggers work when:
- Record is created
- Record is updated
- Record is deleted

Triggers help automate backend processes.

### Example

When a student record is created:
- Trigger automatically sends welcome email.

As a beginner, I understood that triggers react automatically whenever data changes.

---

# 3. Difference Between

## Flow vs Trigger

| Flow | Trigger |
|------|---------|
| Mostly no-code | Requires coding |
| Easy to create | More technical |
| Drag-and-drop interface | Written in Apex |
| Used for simple automation | Used for complex logic |
| Beginner friendly | Developer oriented |

### My Understanding

- Flow is easier for simple tasks.
- Trigger is powerful for advanced automation.

---

## Before Trigger vs After Trigger

| Before Trigger | After Trigger |
|----------------|---------------|
| Runs before saving record | Runs after saving record |
| Used to update field values | Used for actions after save |
| Faster for validations | Used for emails and related records |

---

### Example

## Before Trigger
Automatically set student status before saving record.

## After Trigger
Send confirmation email after record is saved.

---

# 4. My Trigger Use Cases

## 1. Welcome Email Trigger

When a new student is added:
- Automatically send welcome email.

---

## 2. Attendance Warning Trigger

If attendance becomes less than 75%:
- Send warning notification.

---

## 3. Fee Pending Alert Trigger

If fee payment is not completed:
- Notify student automatically.

---

## 4. Scholarship Trigger

If marks are above 90%:
- Automatically assign scholarship status.

---

## 5. Course Capacity Trigger

If course seats are full:
- Prevent adding new students.

---

# 5. Query Examples

## Example 1

Get all student names.

```text
Show all students from Student object
```

---

## Example 2

Find students with attendance below 75%.

```text
Show students whose attendance is less than 75%
```

---

## Example 3

Find students who did not pay fees.

```text
Show students with pending fee status
```

---

## Example 4

Get all courses taught by a faculty member.

```text
Show courses assigned to one faculty
```

---

## Example 5

Find students eligible for scholarship.

```text
Show students whose marks are above 90%
```

---

# Simple Trigger Flow Diagram

```text
Student Record Created
        |
        v
Trigger Executes
        |
        v
Check Conditions
        |
        v
Perform Action
(Send Email / Update Status)
```

---

# 6. Reflection

## Why Enterprise Systems React Automatically to Data Changes

Enterprise systems handle large amounts of data every day.

Doing everything manually is difficult and time consuming.

Automatic reactions help systems:
- Save time
- Reduce human errors
- Improve efficiency
- Maintain accurate data
- Perform quick actions

In Salesforce, triggers and flows help systems respond automatically whenever data changes.

As a beginner, I understood that automation is very important because organizations need fast and smart systems to manage their work efficiently.

---
