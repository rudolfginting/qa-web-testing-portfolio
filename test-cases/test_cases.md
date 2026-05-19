# Test Cases

## TC-001 – Login Authentication Validation

**Module:** Authentication  
**Type:** Functional / Negative Testing  
**Priority:** High  

### Steps:
1. Enter invalid email
2. Enter incorrect password
3. Click Login

### Expected:
- Login fails
- Error message displayed

### Actual:
- User logged in successfully

### Status:
Failed

---

## TC-002 – Update Data (CRUD)

**Module:** Data Management  
**Type:** Functional Testing  
**Priority:** High  

### Steps:
1. Select data
2. Click Edit
3. Modify data
4. Click Save

### Expected:
- Data updated successfully

### Actual:
- Data not updated

### Status:
Failed

---

## TC-003 – Input Validation

**Module:** Input Form  
**Type:** Negative Testing  
**Priority:** Medium  

### Steps:
1. Leave required fields empty
2. Click Submit

### Expected:
- Validation message appears

### Actual:
- Form submitted

### Status:
Failed
