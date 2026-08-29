# 🏦 ParaBank Online Banking – SQA Testing Suite

## 📌 Project Overview
This repository contains a comprehensive **Software Quality Assurance (SQA) testing suite** for the [ParaBank Online Banking](https://parabank.parasoft.com/parabank/index.htm) demo application. The project demonstrates full-lifecycle manual testing, decision-driven test design, backend REST API validation using Postman, defect tracking, and executive summary reporting.

---

## 🛠️ Tools & Technologies Used
* **Test Management & Documentation:** Microsoft Excel / WPS Office
* **API Testing:** Postman (HTTP GET/POST requests, JSON header configuration)
* **Web Diagnostic Tools:** Chrome Developer Tools (Network Tab inspection)
* **Design Techniques:** Equivalence Partitioning (EP), Boundary Value Analysis (BVA), Decision Tables

---

## 📊 Testing Coverage & Modules
The test suite covers core banking functionality across 8 key modules:
1. **User Authentication:** Registration, Login, Session Persistence
2. **Account Management:** Open New Account, Account Overview, Activity Details
3. **Financial Transactions:** Transfer Funds, Bill Pay
4. **Credit & Loans:** Request Loan Application Processing
5. **Search & Diagnostics:** Find Transactions by Amount, Date, and ID
6. **Customer Services:** Contact Info Updates, Admin Services

---

## 📂 Repository Structure
* **`ParaBank.xlsx`**: Master Workbook (Scenarios, Cases, API Log, Bugs, Summary)
* **`README.md`**: Project Overview & Execution Summary

---

## 📑 Workbook Layout & Tabs
* **`TEST SCENARIO`:** High-level operational coverage mapping end-to-end user journeys.
* **`DECISION TABLE`:** Combinatorial logic tables covering multi-condition validation rules.
* **`TEST CASES`:** 28 detailed manual test scripts with prerequisites, steps, expected vs. actual results, and pass/fail statuses.
* **`API TESTING`:** REST endpoint execution log detailing HTTP methods, parameters, status codes (`200 OK`, `405 Method Not Allowed`), and payload responses.
* **`API EVIDENCE`:** Clean execution screenshots verifying Postman JSON responses.
* **`BUG REPORT`:** Standardized defect logging capturing severity, priority, reproduction steps, and expected behavior.
* **`TEST SUMMARY SHEET`:** Metric breakdown detailing total execution counts, pass rates, tool usage, and project sign-off status.

---

## 🚀 Key Highlights & QA Best Practices Applied
* **Independent Endpoint Verification:** Differentiated frontend UI routes (`index.htm`) from backend REST APIs (`/services/bank/login/...`).
* **Header Manipulation:** Configured `Accept: application/json` headers in Postman to validate structured JSON responses.
* **Defect Linkage:** Maintained 1:1 traceability between failed test cases and defect tracking entries.
* **Clean Data Practices:** Applied strict masking of personal credentials and tokens in documentation assets.

---

## 👤 Author
**Ali Jan Anwar Samejo**  
*Software Quality Assurance (SQA) Engineer*  
*Specializations:* Manual, API, Database , and Performance Testing
