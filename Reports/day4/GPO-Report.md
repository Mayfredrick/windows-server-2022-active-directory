# Group Policy Report

## Policies Created
IT Desktop Policy

## Linked Organizational Units
homelab.local/IT

## Password Policy
Minimum Password Length:10 characters
Maximum Password Age: 90days
Password History:5 passwords
Password Complexity:Enabled

## Administrative Template Settings
Prohibit access to Control Panel and PC settings:Enabled

## Commands Used
Get-ADDomain
hostname
gpresult /r
gpudate /force
Get-GPO -All
Get-GPInheritance -Target "OU=IT,DC=homelab,DC=local"
Get-GPOReport -All -ReportType HTML -Path C:\Temp\GPOReport.html

## Lessons Learned
Explain what a Group Policy Object (GPO) is.
Create and link a GPO to an OU.
Configure password and desktop policies.
Understand user vs. computer policies.
Verify that a policy is applied.
Use PowerShell to view Group Policy information.