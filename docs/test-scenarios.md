# Test Scenario

## Project Overview
This portfolio demonstrates web testing using Cypress for:
1. **Automation Exercise** as the black-box testing target
2. **Cypress Real World App (RWA)** as the white-box testing target

The goal is to showcase:
- black-box testing
- white-box testing
- smoke testing
- regression testing
- functional testing
- UI testing
- API/UI validation
- CI/CD integration

---

## Target Applications

### 1. Automation Exercise
Used for:
- Black-box testing
- Functional testing
- Smoke testing
- Regression testing
- UI testing
- API/UI validation

### 2. Cypress Real World App (RWA)
Used for:
- White-box testing
- Component testing
- Code-aware testing
- Coverage-oriented testing

---

## Modules Covered

### Automation Exercise
- Authentication
- Product Listing
- Product Search
- Cart
- Checkout
- API/UI interaction

### Cypress Real World App
- Authentication
- Navigation
- Transaction-related components
- Form validation components
- Reusable UI components

---

## High-Level Test Scenarios

### Authentication
- User can log in with valid credentials
- User cannot log in with invalid credentials
- User sees validation messages for empty required fields
- User can log out successfully

### Product
- User can view the product list
- User can search for a product
- User can open the product detail page

### Cart
- User can add a product to the cart
- User can remove a product from the cart
- Cart updates correctly after user action

### Checkout
- User can complete checkout with valid data
- User cannot complete checkout with missing required fields
- Total amount is displayed correctly

### API/UI Validation
- Login request returns expected response
- Product data from API is correctly rendered in UI

### White-Box / Component
- Component renders correctly with expected props
- Validation state is displayed correctly
- Important branches are exercised by tests

---

## Planned Smoke Scenarios
- Homepage loads successfully
- User logs in with valid credentials
- Product list is displayed
- User adds a product to cart
- User opens cart page
- User accesses checkout page
- User completes checkout successfully

---

## Planned Regression Scenarios
- Invalid login
- Empty field validation
- Product search
- Product detail page
- Add/remove cart item
- Checkout validation
- API/UI assertions
- Responsive viewport checks
- Component validation scenarios

---

## Notes
This document contains high-level scenarios only. Detailed test cases are documented in:
- `test-cases-blackbox.md`
- `test-cases-whitebox.md`