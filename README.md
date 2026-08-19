# Basic-Employee-Onboarding-AD-RBAC-
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.

# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
At NMG users were provisioned manually with no designation system. No OU structure was established, and group memberships were inconsistently assigned across users. These issues create a HIPAA compliance exposure for a 200+ employee healthcare organization.

## Solution Overview
Built the NMG.com domain on Windows Server and designed a department-based OU structure containing four business units. Implemented Role-Based Access Control using security groups linked to each department. Equipped 15 users with standardized designation systems and attribute consistency. Corrected OU and Security Group placement incident for a user.

## Video Walkthrough
https://www.loom.com/share/6044f9089d9243f087b19bf71d16c83a

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
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
