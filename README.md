# TaskPro QA Testing Project

## Overview
This project contains API testing, test case management, and bug tracking activities performed on the TaskPro application.

The goal was to validate core functionalities of the TaskPro system using industry-standard QA tools and workflows.

---

## Tools & Technologies
- Postman (API Testing)
- TestRail (Test Case Management)
- Jira (Bug Tracking)
- Swagger (API Documentation)
- REST API

---

## Application Under Test
TaskPro is a task management application that allows users to:
- Create and manage boards
- Add, update, and delete tasks
- Move tasks between columns
- Authenticate users (register/login)

---

## Test Scope

### Modules Tested:
- User Registration
- User Login
- Board Creation & Management
- Task Operations (Create / Update / Move / Delete)
- Column Management

---

## Testing Approach

### 1. API Testing (Postman)
- All endpoints were tested using Postman
- Positive and negative scenarios were covered
- Authorization tested using Bearer Token
- Status codes validated (200, 401, 404, etc.)

---

### 2. Test Case Management (TestRail)
- Test cases were created based on requirements
- Both functional and edge cases were included
- Test execution results were documented

---

### 3. Bug Tracking (Jira)
- Bugs identified during testing were logged in Jira
- Each bug includes:
  - Steps to reproduce
  - Expected vs actual result
  - Severity level

---

## Example Test Scenarios
- Register with valid/invalid email formats
- Login with incorrect password → 401 Unauthorized
- Create board without token
- Move task between columns and verify order update
- Delete task and verify removal from UI/API

---

## Workflow
Swagger → Postman → TestRail → Jira

---

## Conclusion
This project demonstrates end-to-end QA workflow including API testing, test case design, and defect reporting for a real-world task management system.
