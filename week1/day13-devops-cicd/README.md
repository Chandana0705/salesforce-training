# Day 13 - DevOps and CI/CD

# What is CI/CD?

CI/CD stands for Continuous Integration and Continuous Deployment.

It is a process used in software development to automatically build, test, and deploy applications.

### Continuous Integration (CI)
Developers regularly add their code to a shared repository such as GitHub.

### Continuous Deployment (CD)
After testing is completed successfully, the changes are automatically deployed to the target environment.

### My Understanding

As a beginner, I understood that CI/CD helps developers deliver software updates faster and with fewer errors.

---

# Why Deployment Workflow Matters

A deployment workflow is the process of moving changes from development to production.

It is important because it helps:
- Reduce errors
- Improve software quality
- Ensure testing is completed
- Make deployments more organized
- Maintain system stability

### My Understanding

Without a proper workflow, changes can create problems in the system and affect users.

---

# Problems Without Version Control

Version control tools like Git and GitHub help track changes in a project.

Without version control, teams may face problems such as:

- Losing code changes
- Difficulty tracking updates
- No backup of previous versions
- Team members overwriting each other's work
- Hard to identify mistakes

### Example

If a developer accidentally deletes important code, recovering it becomes difficult without version control.

---

# GitHub + DX + DevOps Explanation

## GitHub

GitHub is used to store project code and track changes.

## Salesforce DX

Salesforce DX helps developers manage Salesforce projects using modern development tools.

## DevOps

DevOps combines development and operations practices to improve software delivery.

### How They Work Together

```text
Developer
    |
    v
Salesforce DX
    |
    v
GitHub Repository
    |
    v
Testing
    |
    v
CI/CD Pipeline
    |
    v
Deployment
    |
    v
Production Environment
```

### My Understanding

GitHub stores the code, Salesforce DX helps manage development, and DevOps helps automate testing and deployment.

---

# Enterprise Deployment Risks

Large organizations must be careful when deploying software because mistakes can affect many users.

Some deployment risks are:

- Application failures
- Data loss
- Security issues
- Broken features
- Performance problems

### Example

If a validation rule is configured incorrectly, users may not be able to save records.

### Risk Reduction Methods

- Testing before deployment
- Code reviews
- Backup strategies
- Version control
- CI/CD automation

---

# Reflection

Today I learned about CI/CD, DevOps, GitHub, and deployment workflows. I understood that enterprise software development requires proper processes to ensure software is reliable and secure. As a beginner, I learned that writing code is only one part of development. Testing, version control, and deployment workflows are also important for delivering high-quality software.

---
