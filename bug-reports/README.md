# Bug Reports

## Introduction
This document outlines various formats for bug reports, providing examples from different tools like Jira, Mantis, and Azure DevOps.

### Jira Format
- **Title:** Issue with Login
- **Description:** Users are unable to log in with correct credentials.
- **Steps to Reproduce:**
  1. Navigate to the login page.
  2. Enter valid credentials.
  3. Click 'Login'.
- **Expected Result:** User is logged in and redirected to the dashboard.
- **Actual Result:** An error message appears saying 'Invalid Credentials'.

### Mantis Format
- **Summary:** Null Pointer Exception on Checkout
- **Description:** A null pointer exception occurs when attempting to checkout products in the basket.
- **Steps to Reproduce:**
  1. Add products to basket.
  2. Proceed to checkout.
  3. An error occurs at payment.
- **Severity:** Major
- **Status:** New

### Azure DevOps Format
- **Title:** UI Rendering Issue on Dashboard
- **Description:** Some UI elements on the dashboard do not render correctly in Chrome.
- **Steps to Reproduce:**
  1. Open Chrome browser.
  2. Navigate to the dashboard.
  3. Observe the rendering issue.
- **Acceptance Criteria:** UI elements must render correctly across all major browsers.