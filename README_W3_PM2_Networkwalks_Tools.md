# 🔓 Networkwalks Week 3 - Password Cracking with Networkwalks Tools

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red)
![Skill](https://img.shields.io/badge/Skill-Ethical%20Hacking-red)
![Tool](https://img.shields.io/badge/Tool-Networkwalks%20Hash%20Calculator-informational)
![Tool](https://img.shields.io/badge/Tool-Networkwalks%20Password%20Cracker-informational)
![Platform](https://img.shields.io/badge/Platform-Web%20Browser-blue)

---

## 📌 Project Overview

This repository documents **Week 3 - Project Module 2 (W3-PM2)** of my Cybersecurity & Ethical Hacking practical work with Networkwalks.

The project focuses on understanding the password recovery process using two browser-based tools:

- **Networkwalks Hash Calculator**
- **Networkwalks Password Cracker**

The lab involved working with the provided password-protected PDF file. The file was first processed to obtain its password hash. The extracted hash was then used with the password recovery tool to recover the password in the authorized training environment.

This exercise demonstrates how weak passwords can be vulnerable and why strong password practices are important for protecting sensitive information.

---

## 🎯 Objectives

The objectives of this project were to:

- Understand the basic process of password recovery.
- Learn how password-protected files can be tested in an authorized environment.
- Use the **Networkwalks Hash Calculator** to extract a password hash.
- Identify the correct PDF hash format.
- Use the **Networkwalks Password Cracker** to perform password recovery.
- Observe how password complexity can affect recovery time.
- Verify the recovered password by opening the protected PDF.
- Understand the importance of strong password practices.

---

## 🧰 Tools Used

`Web Browser` · `Networkwalks Hash Calculator` · `Networkwalks Password Cracker` · `Password-Protected PDF`

---

## 🔍 Methodology

The project followed the following process:

**Download → Extract → Copy → Analyse → Recover → Verify**

### 1. Download

The password-protected PDF file provided for the lab was downloaded to the computer.

### 2. Extract

The file was uploaded to the **Networkwalks Hash Calculator** to extract its password hash.

### 3. Copy

The complete hash value was copied, beginning with:

```text
$pdf$...
```

### 4. Analyse

The extracted hash was prepared for the password recovery process.

### 5. Recover

The hash was entered into the **Networkwalks Password Cracker**.

### 6. Verify

The recovered password was entered into the locked PDF to confirm that the password recovery process was successful.

---

# 🧪 Project Walkthrough

## 1️⃣ Downloading the Locked PDF

The first step was downloading the password-protected PDF file provided for the practical exercise.

The file was used exclusively as part of the authorized Networkwalks cybersecurity training lab.

> 📸 **[Screenshot of- Downloading the encrypted PDF file (My Locked PDF1.pdf) 2026-08-25 113621]**

---

## 2️⃣ Opening the Networkwalks Hash Calculator

The **Networkwalks Hash Calculator** was opened in a web browser.

The tool was used to process the locked PDF and extract the password hash.

![Networkwalks Hash Calculator Upload Interface](Screenshot of- Networkwalks Hash Calculator in your web browser with  hash tool showing value that starts with $pdf$ 2026-08-25 110406)

**Figure 1:** Networkwalks Hash Calculator in the web browser showing the upload interface.

---

## 3️⃣ Extracting the Password Hash

The locked PDF was uploaded to the Hash Calculator.

The tool generated a password hash beginning with:

```text
$pdf$...
```

The complete hash value was copied for the next stage of the exercise.

![Extracted Password Hash](Screenshot of- screenshotsextracted-password-hash 2026-08-25 122417)

**Figure 2:** Extracted hash value beginning with `$pdf$` displayed in the Networkwalks Hash Calculator.

---

## 4️⃣ Opening the Networkwalks Password Cracker

The **Networkwalks Password Cracker** was opened in the web browser.

The extracted PDF hash was entered into the tool for password recovery.

![Networkwalks Password Cracker](screenshots/password-cracker-result.png)

**Figure 3:** Networkwalks Password Cracker showing the hash entered and the password recovery result for My-LockerPDF1.

---

## 5️⃣ Starting the Password Recovery Process

The password recovery process was started after the complete hash was entered.

The tool attempted different password possibilities until a matching password was identified.

The amount of time required can depend on factors such as:

- Password length
- Password complexity
- Password patterns
- Available wordlists
- Password recovery method

![Password Recovery Process](Screenshot of screenshotspassword-cracking-process2026-08-25 122433)

**Figure 4:** Password recovery process showing the password crack for My-LockerPDF1.

---

## 6️⃣ Password Recovery Result

After the recovery process was completed, the recovered password was displayed.

The result was then used to test whether the password could successfully unlock the provided PDF.

![Password Recovery Result](Screenshot of- Networkwalks Password Cracker- result showning the password crack for My-LockerPDF1 2026-08-25 110126)

**Figure 5:** Password recovery result displayed in the Networkwalks Password Cracker.

---

## 7️⃣ Verifying the Password

The recovered password was entered into the protected PDF.

The successful opening of the file confirmed that the password recovery process was completed successfully.

![My-LockerPDF1 Successfully Cracked](Screenshot of- My-LockerPDF1_Successfully Cracked 2026-08-25 110435)

**Figure 6:** My-LockerPDF1 successfully unlocked with the recovered password.

---

## 🔐 Key Security Lessons

This practical exercise demonstrated several important cybersecurity concepts:

| **Concept** | **Key Lesson** |
|---|---|
| Password Strength | Weak passwords can increase the risk of unauthorized recovery. |
| Password Complexity | Longer and more complex passwords are generally more difficult to recover. |
| Password Protection | Sensitive documents should use strong passwords and appropriate protection. |
| Security Awareness | Users should understand the risks associated with weak or reused passwords. |
| Ethical Testing | Password testing must always be performed with proper authorization. |

---

## ⚠️ Risk Highlights

| **Risk Level** | **Example** |
|---|---|
| 🔴 **High** | Sensitive files protected by weak or easily guessed passwords |
| 🟠 **Medium** | Short or predictable passwords |
| 🟢 **Low** | Long, unique, and complex passwords combined with additional security controls |

> **Note:** This project was completed using the password-protected PDF supplied specifically for the authorized training exercise.

---

## 🛠️ Recommendations

1. Use long and unique passwords for sensitive files and accounts.
2. Avoid common passwords and predictable number patterns.
3. Avoid reusing the same password across multiple services.
4. Use password managers to generate strong passwords.
5. Enable multi-factor authentication where available.
6. Protect sensitive documents using strong encryption.
7. Conduct authorized password security assessments.
8. Provide users with cybersecurity awareness training on password security.

---

## 📚 Learning Outcomes

Through this project, I gained experience in:

- Password security concepts
- Password hash extraction
- Password recovery workflows
- Browser-based cybersecurity tools
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Password strength awareness
- Ethical cybersecurity testing
- Security documentation

---

## 📝 Conclusion

This project provided practical experience with the password recovery process using the **Networkwalks Hash Calculator** and **Networkwalks Password Cracker**.

The exercise demonstrated the process of extracting a password hash from a protected PDF and using that information in an authorized password recovery workflow. It also reinforced the importance of strong passwords and appropriate security practices when protecting sensitive information.

---

## ⚖️ Disclaimer

This repository is intended strictly for **educational and authorized cybersecurity training purposes**.

All activities were performed using the password-protected PDF supplied for the Networkwalks lab. The techniques and tools described should only be used against files, accounts, systems, or data where explicit authorization has been granted.

Unauthorized attempts to access protected information may violate laws and organizational policies.

---

## 👤 Author

**Kemar Goulbourne**

Cybersecurity & Information Technology Student
Cybersecurity B082 – Batch A442
LinkedIn: https://www.linkedin.com/in/kemar-gouldbourne-a5008317a/

🇯🇲 Jamaica

---

## ⭐ Project Focus

**Password Security · Hash Extraction · Password Recovery · Networkwalks Tools · Ethical Hacking · Cybersecurity**
