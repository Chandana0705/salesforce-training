# Day 14 - Flow Governance

# Approval Workflow Examples

Approval workflows are used when a process needs permission or verification before moving to the next step.

## Example 1 - Student Scholarship Approval

```text
Student Applies for Scholarship
            |
            v
Faculty Reviews Application
            |
            v
Approved / Rejected
```

If approved, the scholarship is assigned to the student.

---

## Example 2 - Course Change Request

```text
Student Requests Course Change
            |
            v
Department Reviews Request
            |
            v
Approved / Rejected
```

If approved, the student's course is updated.

---

## Example 3 - Fee Waiver Request

```text
Student Requests Fee Waiver
            |
            v
Administration Reviews Request
            |
            v
Approved / Rejected
```

---

# Branching Flow Logic

Branching Flow Logic means a flow can take different paths based on conditions.

### Example - Attendance Monitoring

```text
Check Attendance
       |
       v
Attendance >= 75% ?
      / \
    Yes  No
     |    |
     |    v
     | Send Warning
     |
     v
Continue Normally
```

### Example - Scholarship Eligibility

```text
Check Marks
      |
      v
Marks > 90 ?
     / \
   Yes  No
    |    |
    | Not Eligible
    |
    v
Scholarship Eligible
```

### My Understanding

Branching logic helps Salesforce make decisions automatically based on data values.

---

# Governance Explanation

Governance means following rules, standards, and best practices while building and managing Salesforce applications.

Governance helps:
- Maintain data quality
- Improve security
- Reduce errors
- Ensure consistency
- Manage system changes properly

### Example

Before creating a new flow, a team should check:
- Is a similar flow already available?
- Will it affect existing automation?
- Does it follow company standards?

### My Understanding

Governance helps keep enterprise systems organized and prevents unnecessary problems.

---

# Reflection

Today I learned about approval workflows, branching logic, and governance. I understood that enterprise systems often require approvals and decision-making processes before actions are performed. I also learned that governance is important because large organizations need rules and standards to manage their Salesforce applications properly. As a beginner, I realized that building a system is not only about creating features but also about managing them in a structured and controlled way.

---
