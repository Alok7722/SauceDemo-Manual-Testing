# 🧪 SauceDemo – End-to-End Manual Testing & QA Documentation Portfolio

![Testing Type](https://img.shields.io/badge/Testing%20Type-Manual%20Testing-blue?style=flat-square)
![STLC Lifecycle](https://img.shields.io/badge/STLC-Full%20Lifecycle-success?style=flat-square)
![Test Scenarios](https://img.shields.io/badge/Test%20Scenarios-20%20Scenarios-blueviolet?style=flat-square)
![Test Cases](https://img.shields.io/badge/Test%20Cases-63%20Executed-informational?style=flat-square)
![Pass Rate](https://img.shields.io/badge/Pass%20Rate-95.2%25%20(60%2F63)-brightgreen?style=flat-square)
![Defects Found](https://img.shields.io/badge/Defects%20Logged-4%20Bugs-orange?style=flat-square)
![Requirement Coverage](https://img.shields.io/badge/RTM%20Coverage-100%25-brightgreen?style=flat-square)
![Target Role](https://img.shields.io/badge/Target%20Role-QA%20%7C%20SDET%20Fresher%20(2026)-darkblue?style=flat-square)

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Application Under Test](#-application-under-test)
- [Project Objectives](#-project-objectives)
- [Repository Structure](#-repository-structure)
- [STLC Deliverables & Artifacts](#-stlc-deliverables--artifacts)
- [Test Scenarios & Scope Summary](#-test-scenarios--scope-summary)
- [Test Execution Results & Metrics](#-test-execution-results--metrics)
- [Requirement Traceability Matrix (RTM)](#-requirement-traceability-matrix-rtm)
- [Testing Methodologies Applied](#-testing-methodologies-applied)
- [Defect Reporting & Visual Evidence](#-defect-reporting--visual-evidence)
- [Tools, Techniques & QA Skills Demonstrated](#-tools-techniques--qa-skills-demonstrated)
- [How to Explore the Project Documents](#-how-to-explore-the-project-documents)
- [Key Learnings & Future Roadmap](#-key-learnings--future-roadmap)
- [Author & Professional Links](#-author--professional-links)

---

## 📌 Project Overview

This repository showcases a comprehensive, industry-standard **Manual Testing portfolio project** performed on the **SauceDemo (Swag Labs)** e-commerce web application.

The project demonstrates end-to-end practical mastery of the **Software Testing Life Cycle (STLC)**—from initial requirement breakdown, test planning, scenario specification, and test case authoring, to execution tracking, defect logging with screenshot evidence, bidirectional traceability (RTM), and formal test summary reporting.

---

## 🌐 Application Under Test

* **Platform Name:** SauceDemo (Swag Labs by Sauce Labs)
* **Application URL:** [https://www.saucedemo.com/](https://www.saucedemo.com/)
* **Application Type:** E-commerce Web Application (Single-Page App)
* **Test Environment:** Google Chrome (Version 120+) on Windows 11
* **Test Focus:** Core user journeys including Authentication, Catalog Browsing, Cart Operations, Multi-Step Checkout, and State Management.

---

## 🎯 Project Objectives

1. **Systematic Requirement Analysis:** Extract 20 functional specifications (`FR-001` to `FR-020`) from the web application.
2. **Standardized Test Planning:** Define scope, testing strategy, environments, entry/exit criteria, and risks following IEEE 829 standards.
3. **Comprehensive Test Design:** Create 20 high-level test scenarios and 63 granular, step-by-step test cases.
4. **Rigorous Test Execution:** Validate positive, negative, boundary, and exploratory paths, recording actual vs expected results.
5. **Professional Defect Tracking:** Identify, isolate, and document 4 legitimate defects with reproducible steps, severity/priority tags, and image attachments.
6. **100% Requirement Traceability:** Ensure no requirement remains untested through a bidirectional RTM.
7. **Executive Test Closure:** Synthesize execution data into formal sign-off metrics.

---

## 📁 Repository Structure

```
SauceDemo-Manual-Testing/
├── .gitignore                                         # Filters Office lock files and system metadata
├── README.md                                          # Complete STLC portfolio showcase
├── Requirement_Document_SauceDemo.docx                # BRD / Functional specifications (FR-001 to FR-020)
├── Test_Plan_SauceDemo.docx                           # Master QA strategy, scope, risks & criteria
├── Test_Scenarios_SauceDemo.docx                      # 20 high-level functional & validation scenarios
├── Test_Case_SauceDemo.xlsx                           # 63 test cases with steps, data, status & bug IDs
├── RTM_Requirement_Traceability_Matrix_SauceDemo.docx # Bidirectional matrix ensuring 100% test coverage
├── Test_Execution_SauceDemo.docx                      # Cycle execution log & module-wise statistics
├── Bug_Report_SauceDemo.xlsx                          # Formal defect tracking log (4 defects recorded)
├── Test_Summary_Report_SauceDemo.docx                 # STLC sign-off report & release recommendation
└── bug-evidence/                                      # Defect screenshot attachments
    ├── TC-SD-009-Alignment_issue.png                  # Proof for BUG-LOGIN-001
    ├── TC-SD-012-Product_Name_wrong.png               # Proof for BUG-PRODUCTS-002
    ├── TC-SD-012-Product_Description_Wrong.png        # Proof for BUG-PRODUCTS-003
    └── TC-SD-062-Remove_button_not_changed.png        # Proof for BUG-NAVIGATION-004
```

---

## 📑 STLC Deliverables & Artifacts

| # | Artifact | File | Format | Key Details Included |
|:-:|:---------|:-----|:------:|:---------------------|
| 1 | **Requirements Document** | `Requirement_Document_SauceDemo.docx` | DOCX | 20 functional requirements (`FR-001` to `FR-020`), in-scope/out-of-scope modules, user roles, business rules. |
| 2 | **Test Plan** | `Test_Plan_SauceDemo.docx` | DOCX | IEEE-829 structure: objective, scope, test strategy, browser/OS environment, schedule, entry/exit criteria, and risk mitigation. |
| 3 | **Test Scenarios** | `Test_Scenarios_SauceDemo.docx` | DOCX | 20 high-level test scenarios (`TS-SD-001` to `TS-SD-020`) categorized by module, test type, and coverage focus. |
| 4 | **Test Cases** | `Test_Case_SauceDemo.xlsx` | XLSX | 63 detailed test cases with TC ID, Module, Scenario ID, Title, Pre-conditions, Step No, Test Steps, Test Data, Expected Result, Actual Result, Status, Priority, Tester, and Bug ID. |
| 5 | **Traceability Matrix** | `RTM_Requirement_Traceability_Matrix_SauceDemo.docx` | DOCX | Bidirectional mapping verifying that 100% of functional requirements link to test scenarios and test cases with zero untested features. |
| 6 | **Test Execution Report** | `Test_Execution_SauceDemo.docx` | DOCX | Detailed cycle execution log recording module pass/fail distributions, environment details, and execution observations. |
| 7 | **Bug Report** | `Bug_Report_SauceDemo.xlsx` | XLSX | Formal defect register tracking Bug ID, Title, Module, Severity, Priority, Steps to Reproduce, Expected vs Actual Behavior, Status, and Attachment linkage. |
| 8 | **Test Summary Report** | `Test_Summary_Report_SauceDemo.docx` | DOCX | STLC closure document detailing test metrics, defect analysis, risk summary, and final release recommendation. |

---

## 📋 Test Scenarios & Scope Summary

The testing suite covers **20 high-level test scenarios** (`TS-SD-001` to `TS-SD-020`) spanning all major functional areas:

| Scenario ID | Module | Test Scenario Description | Testing Type | Coverage |
|:------------|:-------|:--------------------------|:------------:|:--------:|
| **TS-SD-001** | Login | Verify SauceDemo login page loads successfully | Smoke | UI |
| **TS-SD-002** | Login | Verify user can login with valid credentials | Functional | End-to-End |
| **TS-SD-003** | Login | Verify error message is displayed for invalid username | Negative | Validation |
| **TS-SD-004** | Login | Verify error message is displayed for invalid password | Negative | Validation |
| **TS-SD-005** | Login | Verify validation message when username is empty | Negative | Validation |
| **TS-SD-006** | Login | Verify validation message when password is empty | Negative | Validation |
| **TS-SD-007** | Products | Verify Products page loads after successful login | Smoke | Navigation |
| **TS-SD-008** | Products | Verify product list displays name, price, image and Add to Cart button | Functional | UI |
| **TS-SD-009** | Products | Verify user can sort products using sort dropdown based on selected criteria | Functional | Business Rule |
| **TS-SD-010** | Products | Verify user can add a single product to cart from Products page | Functional | End-to-End |
| **TS-SD-011** | Products | Verify user can remove a product from Products page after adding to cart | Functional | End-to-End |
| **TS-SD-012** | Cart | Verify cart icon badge count updates correctly after adding/removing items | Regression | Data |
| **TS-SD-013** | Cart | Verify user can navigate to Cart page from Products page | Functional | Navigation |
| **TS-SD-014** | Cart | Verify Cart page displays added product details correctly | Functional | Data |
| **TS-SD-015** | Cart | Verify user can remove product from Cart page | Functional | End-to-End |
| **TS-SD-016** | Checkout | Verify user can proceed to checkout from Cart page | Smoke | End-to-End |
| **TS-SD-017** | Checkout | Verify user can enter checkout information and continue | Functional | End-to-End |
| **TS-SD-018** | Checkout | Verify error message is displayed when checkout information is incomplete | Negative | Validation |
| **TS-SD-019** | Checkout | Verify user can complete the order successfully | Functional | End-to-End |
| **TS-SD-020** | Logout | Verify user can logout successfully from the application | Smoke | Navigation |

---

## 📊 Test Execution Results & Metrics

### Executive Metrics Summary

$$\text{Pass Rate} = \frac{\text{Passed Test Cases}}{\text{Total Test Cases Executed}} \times 100 = \frac{60}{63} \times 100 = \mathbf{95.2\%}$$

| Metric Category | Count | Status / Rate |
|:----------------|:-----:|:-------------:|
| **Total Functional Requirements (FR)** | 20 | 100% Covered |
| **Total Test Scenarios** | 20 | 100% Executed |
| **Total Test Cases Designed** | 63 | 100% Executed |
| **Test Cases Passed** | 60 | 95.2% |
| **Test Cases Failed** | 3 | 4.8% |
| **Test Cases Blocked / Not Run** | 0 | 0.0% |
| **Total Defects Logged** | 4 | All Documented |

### Module-Wise Execution Breakdown

| Module | Test Cases Designed | Test Cases Executed | Passed | Failed | Pass Rate | Linked Defects |
|:-------|:-------------------:|:-------------------:|:------:|:------:|:---------:|:--------------:|
| **Login** | 15 | 15 | 14 | 1 | 93.3% | `BUG-LOGIN-001` |
| **Products Catalog** | 17 | 17 | 16 | 1 | 94.1% | `BUG-PRODUCTS-002`, `BUG-PRODUCTS-003` |
| **Cart Operations** | 10 | 10 | 10 | 0 | 100.0% | None (All Passed) |
| **Checkout Flow** | 15 | 15 | 15 | 0 | 100.0% | None (All Passed) |
| **Logout** | 2 | 2 | 2 | 0 | 100.0% | None (All Passed) |
| **Navigation & Session** | 4 | 4 | 3 | 1 | 75.0% | `BUG-NAVIGATION-004` |
| **Total** | **63** | **63** | **60** | **3** | **95.2%** | **4 Logged Defects** |

---

## 🔗 Requirement Traceability Matrix (RTM)

The Requirement Traceability Matrix maps all **20 Functional Requirements** (`FR-001` through `FR-020`) directly to Test Scenarios and granular Test Cases.

* **Requirement Coverage:** 20 / 20 Requirements Covered (**100%**)
* **Gaps Identified:** **0** (No orphaned requirements, no missing test cases)
* **Bidirectional Traceability:** Forward (Requirement → Test Case) and Backward (Defect → Test Case → Requirement)

| Requirement ID | Requirement Description | Test Scenario ID | Associated Test Case IDs | Coverage Status |
|:--------------:|:------------------------|:----------------:|:-------------------------|:---------------:|
| **FR-001** | Verify login page loads successfully | `TS-SD-001` | `TC-SD-001` | Covered |
| **FR-002** | Verify user can login with valid credentials | `TS-SD-002` | `TC-SD-002, TC-SD-008, TC-SD-044, TC-SD-047, TC-SD-048` | Covered |
| **FR-003** | Verify error message on invalid username | `TS-SD-003` | `TC-SD-003, TC-SD-009, TC-SD-046` | Covered |
| **FR-004** | Verify error message on invalid password | `TS-SD-004` | `TC-SD-004` | Covered |
| **FR-005** | Verify validation when username is empty | `TS-SD-005` | `TC-SD-005, TC-SD-007` | Covered |
| **FR-006** | Verify validation when password is empty | `TS-SD-006` | `TC-SD-006, TC-SD-007` | Covered |
| **FR-007** | Verify Products page loads after login | `TS-SD-007` | `TC-SD-011, TC-SD-060, TC-SD-061, TC-SD-062, TC-SD-063` | Covered |
| **FR-008** | Verify product card details (name, price, img) | `TS-SD-008` | `TC-SD-012, TC-SD-013, TC-SD-014` | Covered |
| **FR-009** | Verify product sorting functionality | `TS-SD-009` | `TC-SD-015, TC-SD-016, TC-SD-017, TC-SD-018` | Covered |
| **FR-010** | Verify single product addition to cart | `TS-SD-010` | `TC-SD-019, TC-SD-021` | Covered |
| **FR-011** | Verify product removal from Products page | `TS-SD-011` | `TC-SD-020, TC-SD-022` | Covered |
| **FR-012** | Verify cart badge count synchronization | `TS-SD-012` | `TC-SD-023, TC-SD-024` | Covered |
| **FR-013** | Verify navigation to Cart page | `TS-SD-013` | `TC-SD-025, TC-SD-026` | Covered |
| **FR-014** | Verify Cart page item listing | `TS-SD-014` | `TC-SD-027, TC-SD-028` | Covered |
| **FR-015** | Verify removing product from Cart page | `TS-SD-015` | `TC-SD-029, TC-SD-030` | Covered |
| **FR-016** | Verify navigation from Cart to Checkout | `TS-SD-016` | `TC-SD-031, TC-SD-032` | Covered |
| **FR-017** | Verify entering valid checkout details | `TS-SD-017` | `TC-SD-033, TC-SD-034, TC-SD-035` | Covered |
| **FR-018** | Verify error handling on missing checkout info | `TS-SD-018` | `TC-SD-036, TC-SD-037, TC-SD-038` | Covered |
| **FR-019** | Verify checkout overview and order completion | `TS-SD-019` | `TC-SD-039, TC-SD-040, TC-SD-041, TC-SD-042, TC-SD-043` | Covered |
| **FR-020** | Verify logout workflow and session termination | `TS-SD-020` | `TC-SD-058, TC-SD-059` | Covered |

---

## 🧪 Testing Methodologies Applied

* **Smoke Testing:** Executed high-level sanity checks to confirm environment readiness, page availability, and primary authentication paths.
* **Functional Testing:** Verified core positive user stories including catalog browsing, cart operations, pricing calculations, and order placement.
* **Negative & Validation Testing:** Tested defensive application boundaries using invalid characters, mismatched passwords, empty mandatory fields, and incomplete postal codes.
* **UI & Visual Validation:** Examined typography, button color changes (Add to Cart vs Remove), badge indicators, alignment, and responsiveness.
* **Exploratory Testing:** Conducted free-form testing beyond scripted steps to uncover application state bugs (such as resetting app state from the sidebar).
* **Regression Testing:** Re-validated cart operations and state persistence across page navigations and user interactions.

---

## 🐛 Defect Reporting & Visual Evidence

During test execution, **4 legitimate defects** were isolated, logged in the defect tracking sheet, and documented with screenshot evidence:

### Defect Register Summary

| Bug ID | Module | Severity | Priority | Defect Summary | Status | Linked Test Case | Evidence Attachment |
|:-------|:-------|:--------:|:--------:|:---------------|:------:|:----------------:|:--------------------|
| **BUG-LOGIN-001** | Login | Minor | Medium | Error message text alignment issue inside error container | New | `TC-SD-009` | `TC-SD-009-Alignment_issue.png` |
| **BUG-PRODUCTS-002** | Products | Major | High | Incorrect product title rendered in catalog listing | New | `TC-SD-012` | `TC-SD-012-Product_Name_wrong.png` |
| **BUG-PRODUCTS-003** | Products | Major | High | Typo and content error in "Sauce Labs Backpack" description | New | `TC-SD-012` | `TC-SD-012-Product_Description_Wrong.png` |
| **BUG-NAVIGATION-004** | Navigation | Major | High | Reset App State clears cart badge count but leaves "Remove" button state unchanged | New | `TC-SD-062` | `TC-SD-062-Remove_button_not_changed.png` |

---

### Detailed Defect Reports & Evidence

#### 1. BUG-LOGIN-001: Error Message UI Alignment Issue
* **Test Case ID:** `TC-SD-009` (Step 3)
* **Module:** Login | **Severity:** Minor | **Priority:** Medium
* **Steps to Reproduce:**
  1. Open Chrome browser and navigate to `https://www.saucedemo.com/`
  2. Enter invalid username and password.
  3. Click the **Login** button.
  4. Inspect the error notification banner at the bottom of the login container.
* **Expected Result:** The error message text should be properly aligned, centered, and readable with proper padding.
* **Actual Result:** The error message text exhibits an alignment issue and does not render cleanly within container boundaries.

![BUG-LOGIN-001 Screenshot](bug-evidence/TC-SD-009-Alignment_issue.png)

---

#### 2. BUG-PRODUCTS-002: Incorrect Product Name in Catalog
* **Test Case ID:** `TC-SD-012` (Step 2)
* **Module:** Products | **Severity:** Major | **Priority:** High
* **Steps to Reproduce:**
  1. Log in to `https://www.saucedemo.com/` with standard credentials.
  2. On the Products inventory page, review all product cards.
  3. Check the item title for the T-Shirt product item.
* **Expected Result:** Every product title must match the official product catalog definition accurately.
* **Actual Result:** The T-Shirt product title contains incorrect nomenclature.

![BUG-PRODUCTS-002 Screenshot](bug-evidence/TC-SD-012-Product_Name_wrong.png)

---

#### 3. BUG-PRODUCTS-003: Product Description Content Typo
* **Test Case ID:** `TC-SD-012` (Step 3)
* **Module:** Products | **Severity:** Major | **Priority:** High
* **Steps to Reproduce:**
  1. Log in to `https://www.saucedemo.com/` with valid credentials.
  2. Locate the "Sauce Labs Backpack" product card.
  3. Inspect the product description text.
* **Expected Result:** Description copy should clearly and accurately describe the item without textual or typographical mistakes.
* **Actual Result:** The description contains a typographical error and content inconsistency.

![BUG-PRODUCTS-003 Screenshot](bug-evidence/TC-SD-012-Product_Description_Wrong.png)

---

#### 4. BUG-NAVIGATION-004: "Reset App State" Fails to Reset Button Text
* **Test Case ID:** `TC-SD-062` (Step 6)
* **Module:** Navigation & Session | **Severity:** Major | **Priority:** High
* **Steps to Reproduce:**
  1. Log in to `https://www.saucedemo.com/`
  2. Click **Add to cart** on one or more products (button toggles to "Remove", cart badge shows count).
  3. Click the sidebar hamburger menu button.
  4. Click **Reset App State**.
  5. Close sidebar and inspect the cart badge and product buttons.
* **Expected Result:** Cart badge resets to 0 AND the product button toggles back from "Remove" to "Add to cart".
* **Actual Result:** Cart badge resets to 0, but the button text remains stuck on "Remove".

![BUG-NAVIGATION-004 Screenshot](bug-evidence/TC-SD-062-Remove_button_not_changed.png)

---

## 🛠️ Tools, Techniques & QA Skills Demonstrated

* **Test Management & Design:** Microsoft Excel (`.xlsx`), Google Sheets
* **Documentation & Reporting:** Microsoft Word (`.docx`), Markdown
* **Test Techniques:** Equivalence Partitioning (EP), Boundary Value Analysis (BVA), Error Guessing, Exploratory Testing
* **Defect Lifecycle Management:** IEEE 829-aligned defect classification (Severity, Priority, Root Cause, Status)
* **Traceability:** Bidirectional RTM mapping (Business Requirements ↔ Test Scenarios ↔ Test Cases)
* **Version Control:** Git & GitHub

---

## 🔍 How to Explore the Project Documents

Because GitHub displays plain-text and image files natively but offers raw download previews for Office files, here is how recruiters and evaluators can explore each artifact:

1. **Quick Overview:** Browse this `README.md` for complete data tables, defect logs, metrics, and screenshots without downloading anything.
2. **Granular Test Cases:** Download [`Test_Case_SauceDemo.xlsx`](Test_Case_SauceDemo.xlsx) to inspect all 63 test cases, precondition definitions, test steps, test data, and pass/fail execution markers.
3. **Defect Tracking Register:** Download [`Bug_Report_SauceDemo.xlsx`](Bug_Report_SauceDemo.xlsx) to view full reproduction steps, severity/priority matrices, and tester notes.
4. **Formal QA Documents:** Download the Word documents ([`Test_Plan_SauceDemo.docx`](Test_Plan_SauceDemo.docx), [`RTM_Requirement_Traceability_Matrix_SauceDemo.docx`](RTM_Requirement_Traceability_Matrix_SauceDemo.docx), [`Test_Summary_Report_SauceDemo.docx`](Test_Summary_Report_SauceDemo.docx)) to review industry-standard documentation standards and formal release criteria.

---

## 💡 Key Learnings & Future Roadmap

### Key Learnings from this Project
* **Value of Exploratory Testing:** Scripted test cases validate expected paths, but exploratory testing uncovered critical state bugs like `BUG-NAVIGATION-004` (state reset failure).
* **Power of Traceability (RTM):** Maintaining bidirectional traceability guarantees 100% test coverage and makes it easy to assess defect impact during regression cycles.
* **Defect Reproducibility:** Providing exact step-by-step reproduction instructions and visual screenshots significantly accelerates defect triage.

### Future Automation Roadmap (SDET Extension)
This manual test suite serves as the complete functional specification for building an automated test framework:
1. **Framework Architecture:** Page Object Model (POM) using **Selenium WebDriver + Java** or **Playwright + TypeScript**.
2. **Data-Driven Testing:** Utilizing Apache POI / JSON data providers to test multi-user scenarios (`standard_user`, `locked_out_user`, `problem_user`, `performance_glitch_user`).
3. **CI/CD Integration:** Automating regression execution via GitHub Actions on every pull request, publishing Allure test reports to GitHub Pages.

---

## 👨‍💻 Author & Professional Links

**Alok Kumar**  
🎓 **B.Tech in Computer Science and Engineering** (Class of 2026)  
🎯 **Aspiring QA Engineer | Manual Testing | Automation / SDET**  

* 🔗 **LinkedIn:** [https://www.linkedin.com/in/alokkr7722/](https://www.linkedin.com/in/alokkr7722/)  
* 🐙 **GitHub:** [https://github.com/Alok7722](https://github.com/Alok7722)  

---

*This project is part of my professional Software Testing portfolio demonstrating practical STLC execution, test design techniques, and defect analysis skills.*
