# Bug Reports

## QA-001 – Login succeeds with invalid credentials

**Severity:** High  
**Priority:** High  

### Steps:
1. Enter invalid email
2. Enter wrong password
3. Click login

### Expected:
- Login rejected

### Actual:
- Login successful

### Impact:
Unauthorized access risk

---

## QA-002 – Data not updated after edit

**Severity:** Medium  
**Priority:** High  

### Steps:
1. Edit data
2. Click save

### Expected:
- Data updated

### Actual:
- Data unchanged

### Impact:
Data inconsistency

---

## QA-003 – Empty input accepted

**Severity:** Medium  
**Priority:** Medium  

### Steps:
1. Submit empty form

### Expected:
- Validation error

### Actual:
- Form accepted

### Impact:
Poor data quality
