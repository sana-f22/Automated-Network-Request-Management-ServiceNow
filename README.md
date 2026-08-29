# Automated Network Request Management in ServiceNow

## Project Overview

Automated Network Request Management is a ServiceNow Service Catalog based solution developed to automate the complete lifecycle of network-related service requests.

The system provides structured request submission, mandatory field validation, approval routing, Network Task creation, status tracking, fulfilment and email notifications.

## Problem Statement

Manual and inconsistent handling of network requests can lead to delays, incomplete information, approval gaps and poor visibility into request status.

This project provides a structured and automated process for managing network service requests.

## Objectives

- Provide a structured entry point for network requests
- Validate mandatory information
- Automatically populate requester information
- Route requests for approval
- Automatically create Network Tasks
- Track request and task status
- Send email notifications
- Maintain data integrity
- Provide role-based access control

## Technologies Used

- ServiceNow Service Catalog
- Service Portal
- Catalog Variables
- Variable Sets
- Flow Designer
- Approvals
- Custom Tables
- Catalog Client Scripts
- UI Policies
- Business Rules
- ACLs
- Email Notifications
- Update Sets

## System Workflow

Service Portal  
↓  
Network Request  
↓  
REQ / RITM  
↓  
Network Database  
↓  
Approval  
↓  
Network Task  
↓  
Task Completion  
↓  
Status Update  
↓  
Email Notification

## Custom Tables

### u_network_database

Stores structured network request information captured from the catalog form.

### u_network_task

Stores task-level information related to network request fulfilment.

## Main Features

- Network Request Catalog Item
- Requester Information Variable Set
- Mandatory field validation
- Dynamic field behaviour
- Automatic requester population
- Dynamic approval routing
- Network Task creation
- Email notifications
- Request status tracking
- Role-based security
- ACL configuration
- End-to-end testing

## Approval Scenarios

- Manager Approval
- Network Security Approval
- Group Approval

## Flow Designer

The Network Request flow automates the request lifecycle.

The flow:

1. Retrieves catalog variables
2. Creates the Network Database record
3. Sends a notification
4. Requests approval
5. Handles approval and rejection
6. Creates the Network Task after approval
7. Updates request and task status
8. Sends completion notifications

## Project Outcome

The completed system provides an automated and structured approach for handling network service requests.

It reduces manual effort, improves request tracking, provides consistent approval handling and maintains better data integrity.

## Documentation

Detailed project documentation is available in the `Documentation` folder.

## Screenshots

Implementation screenshots are available in the `Screenshots` folder.

## Demo

The project demonstration video link is available in the `Demo` folder.

## Future Scope

- Cisco DNA Centre integration
- Ansible integration
- Auto-provisioning
- ServiceNow Integration Hub orchestration
- Reporting dashboards
- Expansion to additional IT services
