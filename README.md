# inFlow Inventory – Manual Testing Project

## 📌 Project Overview

This project focuses on **manual testing of the inFlow Inventory Management System**, an inventory management application that helps businesses maintain records digitally and manage the flow from purchasing products to selling them to customers.

The project primarily focuses on the **Sales Order module**.

---

## 🎯 Project Objectives

- Understand the workflow of the inFlow Inventory application.
- Identify and test functionalities of the Sales Order module.
- Design and execute test cases.
- Perform positive and negative testing.
- Verify expected and actual results.
- Identify and document defects.
- Assign appropriate severity and priority to identified defects.

---

## 🔄 Application Workflow

The overall application workflow is:

**Vendor → Purchase Order → Inventory → Sales Order → Customer**

### Sales Order Workflow

**Customer → Sales Order → Customer Details → Items → Quantity & Price → Discount/Tax → Total → Save → Pick → Pack → Ship → Invoice**

---

## 🧪 Testing Scope

The project focused on manual testing of the **Sales Order module**.

### Functionalities Covered

- Customer
- Contact
- Phone
- Attachment Button
- Sticky Note
- Close Button
- Search
- Quantity
- Unit Price
- Discount
- Subtotal
- Item
- Item Dialog Box
- Taxing Scheme
- Currency
- Remarks
- Customer Address
- Shipping
- Order #
- New Button
- Save Button
- Preview Button

---

## 🔍 Testing Activities

The following testing activities were performed:

- Test Case Design
- Test Case Review
- Functional Testing
- Positive Testing
- Negative Testing
- Input Validation Testing
- Test Case Execution
- Expected vs Actual Result Verification
- Defect Identification
- Defect Documentation
- Severity and Priority Classification

---

## 📋 Test Case Documentation

Test cases were prepared for the assigned functionalities and executed against the application.

The test case documentation includes information such as:

- Test Case ID
- Test Objective
- Preconditions
- Test Data
- Test Steps
- Expected Result
- Actual Result
- Test Status

The complete test case documentation is available in:

📁 **[Test Cases](Test-Cases/TEST_CASES.xlsx)**

---

## 🐛 Defect Reporting

During test execution, defects were identified and documented.

The defect reports include details such as:

- Defect ID
- Functionality
- Requirement
- Actual Result
- Severity
- Priority

### Defects Identified

#### 1. Phone Field Validation

**Requirement:** Phone field should accept only numeric characters.

**Actual Result:** Phone field accepted non-numeric characters.

**Severity:** High  
**Priority:** High

#### 2. Remark Field Validation

**Requirement:** Remark field should not accept only numbers.

**Actual Result:** Remark field accepted only numbers and saved successfully.

**Severity:** Low  
**Priority:** Low

#### 3. Order # Field Validation

**Requirement:** Order # field should not be null and should not accept spaces.

**Actual Result:** Order # field accepted values with spaces.

**Severity:** Low  
**Priority:** High

The complete defect documentation is available in:

📁 **[Defect Reports](Defect-Reports/Defect_Report.xlsx)**

---

## 👨‍💻 My Role

### Team Lead – Chintamani Adak

Responsibilities:

- Assigned functionalities to team members for test case preparation.
- Reviewed test cases prepared by team members.
- Prepared test cases for assigned functionalities.
- Participated in test case execution.
- Prepared test execution and defect reports for assigned functionalities.
- Coordinated testing activities within the team.

### My Assigned Functionalities

- Search
- Quantity
- Unit Price
- Discount
- Subtotal

---

## 👥 Team Members

| Name | Role |
|---|---|
| Chintamani Adak | Team Lead |
| Neha Rajiwade | Team Member |
| Indrajeet Mali | Team Member |
| Rajvardhan Gaikwad | Team Member |

---

## 📁 Project Documentation

```text
inflow-inventory-manual-testing/
│
├── README.md
│
├── Test-Cases/
│   └── TEST_CASES.xlsx
│
└── Defect-Reports/
    └── Defect_Report.xlsx
