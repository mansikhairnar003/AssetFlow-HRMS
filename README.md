# AssetFlow

A complete Asset Request & Allocation Management System built on Salesforce Platform.

## Project Overview

AssetFlow automates the complete asset lifecycle from Employee Request to Asset Allocation and Return. No manual tracking needed — everything is automated!

## Asset Lifecycle

```
Asset Request → Approval → Asset Allocation → Return → Asset Available
```

## Key Features

- Automated Flow 1 — Asset Allocation record auto-created and Asset Status updated when request is approved
- Automated Flow 2 — Asset Status auto-reset to Available when allocation is marked as returned
- Asset Lookup on Request — Approver selects the exact asset to allocate from existing inventory
- Auto-Numbered Asset Records — Every asset gets a unique identifier (e.g. AST-0001)
- Approval Process — Structured approval workflow for asset requests
- Validation Rules — Data quality control on Purchase Date and Return Date
- Custom Reports and Dashboards — Real-time asset allocation insights
- Custom Objects and Relationships — Asset, Asset Request, and Asset Allocation linked via lookups
- Role-based Security Model — Controlled access for Employees and Approvers

## Screenshots

### AssetFlow Home Page
![Home](Screenshots/Home_page.png)

### Object Model Overview
![Objects](Screenshots/Objects.png)

### Asset Fields
![Asset Fields](Screenshots/Asset_Fields.png)

### Asset Records List
![Asset Records List](Screenshots/Asset_Records_List.png)

### Asset Record Detail
![Asset Record Detail](Screenshots/Asset_Record_Detail.png)

### Employees List
![Employees List](Screenshots/Employees_List.png)

### Employee Record — Related Lists
![Employee Record Related](Screenshots/Employee_Record_Related.png)

### Asset Request Fields
![Asset Request Fields](Screenshots/Asset_Request_Fields.png)

### Asset Request List
![Asset Request List](Screenshots/Asset_Request_List.png)

### Asset Request Record Detail
![Asset Request Record Detail](Screenshots/Asset_Request_Record_Detail.png)

### Submit for Approval
![Submit for Approval](Screenshots/SubmitforApproval.png)

### Approval Process Setup
![Approval Process](Screenshots/Approval_Process.png)

### Approval Page
![Approval Page](Screenshots/Approval_Page.png)

### Flow 1 — Create Allocation on Approval
![Flow1](Screenshots/Flow1.png)

### Asset Allocation Fields
![Asset Allocation Fields](Screenshots/Asset_Allocation_Fields.png)

### Asset Allocations List
![Asset Allocations List](Screenshots/Asset_Allocations_List.png)

### Asset Allocation Record Detail
![Asset Allocation Record Detail](Screenshots/Asset_Allocation_Record_Detail.png)

### Flow 2 — Update Asset Status on Return
![Flow2](Screenshots/Flow2.png)

### Purchased Date Validation
![Purchased Date Validation](Screenshots/Purchased_Date_Validation1.png)

### Validation Error — Example 1
![Validation Error 1](Screenshots/Validation1.png)

### Return Date Validation
![Return Date Validation](Screenshots/Return_Date_Validation2.png)

### Validation Error — Example 2
![Validation Error 2](Screenshots/Validation2.png)

### Reports
![Reports](Screenshots/Reports.png)

### Dashboards
![Dashboards](Screenshots/Dashboards.png)

## Tech Stack

- Salesforce Flow Builder — Record Triggered Flows
- Approval Process
- Validation Rules
- Custom Objects and Relationships
- Reports and Dashboards
- Lightning App Builder
- Security Model — Profiles and Field-Level Security

## Author

**Mansi Khairnar**
[LinkedIn](https://www.linkedin.com/in/mansi-khairnar-m310200k2) | [Trailhead](https://www.salesforce.com/trailblazer/mansi-khairnar)
