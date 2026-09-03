# \# Week 2 Day 2

\## Objectives



The objective of today's lab is to promote Windows Server 2022 to a Domain Controller by creating a new Active Directory forest and domain. I will configure Active Directory Domain Services (AD DS), install DNS, verify the domain controller is functioning correctly. Once a server is ready I will start to manage users, computers, and network resources within an Active Directory environment.



## \# Server Information

\-Windows server 2022 stand alone



## \# Active Directory

\-Forest name: homelab.local

\-Domain name: homelab

\-Domain mode: Windows2016Domain

\-DNS status: Installed and working 

\-OU creation: I created 2 organization units one for IT and one for Workstations

## \# Problems Encountered

\-For this lab I faced password issues for local administrator which block the domain controller promotion. I was able to solve this by creating a strong password and I was able to promote domain controller. 

## Lessons Learned

\## Lessons Learned



Today I successfully promoted Windows Server 2022 to a Domain Controller by creating a new Active Directory forest named `homelab.local`. I learned that Active Directory depends on DNS to locate domain services and authenticate users and computers. I also learned the importance of using a static IP address before promotion and verified the installation using PowerShell commands such as `Get-ADDomain`. This lab strengthened my understanding of the foundation of Windows enterprise network administration.



