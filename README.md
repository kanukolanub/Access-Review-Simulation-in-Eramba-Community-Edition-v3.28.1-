# Access-Review-Simulation-in-Eramba-Community-Edition-v3.28.1-
This repository documents a hands‑on Access Review simulation performed using Eramba Community Edition 3.28.1.
The goal of this lab is to demonstrate practical GRC, IAM, and security governance skills by executing a realistic quarterly access review using a lightweight, open‑source GRC platform.

Even though Eramba CE lacks automated workflows, this exercise shows how to perform a complete, audit‑ready access review using manual processes — exactly how many organizations operate today.

🎯 Lab Objectives
This exercise simulates a quarterly access review with the following goals:

Review user access and group memberships

Identify excessive or incorrect access

Update access based on role changes

Deactivate accounts for terminated users

Document changes directly in Eramba CE

Demonstrate Access Certification & Recertification

Practice real‑world GRC/IAM processes

🛠️ Tools & Environment
Eramba Community Edition 3.28.1

Access Management → Accounts

Access Management → Groups

Test Users:

David

John

Test Groups:

GRC Team

SOC Team

🧪 Full Lab Walkthrough
1️⃣ Review Group Memberships
Reviewed both groups (GRC Team and SOC Team) to identify:

Incorrect access

Outdated access

Missing access

This step simulates the “Review” phase of an access certification cycle.

2️⃣ Simulate Real‑World Access Scenarios
Scenario A — Excess Access
David was incorrectly assigned to the SOC Team

Removed David from the SOC Team

Documented the change in the Description field

Scenario B — Role Change
John moved from SOC Team → GRC Team

Updated John’s group memberships accordingly

Documented the change in the Description field

Scenario C — Terminated User
Simulated termination of David

Set account status to Inactive

Removed all group memberships

Documented the deactivation

3️⃣ Documentation (Manual, CE‑Friendly)
Since Eramba CE does not include:

Comments

Workflow

Evidence attachments

Automated access reviews

All review notes were added to the Description fields of:

Users

Groups

This serves as audit evidence for the access review.

🧩 Skills Demonstrated
Access Review & Certification

Identity & Access Management (IAM)

Governance, Risk & Compliance (GRC)

Least Privilege Enforcement

Documentation & Audit Readiness

Manual control execution in CE environments

Hands‑on Eramba configuration

💡 Why This Matters
Access reviews are a foundational control in:

ISO 27001

SOC 2

Internal audits

IAM programs

Security governance frameworks

This lab demonstrates the ability to:

Identify excessive access

Correct access violations

Deactivate accounts

Document decisions

Maintain least privilege

Execute controls manually when tools lack automation

These are essential skills for GRC, IAM, and security analyst roles.
