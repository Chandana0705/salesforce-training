# Day 15 - Data Management

# Data Quality Problems

Data quality problems occur when data is incorrect, incomplete, or duplicated.

Some common data quality problems are:

- Missing information
- Incorrect phone numbers
- Wrong email addresses
- Duplicate records
- Outdated data

### Example

A student record may have:
- Missing phone number
- Wrong email address
- Duplicate admission entries

### My Understanding

As a beginner, I understood that poor data quality can cause confusion and reduce system accuracy.

---

# Migration Discussion

Data migration is the process of moving data from one system to another.

Organizations often migrate data when:
- Adopting Salesforce
- Upgrading systems
- Combining multiple databases

### Example

A college may move student records from Excel sheets into Salesforce.

### Migration Steps

```text
Old System Data
        |
        v
Data Cleaning
        |
        v
Data Mapping
        |
        v
Salesforce Import
        |
        v
Verification
```

### My Understanding

Before migration, data should be cleaned to avoid transferring incorrect or duplicate information.

---

# Duplicate Prevention Ideas

Duplicate records can create confusion and reporting issues.

### Methods to Prevent Duplicates

#### Validation Rules
Check data before saving records.

#### Duplicate Rules
Prevent creation of duplicate records.

#### Matching Rules
Compare records using fields such as:
- Name
- Email
- Phone Number

#### Regular Data Review
Periodically identify and remove duplicate records.

### Example

If a student with the same email already exists, Salesforce can show a warning message.

---

# Enterprise Risks of Bad Data

Bad data can cause serious problems in enterprise systems.

Some risks include:

- Incorrect reports
- Poor decision making
- Duplicate communications
- Loss of customer trust
- Reduced productivity

### Example

If a student's contact information is incorrect:
- Important notifications may not be delivered.

### My Understanding

Enterprise systems depend on accurate data. Poor-quality data can affect the entire organization.

---

# Reflection

Today I learned about data quality, migration, duplicate prevention, and the risks of bad data. I understood that data is one of the most important assets in an organization. Even a well-designed Salesforce system may not work effectively if the data is inaccurate. As a beginner, I learned that maintaining clean and reliable data is essential for successful enterprise applications.

---
