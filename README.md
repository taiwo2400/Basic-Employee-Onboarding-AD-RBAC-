# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group (NMG), a fictional healthcare organization with over 200 employees, faced identity and access management challenges due to mismanagement by its previous MSP. The environment lacked standardized Active Directory structures, consistent access controls, and documented user provisioning processes. These gaps created operational inefficiencies, increased the risk of unauthorized access, and raised potential HIPAA compliance concerns.

## Solution Overview
I built the NMG.com Active Directory domain on Windows Server and established four departmental Organizational Units: Finance, HR, IT, and Operations. I created corresponding security groups to establish a flat Role-Based Access Control (RBAC) structure supporting least-privilege principles. I provisioned 15 user accounts with standardized naming conventions, attributes, and departmental group memberships. I also investigated and corrected a simulated IAM incident involving incorrect OU placement and security group membership, demonstrating structured troubleshooting and access administration.

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
* Built NMG.com domain from scratch using Windows Server, configured Active Directory Domain Services (AD DS), and validated the domain controller's functionality through diagnostic testing.
* Designed and implemented a department-based Active Directory structure, creating four Organizational Units and four corresponding security groups to support a flat RBAC model, organized identity management, and least-privilege access principles.
* Provisioned 15 standardized user accounts and resolved a simulated IAM support incident (NMG-0047) by investigating incorrect OU placement and security group membership, applying the necessary corrections, and documenting the resolution.
