# Test Plan

## 1. Test Plan Identifier

TP-AUTOEX-001

## 2. Introduction

This test plan is designed for testing of the Automation Exercise application. The system is a web-based demo e-commerce platform. The purpose of this testing project is to test the core user functionality of the web application focusing on its most important business workflows using manual and automated testing practices.

## 3. Test Objectives

The objectives for testing the application are as follows:

- Verify that the core system features functions according to expected user behaviour.
- Identify the system's functional defects.
- Validate system behaviour in response to valid and invalid inputs.
- Ensure proper operation of critical user workflows.
- Perform API validation where applicable.
- Build automated tests for key workflows.

## 4. Test Scope

### 4.1 In Scope:

- User authentication workflows
- Product browsing and search functionality
- Shopping cart operations
- Checkout process
- Payment workflow
- UI validation of critical user interface components

### 4.2 Out of Scope:

- Performance testing
- Security and penetration testing
- Third-party payment gateway integration testing
- Cross-device compatibility testing
- Email verification workflows

## 5. Test Approach

Manual testing will be conducted to verify core user functionality and business workflows of the application.  
Automated testing will be implemented to automate critical regression scenarios using:
- Selenium
- JavaScript

Testing will include functional, UI, positive, negative, edge case, and API testing.

## 6. Test Environment

**OS:** Windows 10 Pro  
**Browser:** Chrome, Firefox  
**Automation Tool:** Selenium WebDriver (JavaScript)  
**Repository:** Github Project Repository  
**API Testing:** Postman  

## 7. Test Deliverables
- Requirement Analysis
- Test Plan
- Test Scenarios
- Test Cases
- Bug Reports
- Automation Test Scripts (Selenium)
- Test Summary Report

## 8. Entry Criteria
- Target website availability
- Test environment ready
- Required browsers installed
- Automation tools installed
- Test scenarios prepared

## 9. Exit Criteria
- All tests executed
- Critical bugs reported
- Test summary report prepared

## 10. Risks and Mitigation

| Risk | Mitigation |
|-|-|
| Website downtime | Document system unavailability or retry testing later |
| Unstable test data | Use dedicated test accounts and controlled test inputs |
| UI-API mismatch | Validate API responses separately using Postman |
| Automation failures | Use stable locators and explicit waits in Selenium tests |
| Time constraint | Prioritize critical workflows and avoid out-of-scope features |