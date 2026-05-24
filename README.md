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

### Screenshot

```text
Insert Screenshot Here
```

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

```text
Insert Screenshot Here
```

---

## Step 3 — Open Active Directory Administrative Center

After installation completes and the system restarts:

Open:

- Active Directory Administrative Center (ADAC)

This interface is used to manage users, groups, and organizational units.

### Screenshot

```text
Insert Screenshot Here
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

```text
Insert Screenshot Here
```

---

## Step 5 — Configure User Password

The account will initially appear disabled until a secure password is configured.

Use:

- Reset Password

To activate the account.

### Screenshot

```text
Insert Screenshot Here
```

---

# Group Management

## Step 6 — Create Python Developers Group

Create a new security group named:

- Python Developers

### Screenshot

```text
Insert Screenshot Here
```

---

## Step 7 — Add Python Developers to Developers Group

Add:

- Python Developers

To:

- Developers

This demonstrates nested group management commonly used in enterprise environments.

### Screenshot

```text
Insert Screenshot Here
```

---

## Step 8 — Add Alex to Python Developers Group

Modify the group membership to include:

- Alex

Inside:

- Python Developers

### Screenshot

```text
Insert Screenshot Here
```

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

```text
Insert Screenshot Here
```

---

# Group Policy Management

## Step 10 — Open Group Policy Management

Launch:

- Group Policy Management

This tool allows administrators to manage enterprise policies across systems and users.

### Screenshot

```text
Insert Screenshot Here
```

---

## Step 11 — Create a New GPO

Create a Group Policy Object named:

- New Wallpaper

Link the policy to:

- Developers Organizational Unit (OU)

### Screenshot

```text
Insert Screenshot Here
```

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

```text
Insert Screenshot Here
```

---

## Step 13 — Verify GPO Settings

Verify the configured wallpaper policy inside the Group Policy Management Console.

Ensure the Desktop Wallpaper setting is successfully applied.

### Screenshot

```text
Insert Screenshot Here
```

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







