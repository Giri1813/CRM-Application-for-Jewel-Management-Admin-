# CRM Application for Jewel Management (Admin)

## 📌 Project Overview
The **CRM Application for Jewel Management** is a Salesforce Admin–based application designed to manage jewelry business operations efficiently.  
This project covers customer management, item tracking (Gold & Silver), pricing, billing, automation, reports, dashboards, and role-based access.

The application is built using **Salesforce Lightning Experience** with complete admin configuration.

---

## 🎯 Project Objectives
- Manage Jewel Customers, Items, Orders, Prices, and Billings
- Implement role-based access using Profiles, Roles, and Permission Sets
- Automate email notifications using Salesforce Flows
- Generate Reports and Dashboards for business insights
- Apply validation rules for data accuracy

---

## 🛠️ Technologies Used
- Salesforce Lightning Experience
- Salesforce Admin Tools
- Salesforce Reports & Dashboards
- Salesforce Flow Builder
- Custom Objects & Fields

---

## 📂 Project Modules

### 1️⃣ Salesforce Setup
- Custom Objects creation
- Tabs configuration
- Lightning App creation (Jewelry Inventory System)

---

### 2️⃣ Custom Objects
- **Jewel Customer**
- **Item**
- **Price**
- **Customer Order**
- **Billing**

Each object is configured with:
- Custom fields
- Lookup relationships
- Validation rules
- Record types (Gold / Silver)

---

### 3️⃣ Fields Configuration
- Text, Number, Currency, Picklist fields
- Cross-object formula fields
- Required field validations

---

### 4️⃣ Tabs & Lightning App
- Created custom tabs for all objects
- Added tabs to **Jewelry Inventory System** app
- Enabled tab visibility for required profiles

---

### 5️⃣ Profiles & Roles
#### Profiles
- System Administrator
- Gold Smith
- Worker

#### Roles
- Gold Smith
- Worker (Reports to Gold Smith)

---

### 6️⃣ Users
- Created users with different profiles and roles
- Assigned permission sets for extended access

---

### 7️⃣ Permission Sets
- Created permission set for Worker
- Assigned record type access and object permissions

---

### 8️⃣ Page Layouts & Record Types
- Separate page layouts for:
  - Gold Items
  - Silver Items
- Record Types:
  - Gold
  - Silver
- Assigned layouts per profile

---

### 9️⃣ Validation Rules
- Postal code validation
- Mandatory field validation for objects
- Prevents incomplete and invalid data entry

---

### 🔟 Reports
Created multiple reports including:
- Item Report
- Jewel Customer Report
- Items with Customer Orders
- Billing Reports

Reports are used for tracking sales, customers, and billing details.

---

### 1️⃣1️⃣ Dashboards
- Created dashboards using reports
- Visual representation of business data
- Multiple components added using charts and tables

---

### 1️⃣2️⃣ Salesforce Flow (Automation)
- Record-Triggered Flow on **Billing**
- Trigger: Record Created or Updated
- Automatically sends email notification to customers
- Uses Email Action and Text Template
- Flow activated successfully

---

## 📸 Project Deliverables
- Salesforce configuration screenshots
- Reports and dashboards screenshots
- Flow setup screenshots
- Project documentation
- Demo video (if available)

---

## 📈 Project Outcome
- Successfully built an end-to-end Salesforce Admin CRM application
- Implemented automation, security, and reporting
- Project meets all SmartInternz milestone requirements

---

## 👤 Author
**Chunchu Girija Shankar**  
B.Tech – Computer Science (AI & ML)  
Salesforce Admin Project

---

## 🏁 Conclusion
This project demonstrates hands-on experience in Salesforce Admin concepts including object modeling, security, automation, and analytics. It is suitable for real-world CRM use cases in the jewelry industry.


