# Automated-Network-Request-Management-in-ServiceNow
Automated Network Request Management is a ServiceNow application that streamlines network request submission, approval, task assignment, and fulfillment. It automates workflows using Service Catalog, Flow Designer, and notifications, enabling faster processing, real-time tracking, improved efficiency, and audit-ready request management.


## Overview

Automated Network Request Management is a ServiceNow application designed to simplify and automate the processing of network-related requests within an organization. It provides a centralized platform where users can request network access, firewall changes, VPN access, device configuration, and other network services through the Service Catalog.

The application automates request validation, approval workflows, task assignment, notifications, and status tracking, reducing manual effort while ensuring compliance and transparency throughout the request lifecycle.

---

## Features

- Network Request Service Catalog Item
- Dynamic Form Fields using Client Scripts
- Automated Approval Workflow
- Role-Based Access Control (RBAC)
- Flow Designer Automation
- Automatic Task Creation
- Email Notifications
- SLA Tracking
- Real-Time Request Status Updates
- Reports and Dashboards
- Audit-Ready Request History

---

## Technologies Used

- ServiceNow App Engine
- Service Catalog
- Flow Designer
- Client Scripts
- Business Rules
- UI Policies
- Notifications
- Roles & Groups
- Reports
- Dashboards

---

## Project Workflow

### Step 1 – Request Submission

Users submit a network request through the Service Portal or Service Catalog by entering:

- Request Type
- Access Level
- Device Information
- Business Justification
- Priority

---

### Step 2 – Request Validation

The system validates the submitted information and checks mandatory fields before processing the request.

---

### Step 3 – Approval Process

Based on request type and priority, the request is routed to the designated approver.

Approvers can:

- Approve
- Reject

Automatic email notifications are generated during this stage.

---

### Step 4 – Task Creation

Once approved, ServiceNow automatically creates fulfillment tasks and assigns them to the appropriate Network Team.

---

### Step 5 – Task Fulfillment

Network engineers:

- Process assigned tasks
- Update work notes
- Configure requested network changes
- Complete the assigned work

---

### Step 6 – Status Tracking

The request status updates automatically throughout the lifecycle.

Possible statuses include:

- New
- Awaiting Approval
- Approved
- In Progress
- Completed
- Rejected

---

### Step 7 – Notifications

Email notifications are automatically sent for:

- Request Submitted
- Approval Pending
- Approved
- Rejected
- Task Assigned
- Request Completed

---

### Step 8 – Reporting

Administrators can monitor:

- Pending Requests
- Approved Requests
- Rejected Requests
- SLA Performance
- Team Workload
- Completion Statistics

---

## User Roles

### Requester

- Submit network requests
- View request status
- Receive notifications

### Approver

- Review requests
- Approve or Reject requests
- Track pending approvals

### Network Team

- Receive assigned fulfillment tasks
- Update work notes
- Complete network changes

### Administrator

- Manage users and roles
- Configure workflows
- Generate reports
- Monitor SLAs
- Maintain application

---

## ServiceNow Components Used

| Component | Purpose |
|-----------|----------|
| Service Catalog | Request Submission |
| Client Scripts | Dynamic Form Behavior |
| UI Policies | Field Visibility |
| Flow Designer | Workflow Automation |
| Business Rules | Backend Logic |
| Notifications | Email Alerts |
| Approval Engine | Approval Process |
| Task Management | Fulfillment Tasks |
| Reports | Analytics |
| Dashboards | Monitoring |

---

## Request Lifecycle

```text
User

↓

Submit Network Request

↓

Validation

↓

Approval Required

↓

Approve?

├── No → Rejected

└── Yes

↓

Create Fulfillment Task

↓

Assign Network Team

↓

Network Configuration

↓

Task Completed

↓

Request Closed

↓

Notification Sent
```

---

## Key Benefits

- Eliminates manual request handling
- Faster approval process
- Improved operational efficiency
- Automatic task assignment
- Real-time request tracking
- Increased transparency
- Better SLA compliance
- Audit-ready records
- Scalable workflow automation
- Reduced administrative effort

---

## Future Enhancements

- Multi-Level Approval Workflow
- Integration with Active Directory
- Integration with Network Monitoring Tools
- AI-Based Request Prioritization
- Chatbot Integration
- Mobile Approval Support
- Predictive SLA Monitoring
- REST API Integration
- Performance Analytics Dashboard

---

## Installation

1. Log in to the ServiceNow instance.
2. Create the application using App Engine Studio.
3. Configure the Service Catalog Item.
4. Create user groups and roles.
5. Configure Client Scripts and UI Policies.
6. Develop Flow Designer workflows.
7. Configure Business Rules.
8. Set up Notifications.
9. Create Reports and Dashboards.
10. Test the complete request lifecycle.

---

## Project Structure

```
Automated-Network-Request-Management/

│

├── Service Catalog

├── Client Scripts

├── UI Policies

├── Flow Designer

├── Business Rules

├── Notifications

├── Roles & Groups

├── Reports

├── Dashboards

└── Documentation
```

---


## Skills Demonstrated

- ServiceNow Administration
- Application Development
- Workflow Automation
- Service Catalog Development
- Flow Designer
- Client Scripting
- Business Rules
- Notification Configuration
- Access Control
- Reporting & Dashboards
