# Active Directory Users Report

## Domain
-homelab.local

## Organizational Units
-IT
-Sales
-Workstations
-HR
-Finance
-Servers
-Service Accounts

## Users Created
-John Admin
-Lisa Wilson
-Sarah Brown
-David Miller

## Security Groups
-IT_Admin
-HR_Users
-Finance_Users
-Sales_USers

## PowerShell Commands Used
-Get-ADUser -Filter *
-Get-ADUSer -Filter * | Select Name
-Get-ADGroup -Filter *
-Disable-ADAccount john.admin
-Get-ADUser john.admin -Properties Enabled
-Enable-ADAccount john.admin

## Lessons Learned
Create Organizational Units (OUs)
Create user accounts
Create security groups
Add users to groups
Reset passwords
Disable and enable user accounts
Unlock user accounts
Perform basic Active Directory management with PowerShell
