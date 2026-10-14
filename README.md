# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group (NMG), a fictional healthcare organization with over 200 employees, experienced identity and access management challenges due to mismanagement by its previous Managed Service Provider (MSP). The existing environment lacked a standardized Active Directory organizational structure, consistent security group assignments, and clearly defined access controls. Manual user provisioning processes resulted in inconsistent account configurations, incorrect departmental assignments, and unnecessary access issues. These weaknesses created operational inefficiencies, increased the risk of unauthorized access to sensitive healthcare information, and introduced potential HIPAA compliance concerns.

## Solution Overview
I built a Windows Server Active Directory lab environment from scratch, establishing the NMG.com domain to simulate a centralized identity management infrastructure. I designed a structured Active Directory environment with four departmental Organizational Units (OUs): Finance, Human Resources, IT, and Operations. I implemented four corresponding security groups using a flat Role-Based Access Control (RBAC) model, organizing users by department to support consistent access assignments and the principle of least privilege. I provisioned 15 user accounts using standardized naming conventions, User Principal Names (UPNs), department attributes, and appropriate security group memberships. To demonstrate troubleshooting and access management, I investigated and corrected a simulated support ticket involving incorrect OU placement and security group membership. These improvements established a more organized, manageable identity environment while supporting secure provisioning practices and consistent access administration.

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
