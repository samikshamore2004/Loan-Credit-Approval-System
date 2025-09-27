[View Project PDF](https://github.com/samikshamore2004/Loan-Credit-Approval-System/blob/main/Project%20Title_Loan%20%26%20Credit%20Approval%20System%20(3).pdf)
# 💰Loan & Credit Approval System (Salesforce)

## 📌Overview

This Salesforce based project automates the end-to-end loan approval process for a financial institution. It simplifies loan application handling, calculates EMIs, flags risky loans, and provides an intuitive user interface for both loan officers and managers.

The system combines Salesforce declarative tools (Flows, Validation Rules, Process Builder, Workflow Rules) with Apex programming and Lightning Web Components to ensure efficiency, accuracy, and a user-friendly experience.


---

## ✨ Key Features

- **Loan EMI Calculation:** Automatic calculation of monthly EMI based on loan amount, interest rate, and tenure using Apex.
  
- **Risk Management:** Flags risky loans based on amount and credit score and updates the Eligibility Result field.
  
- **Process Automation:** 
-Validation rules to enforce correct loan details.
-Workflow rules and process builder to trigger notifications and auto-reject loans under certain conditions.
-Flows to auto-populate EMI and approval dates.

- **User Interface:**
- Custom Lightning App: Loan & Credit Approval App.
-Customized record pages for Loan Applications showing EMI, Risky Flags, and related payments or credit checks.
-Custom tabs for all key objects: Loan Application, Payment, Credit Check, Loan Product.

- **Reporting & Dashboards:** 
-Reports created for loan pipelines, portfolio by type, approval times, and delinquent payments.
-Loan Management Dashboard consolidates all key reports.

- **Duplicate Management:** Matching rules and duplicate rules implemented to prevent duplicate contact records.

---

## 🧩 Salesforce Components Included

- **Objects**: Loan_Application__c, Loan_Product__c, Payment__c, Credit_Check__c, and others.
- **Layouts**: Custom layouts for each object and user profile.
- **Profiles & Permission Sets**: Access management for different roles (Loan Officer, Branch Manager, Admin, etc.).
- **Apex Classes & Triggers**: EMI_Calculation – Calculates monthly EMI. LoanRiskHandler – Flags risky loans.
- **Reports & Dashboards**: Ready-to-use reports and dashboards for loan monitoring.
- **Flows:** Auto-fill EMI and approval dates.

- **Validation & Workflow Rules:** Ensure data integrity and automate notifications.

- **Lightning Web Components:** Display record-specific loan information dynamically.
- **VS Code Project Files**: Salesforce DX project structure with metadata, config files, and scripts.

---

## 🚀 Usage
1. Open the Salesforce Org.
2. Navigate to the Loan & Credit Approval App.
3. Create a new loan application. Fields like EMI and approval date will populate automatically.
4. Risky loans will be flagged in the Eligibility Result field.
5. Managers can view related payments and credit checks on the record page.
6. Reports and dashboard provide insights into loan status and approvals.

---
## 🛠️ Tech Stack
- Salesforce Platform (Lightning, Apex, Flows, Validation Rules, Process Builder)
- Lightning Web Components (LWC)
- VS Code with Salesforce SFDX for development and metadata deployment
---
## 👤 Author
- Samiksha More
