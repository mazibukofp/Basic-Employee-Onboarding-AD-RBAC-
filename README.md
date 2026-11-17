# Basic-Employee-Onboarding-AD-RBAC-

## Problem Statement
This project is about a fictional company called Northstar Medical Group, whose Active Directory had become chaotic and disorganized because of mismanagement by previous managed service providers (MSPs). The system lacked structure, and employees were added manually. Permissions were inconsistent: some employees had more access than they needed, while others had less than they should. This created significant security risk and jeopardized the company’s HIPAA compliance.
## Solution Overview
I started by creating a proper Active Directory domain, NMG.com. I then created Organizational Units (OUs) for four departments: Finance, HR, IT, and Operations. This structure is important because every user is identified by the department they belong to, which makes it easy to organize users by the work they do. I also created security groups and configured them so that when users are added to their department, they automatically receive access to what that department needs and nothing more

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Resolved my first incident ticket were I troubleshooted , applied solution and documented the report on the incident.



