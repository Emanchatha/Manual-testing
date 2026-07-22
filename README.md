# Manual Testing Portfolio — OpenCart E-commerce Platform

## Overview
Complete manual testing documentation for OpenCart 
e-commerce platform including test plan, 24 test cases 
across 5 modules, and 6 bug reports found during 
exploratory testing.

**Tester:** Eman Fatima  
**Date:** July 2026  
**Environment:** Chrome, Windows 11  
**Website tested:** demo.opencart.com  

---

## What's Inside

### Test Plan
Defines scope, objectives, test types, entry and exit 
criteria for the testing engagement.

### Test Cases (24 total)
| Module | Test Cases | Types Covered |
|---|---|---|
| User Registration | 6 | Positive, Negative, Boundary |
| User Login | 5 | Positive, Negative, Security |
| Product Search | 4 | Positive, Negative |
| Shopping Cart | 5 | Positive, Negative |
| Checkout | 4 | Positive, Negative, Blocked |

### Bug Reports (6 bugs found)
| Bug ID | Title | Severity | Status |
|---|---|---|---|
| BUG_001 | Single character first name accepted | Major | Open |
| BUG_002 | Empty search submits without validation | Major | Open |
| BUG_003 | No account lockout after failed logins | Critical | Open |
| BUG_004 | Out of stock shown only at checkout | Critical | Open |
| BUG_005 | All products out of stock on demo site | Critical | Open |
| BUG_006 | Checkout button non-functional | Critical | Open |

---

## Testing Approach
- **Functional testing** — verified each feature works 
  as intended
- **Negative testing** — tested invalid inputs and 
  edge cases
- **Boundary testing** — tested minimum and maximum 
  input values
- **Security testing** — identified brute force 
  vulnerability in login

## Tools Used
- Browser: Chrome 126
- Bug tracking: Jira
- Documentation: Google Docs / GitHub Markdown

## Project Management
All test cases and bugs tracked in Jira.
Managed using Scrum with sprints, epics, and stories.
View Jira project: softwaredevelopment1.atlassian.net
