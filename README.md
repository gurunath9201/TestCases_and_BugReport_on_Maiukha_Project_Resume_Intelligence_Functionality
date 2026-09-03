<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=MAIUKHA.COM;Resume+Intelligence;Functional+Test+Suite&font=Fira%20Code&center=true&width=440&height=45&color=0366d6&vCenter=true&size=22" />
</p>

<div align="center">

![Static Badge](https://img.shields.io/badge/Status-Complete-brightgreen)
![Static Badge](https://img.shields.io/badge/Test_Cases-112-blue)
![Static Badge](https://img.shields.io/badge/Bugs_Found-5-red)
![Static Badge](https://img.shields.io/badge/Pass_Rate-93.75%25-brightgreen)

</div>

---

## 🚀 Project Overview
This repository contains the comprehensive **functional test suite** for the Resume Intelligence module of the MAIUKHA platform. The testing covers critical user journeys, including Account Registration, Sign-In, Resume Upload (with ATS analysis), and the Resume Builder & AI Studio.

The objective was to validate the entire resume workflow, from user creation to receiving AI-powered recommendations, and to identify any functional or UI discrepancies.

## ✨ Key Features Tested
- **User Authentication:** Registration, Login, Password Reset, and Social Logins (Google/LinkedIn).
- **ATS Resume Analysis:** Uploading multiple formats (PDF, DOCX, TXT, etc.), processing, and generating an ATS score.
- **AI-Powered Feedback:** Validation of the "AI Action Plan & Recommendations" and the "AI Suggestion Box" in the builder.
- **Resume Builder:** A fully interactive, tab-based builder with real-time "Live Preview" and an "AI Auto-Generate Resume" feature.
- **Resume History:** Tracking and persistence of uploaded resumes.

---

## 📊 Test Results at a Glance
The testing effort resulted in a high pass rate with critical bugs identified in the core workflow.

<p align="center">
  <img src="https://quickchart.io/chart?c=%7Btype%3A'doughnut'%2Cdata%3A%7Blabels%3A%5B'Passed'%2C'Failed'%5D%2Cdatasets%3A%5B%7Bdata%3A%5B105%2C7%5D%2CbackgroundColor%3A%5B'%2336A2EB'%2C'%23FF6384'%5D%7D%5D%7D%7D" alt="Test Results Chart" width="300" height="300"/>
</p>

- **Total Test Cases Executed:** 112
- **Passed:** 105 (93.75%)
- **Failed:** 7 (6.25%)

---

## 🐞 Summary of Critical Bugs
Below are the most impactful bugs discovered during the testing cycle.

| Bug ID | Module | Severity | Summary |
| :--- | :--- | :--- | :--- |
| **BUG-001** | Upload Resume | High | ATS score and recommendations are displayed **before uploading a resume**. |
| **BUG-002** | Upload Resume | High | Resume processing **gets stuck at 90%**, causing significant delays. |
| **BUG-003** | Resume History | High | Uploaded resumes and ATS scores **disappear after a page refresh**. |
| **BUG-004** | Resume Builder | Medium | **Inconsistent theme toggling** leaves some UI elements in the wrong theme with low contrast. |
| **BUG-005** | Resume Builder | Medium | **Data is lost** on accidental page refresh with no warning or auto-save. |

---

## 🛠️ Technology Stack
The testing utilized the following tools and frameworks:
- **Test Management:** Manual test cases were documented and executed.
- **Defect Tracking:** Bugs were tracked with unique IDs, priorities, and severity levels.
- **Browser Testing:** Chrome, Edge, and Firefox were used for cross-browser validation.

---

## 🧪 Test Coverage Highlights
The test suite focused on high-impact areas:

- **AI Hallucination Checks:** Validated that AI suggestions are based solely on the provided resume data and do not fabricate experience or skills.
- **Resume Builder Logic:** Tested the auto-generation of resumes and real-time preview updates.
- **Performance:** Upload and processing times were measured to ensure a reasonable user experience.

---

## 📄 How to Use This Report
1.  **For Developers:** Review the `Bug Report` tab for detailed steps to reproduce and resolve the identified issues.
2.  **For QA/Testers:** Use the `Test Cases` tab as a baseline for future regression testing.
3.  **For Stakeholders:** The summary provides a clear overview of the current application health.

---
<div align="center">
Created By - Gurunath Mule
</div>
