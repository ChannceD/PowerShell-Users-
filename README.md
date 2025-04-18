<p align="center">
<img src="C:\Users\Chann\Downloads\powershel.png"/>
</p>
# ⚡ Creating Users in Active Directory with PowerShell

This lab demonstrates how to automate the creation of user accounts in Active Directory using a PowerShell script. This process is critical for IT administrators managing large organizations and needing to onboard multiple users efficiently.

---

## 🖼️ Lab Overview (Screenshots + Descriptions)

### 1. Open PowerShell as Administrator on the Domain Controller
![PowerShell Admin](Creating%20Users%20with%20PowerShell/1.%20In%20Domain%20Controller%20open%20Powershell%20as%20admin%20.png)

We start by launching **PowerShell with administrative privileges** on our Domain Controller to gain the necessary rights for user creation.

---

### 2. Create a New PowerShell Script File
![Save New File](Creating%20Users%20with%20PowerShell/2.%20Save%20new%20file%20in%20PS%20.png)

A new `.ps1` script file is created and prepared to input the user creation commands.

---

### 3. Writing the Script to Create Users
![Write Script](Creating%20Users%20with%20PowerShell/3.%20Using%20a%20a%20script%20to%20create%20our%20users.png)

In this script, we loop through a list or use auto-generation logic to define parameters such as `FirstName`, `LastName`, `Username`, and default passwords.

---

### 4. Running the Script in PowerShell
![Run Script](Creating%20Users%20with%20PowerShell/4.%20Creating%20our%20users%20using%20script%20in%20poweshell%20.png)

With the script ready, it's executed in PowerShell to create user objects directly in Active Directory.

---

### 5. Successfully Created 1,000 Users
![Success](Creating%20Users%20with%20PowerShell/5.%20Sucsessfully%20creating%20our%201000%20users%20.png)

The script successfully created **1,000 user accounts**—proving how scalable and powerful scripting can be for IT admins.

---

### 6. Selecting a User to Test Login
![Choose User](Creating%20Users%20with%20PowerShell/6.%20choose%20a%20user%20to%20log%20into.png)

We select one of the newly created users to test authentication and ensure the account was provisioned correctly.

---

### 7. Logging In with New User
![Login](Creating%20Users%20with%20PowerShell/7.%20log%20in%20.png)

The selected user logs into the domain for the first time, validating the script's success.

---

### 8. Test Successful - User is Functional
![Login Test Pass](Creating%20Users%20with%20PowerShell/8.%20test%20sucessful%20user%20is%20working%20.png)

The login test passes, and the user is fully functional in the domain environment.

---

## 🚀 Skills Demonstrated

- PowerShell scripting for AD automation
- Active Directory user provisioning
- Administrative scripting practices
- Bulk user creation logic
- Domain login verification

---

## 💼 Why This Matters

Manual user creation is time-consuming and error-prone. Automating this process with PowerShell saves time, reduces mistakes, and scales effortlessly — making it a vital skill for system administrators and IT support technicians.

---
