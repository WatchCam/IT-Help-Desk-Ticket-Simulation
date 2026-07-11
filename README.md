# IT-Help-Desk-Ticket-Simulation

## Project Overview

This repository demonstration common IT Help Desk support tasks performed in a Windows Active Directory lab environment.
The purpose of this project is to showcase practical troubleshooting , user administration, and documentation skills expected of an entry-level IT support Specialist or Help Desk Technichian.

---

## Lab Environment

### Infrastructure

- Windows Server 2022|
- Active Directory Domain Services (AD DS)
- Windows 11 Client 
- Oracle VirtualBox

### Technologies Used

- Active Directory Users and Computers (ADUC)
- DNS
- Organizational Units (OUs)
- Security Groups
- NTFS Permissions
- Microsoft 365
- Windows 11
- Group Policy

---

## Skills Demonstrated

- User account provisioning
- Password resets
- Account unlocks
- Security group managements
- NTFS permissions
- Active Directory administration
- Windows troubleshooting 
- IT documentation
---

# Ticket 1 - Password Reset 
## Issue

A user contacted the IT Help Desk after forgetting their Active Directory password and was unable to sign in.

## Environment

- Windows Server 2022
- Active Directory Users and Computers (ADUC)

## Troubleshooting Steps 

1. Opened Active Directory Users and Computers.
2. Located John Carter.
3. Selected **Reset Password**.
4. Assigned a temporary password.
5. Required the user to change the password at next logon.
6. Verified the password reset was successful.

## Resolution

The password was successfully reset and the user was instructed to create a new password during their next sign-in.

## Skills Demonstrated

- Active Directory Administration
- Password Reset 
- User Account Management 
- Help Desk Support
- IT Documentation

## Evidence

### Screenshot 1 - Password Reset Window
<img width="1152" height="1536" alt="86AF6F76-51FB-4EA2-8AF9-B94CD5D399B4 - Copy" src="https://github.com/user-attachments/assets/b48204cc-7102-4de1-8d38-7ba6fb68b49e" />

### Screenshot 2 - Password Reset Successful
<img width="3024" height="4032" alt="IMG_1478" src="https://github.com/user-attachments/assets/717e6a9f-a157-4481-8e83-b901af222af8" />

---

# Ticket #2 - Unlock Locked User Account 

## Ticket Information

**Issue:**
User John Carter is unable to sign in because the Active Directory account is locked after multiple failed login attempts.

**Priority:**
Medium

**Category:**
Account Lockout

---

## Resolution Steps

1. Opened **Active Directory Users and Computers (ADUC)**.
2. Located the user **John Carter**.
3. Opened the user properties.
4. Navigated to the **Account** tab.
5. Checked **Unlock account**.
6. Clicked **Apply** and **OK**.
7. Verified the account was unlocked.

---

## Resolution

THe user account was successfully unlocked and access was restored.

---

## Skills Demonstrated

- Active Directory Administration
- Account Unlock
- User Account Management
- Help Desk Troubleshooting
- IT Documentation

---

## Evidence 

### Screenshot 1 - Account Unlock
<img width="3024" height="4032" alt="IMG_1479" src="https://github.com/user-attachments/assets/95cfdada-1b75-4459-9b95-2b58fae9037e" />

### Screenshot 2 - Account Successfully Unlocked
<img width="3024" height="4032" alt="IMG_1480" src="https://github.com/user-attachments/assets/3aaabc76-7300-4b5d-89d5-a262646b167a" />

---

# Ticket #3 - Add User to IT Support Security Group

## Issue
John Carter requires access to IT resources to perform help desk duties.

## Resolution Steps
1. Opened Active Directory Users and Computers.
2. Located John Carter.
3. Opened Properties > Memeber Of.
4. Added the user to the IT_Support security group.
5. Applied the changes and verified group membership.

## Resolution
John Carter was successfully added to the IT_Support security group.

## Skills Demonstrated
- Active Directory Administration 
- Security Group Management 
- User Provisioning 
- Access Control (RBAC)
- IT Documentation

## Evidence

### Screenshot 1 - Before Group Assignment 
<img width="3024" height="4032" alt="IMG_1491" src="https://github.com/user-attachments/assets/c2103852-afe1-4e57-874c-6abdc60459b4" />

### Screenshot 2 - IT_Support Group Added
<img width="3024" height="4032" alt="IMG_1492" src="https://github.com/user-attachments/assets/a173000e-dd11-4458-bb6b-ebe557a66869" />

