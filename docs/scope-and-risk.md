# Scope and Risk

## In Scope

### Automation Exercise
- Authentication flow
- Product listing and search
- Cart functionality
- Checkout flow
- Basic API/UI validation
- Basic responsive checks

### Cypress Real World App
- Selected component behavior
- Validation logic
- Rendering states
- White-box/component scenarios

---

## Out of Scope
- Performance testing
- Load testing
- Security penetration testing
- Cross-browser full matrix testing
- Database-level validation
- Full accessibility audit
- Payment gateway real transaction testing

---

## Key Risks

### 1. Public Demo Site Instability
Automation Exercise is a public practice site, so UI changes or environment instability may affect test reliability.

### 2. Test Data Dependency
Some flows depend on valid user data and reusable accounts.

### 3. Selector Fragility
If the target application changes DOM structure, some selectors may become unstable.

### 4. White-Box Coverage Limitation
White-box testing is only feasible on applications with source code access, so it is limited to RWA.

### 5. CI Runtime Differences
Tests that pass locally may behave differently in CI due to environment speed or rendering differences.

---

## Mitigation Plan
- Use stable selectors whenever possible
- Keep fixtures separate from test logic
- Isolate smoke and regression suites
- Document known limitations clearly
- Avoid over-dependence on brittle UI paths

---

## Priority Model
Priority is assigned as:
- **Critical**: core business flow blocked
- **High**: major functionality affected
- **Medium**: important but non-blocking functionality
- **Low**: minor issue or cosmetic behavior

---

## Notes
This project is designed as a learning and portfolio exercise, so scope is intentionally focused on realistic and demonstrable web testing practices.