# Black-Box Test Cases

## Legend
- **Type**: Functional / Smoke / Regression / Negative / UI / Integration
- **Priority**: Critical / High / Medium / Low
- **Automation**: Yes / No / Planned

---

## Authentication

| ID | Module | Type | Priority | Scenario | Preconditions | Test Data | Expected Result | Automation |
|----|--------|------|----------|----------|---------------|-----------|-----------------|------------|
| TC-AUTH-001 | Authentication | Functional, Smoke | High | Login with valid credentials | User account exists | Valid email and password | User is logged in successfully and redirected to authenticated area | Yes |
| TC-AUTH-002 | Authentication | Functional, Negative, Regression | High | Login with invalid password | User account exists | Valid email, invalid password | Error message is displayed and login is blocked | Yes |
| TC-AUTH-003 | Authentication | Validation, Regression | Medium | Submit login form with empty fields | Login page is open | Empty email and password | Validation message is displayed or form submission is blocked | Yes |
| TC-AUTH-004 | Authentication | Functional, Sanity | High | Logout after successful login | User is logged in | Valid session | User session is cleared and public page is shown | Planned |

---

## Product

| ID | Module | Type | Priority | Scenario | Preconditions | Test Data | Expected Result | Automation |
|----|--------|------|----------|----------|---------------|-----------|-----------------|------------|
| TC-PROD-001 | Product Listing | Functional, Smoke | High | View product list | Product page is accessible | N/A | Product cards are displayed with basic information | Yes |
| TC-PROD-002 | Product Search | Functional, Regression | Medium | Search product by keyword | Product page is open | Product keyword | Relevant search results are displayed | Planned |
| TC-PROD-003 | Product Detail | Functional, UI | Medium | Open product detail page | Product exists | Product name | Product detail page displays name, image, description, and price | Planned |

---

## Cart

| ID | Module | Type | Priority | Scenario | Preconditions | Test Data | Expected Result | Automation |
|----|--------|------|----------|----------|---------------|-----------|-----------------|------------|
| TC-CART-001 | Cart | Functional, Smoke | Critical | Add product to cart | Product page is open | Single product | Selected product is added to cart and cart count is updated | Yes |
| TC-CART-002 | Cart | Functional, Regression | High | Remove product from cart | Product already in cart | Existing cart item | Product is removed and cart is updated | Planned |
| TC-CART-003 | Cart | Negative | Medium | Open checkout with empty cart | Cart is empty | N/A | User is blocked or informed that cart is empty | Planned |

---

## Checkout

| ID | Module | Type | Priority | Scenario | Preconditions | Test Data | Expected Result | Automation |
|----|--------|------|----------|----------|---------------|-----------|-----------------|------------|
| TC-CHK-001 | Checkout | Functional, Smoke | Critical | Complete checkout with valid data | Product exists in cart | Valid checkout data | Order is completed successfully and confirmation is displayed | Yes |
| TC-CHK-002 | Checkout | Validation, Negative, Regression | High | Submit checkout with missing required fields | User is on checkout page | Missing first name / address / other required data | Validation message is shown and order is not completed | Planned |
| TC-CHK-003 | Checkout | Functional, Regression | High | Verify total amount calculation | Product exists in cart | Product price and quantity | Total amount matches selected items | Planned |

---

## API/UI Validation

| ID | Module | Type | Priority | Scenario | Preconditions | Test Data | Expected Result | Automation |
|----|--------|------|----------|----------|---------------|-----------|-----------------|------------|
| TC-API-001 | Login API + UI | Integration, Regression | High | Verify login response and UI state | Login page is open | Valid credentials | Login request succeeds and UI updates accordingly | Planned |
| TC-API-002 | Product API + UI | Integration | Medium | Verify product data is rendered in UI | Product page is open | Product response data | UI displays data that matches API response | Planned |