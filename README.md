# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical is a fictional, fast-growing company that outsources its IT management to a third party called MSP. MSP relies on manual processes, and Northstar Medical has no Role-Based Access Control (RBAC) policy in place, creating potential HIPAA compliance and security risks. Initially, IT management appeared to work well, but as the company grew, access-control problems began to emerge. For example, a newly hired HR payroll specialist could log into the system but could not access the HR resources required to perform her job. This situation demonstrated the need for proper RBAC policies to ensure employees have appropriate access based on their job responsibilities.

## Solution Overview
* The solution is to build a structured Active Directory environment with OUs and security groups structure that separate employees based on their roles and responsibilities. I identified that the HR payroll specialist had been placed in the wrong OU, I moved her to the correct OU, and updated the related security policies. I created security groups and implemented a RBAC model that ensured users receive access based only on their assigned roles. This approach reduced manual errors, enforced least-privilege access, and ensured employees received only the resources required to perform their jobs.

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
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
