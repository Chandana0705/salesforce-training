# Admin Day 4 - Security and Sharing

# What is OWD?

OWD stands for Organization-Wide Defaults.

OWD is the baseline level of access that determines which records users can see in Salesforce.

It helps control record-level security.

### Example

If Student records are set to Private:

- Students can only see their own records.
- Other users cannot see those records unless additional access is granted.

### My Understanding

As a beginner, I understood that OWD decides the default visibility of records in Salesforce.

---

# What is Role Hierarchy?

Role Hierarchy allows users higher in the organization structure to access records owned by users below them.

### Example

```text
Principal
    |
Department Head
    |
Faculty
```

In this hierarchy:

- Principal can view records of Department Heads and Faculty.
- Department Head can view records of Faculty.
- Faculty can only view their own records.

### My Understanding

Role Hierarchy helps organizations share records based on their management structure.

---

# What are Sharing Rules?

Sharing Rules are used to provide additional access to records beyond the OWD settings.

### Example

If Student records are Private:

A Sharing Rule can allow all Faculty members to view student records within their department.

### My Understanding

Sharing Rules help administrators safely share records with specific groups of users.

---

# Difference Between Profile, Permission Set, and Role

| Feature | Profile | Permission Set | Role |
|----------|----------|---------------|------|
| Controls User Permissions | Yes | Yes | No |
| Controls Record Access | No | No | Yes |
| Assigned to Every User | Yes | No |
| Provides Additional Access | No | Yes | No |
| Defines Hierarchy | No | No | Yes |

---

## Profile

A Profile determines what a user can do.

Examples:
- Create records
- Edit records
- Delete records

---

## Permission Set

A Permission Set provides extra permissions without changing the user's profile.

Example:
- Allow a faculty member to update attendance records temporarily.

---

## Role

A Role determines which records a user can view based on the organization's hierarchy.

Example:
- Principal can view records owned by faculty members.

---

# College Security Design

The College Management System should provide different access levels for different users.

```text
Administrator
      |
      +--- Principal
      |
      +--- Department Head
      |
      +--- Faculty
      |
      +--- Accounts Staff
      |
      +--- Students
```

### Access Design

| User | Access |
|--------|--------|
| Administrator | Full Access |
| Principal | View All College Records |
| Department Head | Department Records |
| Faculty | Student and Course Records |
| Accounts Staff | Fee Records |
| Student | Own Records Only |

---

# Faculty Access Scenario

### Scenario

A faculty member needs access to:

- Student attendance
- Assigned courses
- Student academic records

But should NOT access:

- Payroll information
- Administrative settings
- Other department records

### Solution

- Profile grants basic faculty permissions.
- Role provides access to faculty-owned records.
- Sharing Rules provide access to department student records.
- Permission Sets can provide temporary extra permissions if needed.

### My Understanding

Security should follow the principle of giving users only the access they need to perform their work.

---

# Reflection

Today I learned about OWD, Role Hierarchy, Sharing Rules, Profiles, and Permission Sets. I understood that Salesforce security works in multiple layers to protect data and control access. As a beginner, I learned that different users should have different levels of access based on their responsibilities. Proper security helps organizations protect sensitive information and maintain data privacy.

---

# Why is Record-Level Security Important?

Record-level security is important because not every user should be able to view or modify every record in the system. It helps protect sensitive information, prevents unauthorized access, and ensures users only work with relevant data. In a College Management System, students should only see their own records, while faculty and administrators should access records related to their responsibilities. As a beginner, I understood that record-level security is essential for maintaining privacy, security, and trust in enterprise systems.

---
