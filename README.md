# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
 * This company, Northstar Medical Group (NMG), had no structure and was previously managed by a third-party MSP; therefore, end users who were supposed to have access in one department had access to other departments they weren’t supposed to. There was no documentation, management, or order in place, and since NMG is a medical company, HIPAA risks were indeed in play.
   
## Solution Overview
* The solution was creating a new employee pipeline. I created a new Domain, and then created 4 departments (OUs) so that we could begin with structure and have proper placement. I then created security groups for each department so that when end users are placed, they have (RBAC) Role-Based Access, and so one member from another department (IT) won’t have access to another (HR), confidentiality can be kept, and company efficiency can rise without compromise. Also simulated a mock ticket where a user was provisioned with the incorrect level of access.
  
## Video Walkthrough
https://www.youtube.com/watch?v=Ix6cqKg49lw

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
* Building OUs and Setting up Security Groups
* Solving Simulation Ticket
  
