# Payville Inc. Server Security Configuration

## Project Overview
This project involved setting up a secure Linux environment for Payville Inc. The goal was to ensure that sensitive company data is only accessible to authorized personnel.

## User & Group Management
I created departmental groups and assigned employees to them as follows:

| Group | Members | Purpose |
| :--- | :--- | :--- |
| admin | Andrew, Gozie, ella | System maintenance. |
| finance | Adeola, Ogochukwu | Budgeting and payroll. |
| management | Bach, Jennifer | Oversight. |
| legal | Julius | Contracts. |
| hr | Chizi | Employee records. |

## Permissions Breakdown
I used specific numeric codes to ensure strict access control:
* 770 (Private): Used for Finance, HR, and Admin scripts. Only the group members can access these.
* 775 (Public): Used for the Vision & Mission folder so the whole company can read it.

## Final Verification
Below are the screenshots showing the step-by-step configuration of the Payville Server.
### Step 1: Directory Structure & Initial Ownership
![Directory Setup](Screenshot%202026-02-22%20154143.png)
### Step 2: Directory Structure II
![Directory Setup](Screenshot%202026-02-22%20154207.png)
### Step 3: Permission Configuration (chmod 770/775) and  Group Assignments (chown)
![Group Ownership & Permissions Applied](Screenshot%202026-02-22%20154022.png)
### Step 4: Final Verification (ls -l)
![Final Result](Screenshot%202026-02-22%20163453.png)

