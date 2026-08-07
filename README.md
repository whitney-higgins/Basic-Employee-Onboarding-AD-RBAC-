# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group (fictional) relied on a managed service provider to handle their IT infrastructure. As the company grew to 200+ employees, the MSP's mismanagement resulted in a disorganized Active Directory. User accounts weren't organized into Organizational Units, and RBAC. Some users had access to sensitive resources they didn't need, while others couldn't access what they needed. This inconsistency put sensitive resources at risk and could have led to NMG violating HIPAA requirements. 

## Solution Overview
* I built an NMG.com Active Directory domain and created OUs based on departments. I implemented RBAC by creating security groups and assigning users to those groups based on their roles. I ensured users have access to resources specific to their job roles.

## Video Walkthrough
[AD Domain Walkthrough](https://www.loom.com/share/e79711293549415fb4ec2dfb619b78aa)

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
