# Admin Day 1 - User Management

# What is a Salesforce Administrator?

A Salesforce Administrator is a person who manages and maintains the Salesforce system.

An administrator is responsible for:
- Creating users
- Managing security
- Assigning permissions
- Creating reports and dashboards
- Configuring Salesforce features

### My Understanding

As a beginner, I understood that a Salesforce Administrator helps ensure the system runs smoothly and securely.

---

# Difference Between User, Role, Profile, and Permission Set

| Term | Meaning |
|--------|---------|
| User | A person who can log in to Salesforce |
| Role | Defines record visibility and hierarchy |
| Profile | Defines what a user can do in Salesforce |
| Permission Set | Gives additional permissions without changing the profile |

---

## User

A User is an individual who accesses Salesforce.

### Example

- Student Coordinator
- Faculty Member
- College Administrator

---

## Role

A Role controls which records a user can view based on the organization's hierarchy.

### Example

```text
College Principal
       |
       v
Department Head
       |
       v
Faculty Member
```

---

## Profile

A Profile controls permissions such as:

- Create records
- Edit records
- Delete records
- View objects

### Example

Faculty Profile:
- Can view student records
- Cannot delete student records

---

## Permission Set

Permission Sets provide extra permissions to specific users.

### Example

A faculty member may temporarily receive permission to update attendance records.

---

# College Security Design

For the College Management System, different users should have different levels of access.

| User Type | Access Level |
|------------|-------------|
| Administrator | Full access |
| Faculty | Student and course access |
| Student | Own records only |
| Accounts Staff | Fee-related records |
| Department Head | Department records |

### Simple Security Structure

```text
Administrator
      |
      +--- Faculty
      |
      +--- Accounts Staff
      |
      +--- Students
```

### My Understanding

Not every user should have access to all information. Access should be given based on job responsibilities.

---

# Administrator Access Risks

Administrators have powerful permissions, so improper use can create risks.

## Risk 1

Accidental deletion of important records.

---

## Risk 2

Incorrect permission assignments.

---

## Risk 3

Unauthorized access to sensitive data.

---

## Risk 4

Changes that affect system functionality.

---

## Risk 5

Security and compliance issues.

### My Understanding

Administrator access should be used carefully because it can impact the entire organization.

---

# Reflection

Enterprise systems store important business and customer data. If every user has full access, data can be changed, deleted, or viewed by unauthorized people. Roles, Profiles, and Permission Sets help ensure users only access the information they need. As a beginner, I understood that strong access control improves security, protects sensitive data, and helps organizations operate safely and efficiently.

---

# Why Do Enterprise Systems Need Strong Access Control?

Enterprise systems need strong access control to protect sensitive information and ensure users only perform actions related to their responsibilities. Proper access control reduces security risks, prevents unauthorized changes, protects data privacy, and helps maintain system reliability. As a beginner, I learned that security is one of the most important parts of managing a Salesforce organization.

---
