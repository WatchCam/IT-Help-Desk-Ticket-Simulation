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

---

# Ticket #4 - Disable User Account 

## Issue
Employee Sarah Brooks has left the company and access must be removed.

## Resolution Steps
1. Opened Active Directory Users and Computers.
2. Located Sarah Brooks.
3. Right-Clicked the account 
4. Selected Disable Account
5. Verified the account was disabled.

## Resolution 
The user account was succesfully disabled to prevent unauthorization access.

## Skills Demonstrated

- Active Directory Administration
- Account Deprovisioning
- Identity & Access Management
- Help Desk Operations
- IT Documentation

## Evidence

### Screenshot 1 - Disable Account
<img width="3024" height="4032" alt="IMG_1516" src="https://github.com/user-attachments/assets/55f377be-b432-4656-aa21-829d59b5baaa" />

### Screenshot 2 - Account Disabled
<img width="3024" height="4032" alt="IMG_1515" src="https://github.com/user-attachments/assets/3d317c4f-61f0-4f42-b1c4-b5f1982aa8d2" />

---
# Ticket #5 - Create New Active Directory User

## Issue
A new employee, Emily Davis, requires an Active Directory account before starting work. 

## Resolution Steps

1. Opened Active Directory Users and Computers.
2. Navigated to CAMLAB Users.
3. Created a new user named Emily Davis.
4. Assigned username e.davis.
5. Configured an initial password.
6. Verified the account was successfully created.

## Resolution

The new employee account was successfully created and is ready for access provisioning.

## Skills Demonstrated

- Active Directory Administration 
- User Provisioning
- Identity Lifecyle Management (JML)
- Help Desk Support
- IT Documentation

## Evidence

### Screenshot 1 - New User Wizard
<img width="3024" height="4032" alt="IMG_1517" src="https://github.com/user-attachments/assets/930e2300-c04c-4f39-b01e-6bbc5ecb007d" />

### Screenshot 2 - Password Configuration
<img width="3024" height="4032" alt="IMG_1518" src="https://github.com/user-attachments/assets/6481178a-6f28-4822-acc8-acd8bdd3dfe6" />

### Screenshot 3 - User Successfully Created
<img width="3024" height="4032" alt="IMG_1519" src="https://github.com/user-attachments/assets/33576abd-74dd-4f23-89ca-f11c2067e2d0" />

---

# Ticket #6 - Move User to a Different Organizational Unit

## Issue
Emily davis transferred to the Human Resources department and needed to be moved to the correct Organizational Unit.

## Resolution Steps

1. Opened Active Directory Users and Computers.
2. Located Emily Davis.
3. Selected Move.
4. Chose the HR Organizational Unit.
5. Vewrified the user was successfully moved.

## Resolution

Emily Davis was successfully moved into the HR Organizational Unit.

## Skills Demonstrated

- Active Directory Administration
- Organizational Units (OUs)
- User Management
- Identity Lifecycle Management
- IT Documentation

## Evidence

### Screenshot 1 - Before Move
<img width="3024" height="4032" alt="IMG_1523" src="https://github.com/user-attachments/assets/b64bf750-b61d-49e1-933b-77d0b456dd29" />

### Screenshot 2 - Move User Dialog
<img width="3024" height="4032" alt="IMG_1524" src="https://github.com/user-attachments/assets/913be8d6-5dcd-49e8-bd81-60600bde431f" />

### Screenshot 3 - User Successfully Moved
<img width="3024" height="4032" alt="IMG_1525" src="https://github.com/user-attachments/assets/9d4d2eec-88f8-42c8-96e4-4df173e8efb2" />

---

