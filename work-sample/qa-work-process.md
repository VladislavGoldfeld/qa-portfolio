# QA Work Sample — Example Process

## Context
Simulated QA workflow based on typical web application testing tasks.

---

## Task
Test the login functionality of a web application.

---

## Test approach

### 1. Functional testing
- Verified login with valid credentials
- Checked login with invalid email format
- Checked login with empty fields
- Verified error messages display

### 2. UI testing
- Checked alignment of login form elements
- Verified button states (enabled/disabled)
- Checked responsiveness on different screen sizes

### 3. API validation (basic understanding)
- Observed login request in DevTools Network tab
- Verified status codes (200 / 400 / 401)
- Checked response body structure

---

## Found issues

### Bug 1
Login button does not show validation message for empty fields

Severity: Medium  
Priority: High  

---

### Bug 2
Incorrect error message displayed for invalid email format

Severity: Low  
Priority: Medium  

---

## Tools used
- Chrome DevTools
- Postman (conceptual understanding)
- Manual testing

---

## Result
Login functionality partially works but requires improvements in validation handling and UX feedback.
