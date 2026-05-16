# 📊 Employee Request and Approval Management System using ServiceNow

## 📌 Project Overview

The Employee Request and Approval Management System is a ServiceNow-based application developed to streamline employee service request handling and approval processes. The system allows employees to submit requests and enables administrators to manage, track, and monitor requests efficiently using records, reports, and dashboard visualizations.

This project demonstrates end-to-end ServiceNow development including custom table creation, module creation, record management, report generation, and dashboard integration.



## 🛠️ Technologies Used

- ServiceNow Platform
- ServiceNow Studio
- Custom Tables
- Forms
- Modules
- Reports
- Dashboard
- Pie Chart Visualization



# 🗄️ Application Creation

### Application Name:
Smart Employee Request System

A custom ServiceNow application was created to manage employee requests and approval processes in a centralized platform.



# 📂 Modules Created

The following modules were created:

### Create Request
Allows users to submit employee requests.

### View Requests
Displays all employee request records.

### Reports
Used to generate request status reports.

### Dashboard
Displays visual analytics and reports.



# 📋 Custom Table Creation

### Table Name:
Employee Requests

The Employee Requests table was created to store employee request information.

### Fields Created

| Field Name | Type | Description |
|-------------|-------|-------------|
| Employee ID | String | Unique employee identifier |
| Employee Name | String | Name of employee |
| Request Type | Choice | Request category |
| Manager Approval | Choice | Approval status |
| Status | Choice | Approved / Open / Pending / Rejected |



# 📝 Record Creation

Sample employee request records were inserted into the Employee Requests table for testing and analysis.

Example records created:

| Employee Name | Request Type | Status |
|---------------|--------------|----------|
| Sathya | Laptop Request | Open |
| Poojitha | Software Access | Pending |
| Priya | ID Card Request | Approved |
| Rahul | Leave Request | Rejected |

These records were created to simulate real-world employee request and approval workflows.

The inserted records were used for:

- Testing employee request handling
- Updating request status
- Generating reports
- Creating dashboard visualizations
- Analyzing request distribution

The record data was further used to create the **Employee Request Status Report** and integrate it into the dashboard for real-time visualization.



# 📊 Report Creation

### Report Name:
Employee Request Status Report

### Report Type:
Pie Chart

### Configuration

- Data Source: Employee Requests
- Group By: Status
- Visualization Type: Pie Chart

### Purpose

The report displays employee request distribution based on status:

- Approved
- Open
- Pending
- Rejected

This helps monitor workflow and request activity.


# 📈 Dashboard Creation

### Dashboard Name:
Employee Request Dashboard

The dashboard was created to provide a visual representation of employee request analytics.

### Dashboard Features

- Request status visualization
- Pie Chart integration
- Interactive dashboard view
- Request monitoring


# 📸 screen shots

The following screenshots are included in the screen shots folder:

### Module View
Modules created in the ServiceNow application

File:
module_view.jpeg



### Table Structure
Employee Requests table fields and configuration

File:
table_structure.jpeg



### Pie Chart Report
Employee Request Status Report using Pie Chart visualization

File:
report_piechart.jpeg



### Dashboard
Employee Request Dashboard with request analytics

File:
dashboard.jpeg



# 🔄 Project Workflow

Employee submits request

↓

Request stored in Employee Requests table

↓

Admin reviews request

↓

Request status updated

↓

Reports generated

↓

Dashboard visualizes analytics


# 🎓 Learning Outcomes

Through this project I learned:

- ServiceNow application development
- Module creation
- Custom table creation
- Record management
- Report generation
- Dashboard integration
- Data visualization


# 📌 Project Status

✅ Completed Successfully


## 👩‍💻 Author

Paluru Sathya Poojitha


## ⭐ Conclusion

The Employee Request and Approval Management System successfully demonstrates a complete ServiceNow workflow from request creation to dashboard visualization. This project provides practical exposure to ServiceNow development and workflow management concepts.
