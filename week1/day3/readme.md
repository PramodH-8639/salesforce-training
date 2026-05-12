# Day 3 - Data Modeling

## 1. Difference Between App, Object, Record, and Field

An App is a collection of related tools and objects used for a specific purpose. An Object is like a table that stores data. A Record is a single row of information inside an object. A Field is a single piece of information in a record such as name or age.

---

## 2. Standard vs Custom Objects

Standard Objects are already provided by Salesforce for common business needs like Account and Contact. Custom Objects are created by users according to their own requirements such as Student or Course.

---

## 3. College Data Model

The college data model contains objects like Student, Course, and Faculty. Students enroll in courses, and faculty members teach courses.

### Diagram

Student → Course ← Faculty

---

## 4. Formula Fields

Formula fields automatically calculate values using other fields. For example, Total Fees can be calculated using Tuition Fees and Hostel Fees.

Tuition_Fees + Hostel_Fees
5. Validation Rules
Validation rules prevent incorrect data from being saved. For example, a student age should not be less than 16.
Example:
Plain text
Age < 16
6. Reflection
Structured enterprise data is important because it keeps information organized, reduces errors, and helps businesses work more efficiently.<img width="1648" height="636" alt="Screenshot 2026-05-12 192421" src="https://github.com/user-attachments/assets/31da236a-183f-4781-8ecd-4e6def37ce9c" />
<img width="1615" height="621" alt="Screenshot 2026-05-12 192352" src="https://github.com/user-attachments/assets/4b26a89d-b2cf-4003-b10e-f2f63cfe1f8f" />

