# Test Strategy – Kapital Bank Website

## 1. Purpose
The purpose of this Test Strategy is to define the testing approach, scope, environments, risks, and non-functional coverage for the Kapital Bank website.

## 2. Project Overview
The system under test is the official Kapital Bank public website:
https://www.kapitalbank.az

The website provides informational banking services including cards, credits, deposits, and online banking access.

## 3. Test Environments and Limitations

### Test Environment
- Used for functional, exploratory, negative, and regression testing
- No impact on real users
- Full testing scope allowed

### Production Environment
Testing on production is limited due to:
- Presence of real users
- Real financial and business data
- Legal and reputational risks

Allowed on Production:
- Smoke testing
- Content verification
- Navigation checks
- UI and responsiveness validation

Not Allowed on Production:
- Destructive testing
- Performance stress testing
- Security attack simulations
- Form submission with real data

## 4. Scope of Testing

### In Scope
- User-facing website features
- Navigation and content availability
- UI behavior and responsiveness

### Out of Scope
- Backend systems
- Core banking systems
- Mobile applications
- Third-party payment processing

## 5. Test Types and Approach

### Functional Testing
Verification of main user flows and feature behavior.

### Exploratory Testing
Ad-hoc testing to identify unexpected issues without predefined test cases.

### Negative Testing
Validation of system behavior with invalid inputs and incorrect user actions.

### UI & Responsiveness Testing
Verification of correct layout and usability across different screen resolutions and browsers.

### Content Testing
Validation of text accuracy, consistency, and correctness of banking information.

## 6. Non-Functional Testing (Basic Level)

### Performance (Basic)
- Page load time observation
- Verification that pages load without delays or errors

### Security (Basic)
- HTTPS availability
- No sensitive data exposed in UI
- Basic access control validation

### Accessibility (Basic)
- Readability of text
- Contrast between text and background
- Basic keyboard navigation checks

## 7. Test Tools
- Documentation: GitHub Markdown
- Bug tracking: GitHub Issues
- Diagram creation: draw.io

## 8. Entry Criteria
- Website is accessible
- Test environment is available
- Test documentation is prepared

## 9. Exit Criteria
- All planned tests are executed
- No critical production-blocking defects
- Test Summary Report prepared

## 10. Risks

- Website changes during testing
- Limited access to internal functionality
- Production testing limitations
- Browser-specific UI issues
- Incomplete or outdated content
