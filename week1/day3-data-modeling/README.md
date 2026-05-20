# Salesforce Basics – Beginner Understanding

## 1. Difference Between App, Object, Record, and Field

| Term | Simple Meaning | Example |
|------|----------------|---------|
| App | A collection of tools/tabs used for a specific work | Student Management App |
| Object | A table that stores similar type of data | Student Object |
| Record | One single row of data inside an object | One student details |
| Field | A column that stores one piece of information | Student Name, Roll Number |

### Easy Example

If Salesforce is like an Excel file:

- App = Complete workbook
- Object = One sheet
- Record = One row
- Field = One column

---

# 2. Standard vs Custom Objects

| Standard Object | Custom Object |
|-----------------|---------------|
| Already provided by Salesforce | Created by user |
| Used for common business data | Used for company-specific data |
| Examples: Account, Contact, Opportunity | Examples: Student, Course, Faculty |

### My Understanding

- Salesforce already gives some ready-made objects called Standard Objects.
- If our college or company needs extra data, we create Custom Objects.

Example:

- Standard Object → Contact
- Custom Object → Student

---

# 3. My College Data Model

## Objects Used

### Custom Objects

1. Student
2. Course
3. Faculty
4. Attendance

---

## Relationships

| Object 1 | Relationship | Object 2 |
|----------|-------------|-----------|
| Student | Enrolled In | Course |
| Faculty | Teaches | Course |
| Student | Has | Attendance |

---

# College Data Model Diagram

```text
+-----------+        +-----------+
|  Student  | ------ |  Course   |
+-----------+        +-----------+
      |
      |
      v
+--------------+
| Attendance   |
+--------------+

+-----------+
| Faculty   |
+-----------+
      |
      v
+-----------+
| Course    |
+-----------+
```

---

# 4. Formula Fields

## What is Formula Field?

Formula Field automatically calculates value based on other fields.

We do not enter the value manually.

---

## Example 1: Student Full Name

### Formula

```text
First_Name + " " + Last_Name
```

### Explanation

It combines first name and last name automatically.

Example:

- First Name = Sai
- Last Name = Sree

Output:

```text
Sai Sree
```

---

## Example 2: Attendance Percentage

### Formula

```text
(Classes_Attended / Total_Classes) * 100
```

### Explanation

It automatically calculates attendance percentage.

Example:

- Classes Attended = 45
- Total Classes = 50

Output:

```text
90%
```

---

# 5. Validation Rules

## What is Validation Rule?

Validation Rule checks whether entered data is correct or not.

If data is wrong, Salesforce shows an error message.

---

## Example 1: Phone Number Validation

### Rule

Phone number should contain exactly 10 digits.

### Error Message

```text
Please enter valid 10-digit phone number.
```

### Explanation

This prevents users from entering incorrect phone numbers.

---

## Example 2: Age Validation

### Rule

Student age should not be less than 16.

### Error Message

```text
Age must be greater than or equal to 16.
```

### Explanation

This ensures only valid student data is stored.

---

# 6. Reflection – Why Structured Enterprise Data Matters

Structured enterprise data is important because it helps organizations store data in a proper and organized way.

Benefits:

- Easy to search information
- Reduces confusion
- Improves accuracy
- Saves time
- Helps in better decision making

In Salesforce, structured data helps companies and colleges manage students, customers, employees, and business processes efficiently.

As a beginner, I understood that Salesforce mainly works on organizing data properly so that businesses can work smoothly.

---
