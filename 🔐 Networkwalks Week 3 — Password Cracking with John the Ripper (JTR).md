# 🔐 Networkwalks Week 3 — Password Cracking with John the Ripper (JTR)

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red)
![Skill](https://img.shields.io/badge/Skill-Ethical%20Hacking-red)
![Tool](https://img.shields.io/badge/Tool-John%20the%20Ripper-informational)
![Tool](https://img.shields.io/badge/Tool-Johnny%20GUI-informational)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)

---

## 📌 Project Overview

This repository documents **Week 3 — Project Module 1 (W3-PM1)** of my Cybersecurity & Ethical Hacking practical work with Networkwalks.

The project focuses on understanding **password security and password recovery** using **John the Ripper (JTR)** and its graphical interface, **Johnny**.

For this lab, I worked with the provided password-protected PDF file, extracted its password hash, loaded the hash into Johnny, and performed the password recovery process in the authorized lab environment.

The exercise demonstrates why weak passwords can create security risks and why strong password practices are important.

---

## 🎯 Objectives

The objectives of this project were to:

- Understand the purpose of password cracking in cybersecurity.
- Learn how password-protected files can be tested in an authorized environment.
- Use **John the Ripper (JTR)** for password recovery.
- Configure and use the **Johnny GUI**.
- Extract the password hash from the provided locked PDF.
- Save and load the extracted hash for analysis.
- Recover the password of the provided lab file.
- Verify the recovered password by opening the PDF.
- Understand the importance of strong passwords.

---

## 🧰 Tools Used

`Windows` · `John the Ripper (JTR)` · `Johnny GUI` · `Online PDF Hash Extractor` · `Notepad` · `Password-Protected PDF`

---

## 🔍 Methodology

The project followed the following process:

**Prepare → Extract Hash → Save Hash → Load → Recover → Verify**

### 1. Prepare

John the Ripper and the Johnny graphical interface were installed and configured on the Windows system.

### 2. Extract Hash

The password hash was extracted from the provided locked PDF file.

### 3. Save Hash

The extracted hash was copied into a text file named `hash1.txt`.

### 4. Load

The hash file was opened in Johnny.

### 5. Recover

A new password recovery attack was started against the provided hash.

### 6. Verify

The recovered password was used to open the protected PDF and confirm the result.

---

# 🧪 Project Walkthrough

## 1️⃣ Installing John the Ripper

The first step involved obtaining and setting up **John the Ripper** on the Windows computer.

John the Ripper is a password recovery tool used by security professionals to evaluate password strength and recover passwords in authorized security-testing environments.

### 📸 Screenshot

> 🖼️ **[INSERT JOHN THE RIPPER INSTALLATION SCREENSHOT HERE]**

---

## 2️⃣ Installing and Configuring Johnny

**Johnny** was used as the graphical interface for John the Ripper.

After installation, Johnny was configured to locate the `john.exe` executable.

### 📸 Screenshot

> 🖼️ **[INSERT JOHNNY CONFIGURATION SCREENSHOT HERE]**

---

## 3️⃣ Extracting the PDF Hash

The provided locked PDF was processed to obtain its password hash.

The extracted value was saved in the correct format beginning with:

```text
$pdf$...
```

The hash was then copied into a text file.

### 📸 Screenshot

> 🖼️ **[INSERT HASH EXTRACTION SCREENSHOT HERE]**

---

## 4️⃣ Creating the Hash File

The extracted password hash was saved using Notepad as:

```text
hash1.txt
```

This file was then prepared for use with Johnny and John the Ripper.

### 📸 Screenshot

> 🖼️ **[INSERT HASH1.TXT SCREENSHOT HERE]**

---

## 5️⃣ Loading the Hash into Johnny

The `hash1.txt` file was opened using the **Open Password File** option in Johnny.

The password hash was then ready for the recovery process.

### 📸 Screenshot

> 🖼️ **[INSERT JOHNNY HASH FILE SCREENSHOT HERE]**

---

## 6️⃣ Starting the Password Recovery Process

A new attack was started using Johnny and the loaded password hash.

The recovery time can vary depending on factors such as:

- Password length
- Password complexity
- Password patterns
- System performance
- Available wordlists or cracking methods

### 📸 Screenshot

> 🖼️ **[INSERT PASSWORD RECOVERY SCREENSHOT HERE]**

---

## 7️⃣ Verifying the Recovered Password

After the password was recovered, it was used to unlock the provided PDF file.

The successful opening of the document confirmed that the password recovery process was completed successfully.

### 📸 Screenshot

> 🖼️ **[INSERT UNLOCKED PDF SCREENSHOT HERE]**

---

# 🔐 Key Security Lessons

This practical exercise demonstrated several important cybersecurity concepts:

| **Concept** | **Key Lesson** |
|---|---|
| Password Strength | Weak or predictable passwords may be easier to recover. |
| Password Hashes | Password protection mechanisms can use hash-based data that can be tested during authorized recovery processes. |
| Password Complexity | More complex passwords generally increase the difficulty and time required for recovery attempts. |
| Security Testing | Password auditing should only be performed with proper authorization. |
| User Awareness | Strong passwords are an important part of protecting sensitive information. |

---

# ⚠️ Risk Highlights

| **Risk Level** | **Example** |
|---|---|
| 🔴 High | Weak or easily guessed passwords protecting sensitive files |
| 🟠 Medium | Short passwords or passwords based on common words and predictable patterns |
| 🟢 Low | Strong, unique, and appropriately complex passwords |

> **Note:** This project involved a password-protected file supplied specifically for the lab. No unauthorized password recovery or access was performed.

---

# 🛠️ Recommendations

1. Use long and unique passwords.
2. Avoid common words and predictable patterns.
3. Use a combination of uppercase letters, lowercase letters, numbers, and symbols where appropriate.
4. Avoid reusing passwords across multiple accounts or systems.
5. Use password managers to generate and store strong passwords.
6. Use multi-factor authentication where available.
7. Conduct authorized password audits to identify weak credentials.
8. Protect sensitive files using appropriate encryption and access controls.

---

# 📂 Repository Structure

```text
W3-PM1-Password-Cracking-with-JTR/
│
├── README.md
│
├── screenshots/
│   ├── john-installation.png
│   ├── johnny-configuration.png
│   ├── hash-extraction.png
│   ├── hash1-file.png
│   ├── johnny-password-file.png
│   ├── password-recovery.png
│   └── unlocked-pdf.png
│
└── evidence/
    └── lab-evidence/
```

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Password security concepts
- Password recovery in an authorized environment
- John the Ripper
- Johnny GUI
- Password hash extraction
- Password hash handling
- Password strength testing
- Cybersecurity documentation
- Ethical and responsible security practices

---

# 📝 Conclusion

This project provided practical experience with password recovery using **John the Ripper and Johnny**. The lab demonstrated the relationship between password strength and the difficulty of recovering a protected password.

The exercise reinforced the importance of using strong and unique passwords to protect sensitive information. It also demonstrated how cybersecurity professionals can use password recovery tools during authorized security assessments and password audits.

---

# ⚖️ Disclaimer

This project was completed strictly for **educational and authorized cybersecurity training purposes**.

All password recovery activities were performed only on the password-protected PDF provided for the lab. The techniques and tools discussed in this repository should only be used on systems, accounts, files, or data for which explicit authorization has been granted.

Unauthorized access to protected files, systems, or accounts may be illegal.

---

# 👤 Author

**Kemar Goldburn**

Cybersecurity & Information Technology Student

🇯🇲 Jamaica

---

## ⭐ Project Focus

**Password Security • John the Ripper • Johnny GUI • Password Recovery • Hash Analysis • Ethical Hacking • Cybersecurity**