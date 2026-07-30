# online-Bookstore-QA-Testing
# Online Book Store Platform — QA Testing & Management

This repository contains the Quality Assurance (QA) manual testing documentation and execution deliverables for the **Online Book Store Platform** (Assignment 2).

---

## 👤 Project Information
* **Student Name:** Lamaan Ali Bukhsh
* **Role:** Quality Assurance Intern
* **Project:** Online Book Store QA Assignment
* **Repository Scope:** Test Plan, Test Cases, and Test Execution Reporting

---

## 📁 Repository Deliverables

| Deliverable File | File Format | Description |
| :--- | :--- | :--- |
| **`TestPlan_OnlineBookstore.docx`** | Word (`.docx`) | High-level testing strategy covering scope, environment, testing types (Smoke, Negative, Regression), and criteria. |
| **`TestCases_OnlineBookstore.csv`** | CSV (`.csv`) | Test cases mapped to Functional Requirements (FR-01, FR-02, FR-03) with test steps, expected results, and priority tags. |
| **`TestRunReport_OnlineBookstore.pdf`** | PDF (`.pdf`) | Sprint 1 execution summary report detailing test execution statuses (75% Pass Rate). |

---

## 🛠️ Testing Tools & Reporting Note

* **Test Management Tool:** Testworthy
* **Documentation Tools:** Microsoft Word, CSV Export, Python / Gemini

> **Note on Test Execution Report Format:**  
> When exporting the executed test run results from Testworthy, the platform provided the output in raw `.json` format (`test-run-511-results.json`). To fulfill the assignment requirement for a formatted PDF execution report (`TestRunReport_OnlineBookstore.pdf`), the exported JSON payload was processed via **Gemini / Python scripts** to generate the final, professionally styled PDF report included in this repository.

---

## 📊 Summary of Test Execution Results

* **Total Executed Tests:** 4
* **Passed:** 3 (75%)
* **Blocked:** 1 (25% — *Payment Gateway Sandbox Staging Downtime*)
* **Failed:** 0 (0%)
