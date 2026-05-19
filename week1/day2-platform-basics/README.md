
## 1. What is Salesforce Platform?

Salesforce Platform is a cloud-based platform used to build and manage business applications without needing heavy hardware or software installation.

It helps companies:
- Store customer data
- Automate business work
- Create apps
- Manage users and records

Example:
A college can use Salesforce to manage:
- Student details
- Courses
- Fees
- Attendance

Everything is stored online and can be accessed easily.

---

# 2. Explain

## App

An App in Salesforce is a collection of tools, tabs, and objects designed for a specific work.

Example:
Student Management App

Inside the app:
- Student Tab
- Course Tab
- Faculty Tab

The app helps users access everything in one place.

---

## Object

An Object is like a database table used to store data.

Example:

| Object Name | Stores |
|-------------|--------|
| Student | Student details |
| Course | Course information |
| Faculty | Faculty data |

Each object contains records and fields.

Example:
Student Object fields:
- Name
- Roll Number
- Branch
- Phone Number

---

## Tab

A Tab is used to open and access objects or pages in Salesforce.

It helps users quickly view records.

Example:
- Student Tab → Opens Student records
- Course Tab → Opens Course records

Tabs make navigation simple for users.

---

# 3. Difference: Configuration vs Coding

| Configuration | Coding |
|---------------|--------|
| Done using clicks | Done using programming |
| Easy to create | Requires coding knowledge |
| Faster development | Takes more time |
| Uses tools already available in Salesforce | Uses Apex or Visualforce/LWC |
| Example: Creating objects | Example: Writing Apex class |

Simple Meaning:
- Configuration = No-code or low-code development
- Coding = Writing custom logic using code

---

# 4. Your System Design

## App Name
Student Management System

## Objects Used
1. Student
2. Course
3. Faculty
4. Attendance

## User Interaction

### Admin
- Adds student details
- Creates courses
- Manages faculty data

### Faculty
- Updates attendance
- Views student information

### Student
- Views course details
- Checks attendance

Flow:
User → Opens App → Uses Tabs → Accesses Objects → Performs Actions

---

# Conclusion

Salesforce Platform helps in creating applications easily using apps, objects, and tabs. It supports both configuration and coding methods to build business solutions.
