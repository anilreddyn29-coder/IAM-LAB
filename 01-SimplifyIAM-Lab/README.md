
# SimplifyIAM - Identity Lifecycle Management Lab

## Project Overview

This hands-on lab demonstrates automated Identity and Access Management (IAM) using SimplifyHR, midPoint and OpenLDAP.

The lab covers employee onboarding, account provisioning, employee termination and automated account deactivation.

## Technologies Used

- SimplifyHR - HR Management System
- midPoint - Identity Management Platform
- OpenLDAP - Directory Service

## Lab Implementation

### 1. Employee Onboarding (Joiner)

- Created a new employee in SimplifyHR.
- Employee information was synchronized with midPoint.
- midPoint automatically created the employee's LDAP account.
- Verified account provisioning.

### 2. Employee Termination (Leaver)

- Terminated an employee in SimplifyHR.
- midPoint detected the identity status change.
- The LDAP account was automatically disabled.
- The account was moved to the `ou=inactive` organizational unit.

## IAM Concepts Demonstrated

- Identity Lifecycle Management
- Joiner and Leaver Processes
- Automated User Provisioning
- Account Deactivation
- Identity Synchronization
- HR-driven Identity Management

## Learning Outcomes

- Understood HR-driven identity management.
- Practiced automated account provisioning.
- Learned identity synchronization between systems.
- Understood employee termination workflows.
- Explored automated account deactivation.

## Project Author

Anil Kumar Reddy
