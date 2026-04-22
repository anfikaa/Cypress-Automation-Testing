# Bug Reports

## Bug Report Template

### Bug ID
BUG-001

### Title
Login form allows submission with empty password

### Module
Authentication

### Severity
High

### Priority
High

### Environment
- Browser: Chrome
- Test Type: Black-box
- Environment: Automation Exercise

### Preconditions
User is on the login page.

### Steps to Reproduce
1. Open login page
2. Enter valid email
3. Leave password field empty
4. Click login button

### Actual Result
The form is submitted without blocking the request.

### Expected Result
The form should block submission and display a validation message.

### Attachment
Screenshot/video path: `docs/evidence/screenshots/bug-001.png`

---

## Bug Report Example 2

### Bug ID
BUG-002

### Title
Cart item count does not update after removing a product

### Module
Cart

### Severity
Medium

### Priority
High

### Environment
- Browser: Chrome
- Test Type: Regression
- Environment: Automation Exercise

### Preconditions
User has at least one product in the cart.

### Steps to Reproduce
1. Open cart page
2. Remove one product
3. Observe cart count badge

### Actual Result
The item is removed from cart list, but badge count remains unchanged.

### Expected Result
The badge count should update immediately after item removal.

---

## Notes
Only validated and reproducible issues should be treated as actual defects. Example reports in this repository are included to demonstrate bug documentation format.