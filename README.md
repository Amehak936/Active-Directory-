# Active Directory Administration Lab

## Project Overview

This project demonstrates hands-on experience with installing, configuring, and managing Active Directory in a Windows environment. The lab simulates real-world enterprise administrative tasks including:

- Installing Active Directory
- Managing domain users
- Managing security groups
- Configuring group memberships
- Editing user permissions
- Managing Group Policy Objects (GPOs)

This project was created to showcase practical IT administration and cybersecurity skills relevant to enterprise environments.

---

# Skills Demonstrated

- Active Directory Administration
- Windows Server Administration
- User & Group Management
- Group Policy Management (GPO)
- Identity & Access Management (IAM)
- PowerShell Administration
- Windows System Configuration
- Enterprise IT Operations
- Access Control Management

---

# Tools & Technologies

| Tool | Purpose |
|---|---|
| Windows Server | Active Directory Environment |
| Active Directory Administrative Center (ADAC) | User & Group Management |
| Group Policy Management | GPO Configuration |
| Windows PowerShell | Active Directory Installation |

---

# Lab Objectives

- Install and configure Active Directory
- Create and manage users
- Create and manage security groups
- Configure nested group memberships
- Modify existing user permissions
- Create and configure Group Policy Objects
- Apply enterprise desktop policies

---

# Installation Process

## Step 1 — Launch PowerShell

Open Windows PowerShell as Administrator.


---

## Step 2 — Install Active Directory

Run the following PowerShell script:

```powershell
C:\Qwiklabs\ADSetup\active_directory_install.ps1
```

Expected behavior:

- Installation may take several minutes
- Warning messages may appear
- The system will restart after installation completes

### Screenshot


<img width="844" height="632" alt="Screenshot 2026-05-24 at 3 50 48 PM" src="https://github.com/user-attachments/assets/f9002e5a-1d76-4bc7-80ba-d98289811b5e" />



---

## Step 3 — Open Active Directory Administrative Center

After installation completes and the system restarts:

Open:

- Active Directory Administrative Center (ADAC)

This interface is used to manage users, groups, and organizational units.

### Screenshot

```text
Insert Screenshot Here <img width="570" height="341" alt="Screenshot 2026-05-24 at 4 12 49 PM" src="https://github.com/user-attachments/assets/4cdab2e8-83b8-4986-bd91-a4369dcd5c4e" />

```

---

# User Management

## Step 4 — Create a New User

Create a new user named:

- Alex

Navigate to:

- Example (Local)
- Users
- New → User

Fill in the required user information and create the account.

### Screenshot


 <img width="553" height="298" alt="Screenshot 2026-05-24 at 4 17 16 PM" src="https://github.com/user-attachments/assets/1e031a90-6f97-4022-a081-41350743a21c" />


---

## Step 5 — Configure User Password

The account will initially appear disabled until a secure password is configured.

Use:

- Reset Password

To activate the account.

### Screenshot

<img width="468" height="252" alt="image" src="https://github.com/user-attachments/assets/900294af-f00d-4deb-b8f7-3bb4382205e5" />

<img width="241" height="165" alt="image" src="https://github.com/user-attachments/assets/3e0dd8aa-d2e6-4aa9-aa59-86d7c773167e" />

---

# Group Management

## Step 6 — Create Python Developers Group

Create a new security group named:

- Python Developers

### Screenshot

<img width="290" height="248" alt="image" src="https://github.com/user-attachments/assets/2c6866c1-74ed-474d-94e2-801f29fc3c68" />

---

## Step 7 — Add Python Developers to Developers Group

Add:

- Python Developers

To:

- Developers

This demonstrates nested group management commonly used in enterprise environments.

### Screenshot

<img width="366" height="193" alt="image" src="https://github.com/user-attachments/assets/fe7f1a11-3f03-408a-bf1a-8feafe0570db" />

---

## Step 8 — Add Alex to Python Developers Group

Modify the group membership to include:

- Alex

Inside:

- Python Developers

### Screenshot

<img width="468" height="355" alt="image" src="https://github.com/user-attachments/assets/245feead-bc21-40ea-b8a7-b803c7d87583" />

---

# Editing User Memberships

## Step 9 — Modify Existing User Memberships

Locate the existing user:

- Alosha

Tasks performed:

- Remove from Java Developers
- Add to Python Developers

This demonstrates modifying role-based access permissions.

### Screenshot

<img width="468" height="276" alt="image" src="https://github.com/user-attachments/assets/c1f917c1-f85f-426f-8cd8-a7fcc8372706" />

---

# Group Policy Management

## Step 10 — Open Group Policy Management

Launch:

- Group Policy Management

This tool allows administrators to manage enterprise policies across systems and users.

### Screenshot

<img width="370" height="270" alt="image" src="https://github.com/user-attachments/assets/e7b0edf2-a1b5-4df5-887b-7c2846840207" />

---

## Step 11 — Create a New GPO

Create a Group Policy Object named:

- New Wallpaper

Link the policy to:

- Developers Organizational Unit (OU)

### Screenshot

<img width="468" height="224" alt="image" src="https://github.com/user-attachments/assets/d5cc4f2b-1689-46bb-b51d-0c39abac4215" />

---

## Step 12 — Configure Desktop Wallpaper Policy

Navigate to:

```text
User Configuration → Policies → Administrative Templates → Desktop → Desktop
```

Configure:

- Desktop Wallpaper

Wallpaper path:

```text
C:\Qwiklabs\wallpaper.jpg
```

Enable the setting and apply the wallpaper path.

### Screenshot

<img width="468" height="319" alt="image" src="https://github.com/user-attachments/assets/3e632eb2-3ab5-4cbf-b57d-b0e5855d109c" />

---

## Step 13 — Verify GPO Settings

Verify the configured wallpaper policy inside the Group Policy Management Console.

Ensure the Desktop Wallpaper setting is successfully applied.

### Screenshot

<img width="468" height="233" alt="image" src="https://github.com/user-attachments/assets/41f8a83c-3deb-465c-b9d9-0b7c0231317e" />

---

# Key Takeaways

This project demonstrates:

- Enterprise Active Directory administration
- Identity & Access Management concepts
- Windows domain administration
- Group Policy management
- Access control administration
- PowerShell usage
- Technical documentation skills

---

# Why This Project Matters

Active Directory is widely used in enterprise environments for centralized authentication and access management.

This project demonstrates real-world administrative tasks relevant to:

- SOC Analyst Roles
- ISSO Positions
- System Administration
- IT Support
- Cybersecurity Operations
- Identity & Access Management (IAM)

---

# Future Improvements

Potential future enhancements include:

- Password policy hardening
- Account lockout policies
- SIEM integration
- Windows Event Log monitoring
- PowerShell automation
- Multi-server enterprise environments
- Security auditing







