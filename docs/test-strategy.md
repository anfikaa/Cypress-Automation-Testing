# Test Strategy

## Objective
The objective of this project is to build a QA automation portfolio using Cypress that demonstrates practical web testing skills across multiple testing types, including:
- black-box testing
- white-box testing
- smoke testing
- regression testing
- functional testing
- UI testing
- API/UI validation
- CI/CD execution

---

## Test Approach

### Black-Box Testing
Black-box testing is performed on **Automation Exercise**, focusing on user-facing functionality without relying on internal application code.

### White-Box Testing
White-box testing is performed on **Cypress Real World App (RWA)** using component-level and code-aware testing approaches, since source code access is required.

### Smoke Testing
A small set of critical scenarios is executed to confirm the application is stable enough for deeper testing.

### Regression Testing
A broader suite is executed to verify that existing features continue to work after changes or refactoring.

---

## Test Types Included
- Functional Testing
- UI Testing
- Smoke Testing
- Regression Testing
- Negative Testing
- API/UI Validation
- Component Testing
- Responsive Testing (basic)

---

## Tools
- Cypress
- JavaScript
- Node.js
- GitHub Actions
- Fixtures for test data
- Custom Cypress commands
- Page abstraction/helpers

---

## Test Environment

### Black-Box Environment
- Website: Automation Exercise
- Browser: Chrome / Electron
- Execution: Local and CI

### White-Box Environment
- App: Cypress Real World App (local)
- Execution: Local and CI

---

## Entry Criteria
Testing can start when:
- target application is accessible
- environment is stable
- core scenarios are identified
- test data is prepared

---

## Exit Criteria
Testing is considered complete when:
- smoke suite passes
- planned automated scenarios are implemented
- critical defects are documented
- test reports and evidence are generated
- CI workflow runs successfully

---

## Deliverables
- Test scenarios
- Test cases
- Traceability matrix
- Bug report samples
- Test summary report
- Cypress test scripts
- CI/CD workflow configuration

---

## Risks and Constraints
Detailed risks are documented in `scope-and-risk.md`.