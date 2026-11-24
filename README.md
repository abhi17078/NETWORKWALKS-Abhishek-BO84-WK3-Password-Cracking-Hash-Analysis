# NETWORKWALKS-Abhishek-BO84-WK3-Password-Cracking-Hash-Analysis
This repository documents my Week 3 practical tasks, focusing on password auditing, hash analysis, dictionary-based attacks, and password security.


## Cybersecurity Internship | Practical Submission

## ⭐ Project Highlights

![John the Ripper](https://img.shields.io/badge/John_the_Ripper-Password_Auditing-red?style=for-the-badge&logo=kalilinux&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-Lab_Environment-blue?style=for-the-badge&logo=kalilinux&logoColor=white)
![Hash Analysis](https://img.shields.io/badge/Hash_Analysis-MD5%20%7C%20SHA-orange?style=for-the-badge)
![Dictionary Attack](https://img.shields.io/badge/Dictionary_Attack-Wordlists-purple?style=for-the-badge)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-Online_Tools-green?style=for-the-badge)
![PDF Hash Extraction](https://img.shields.io/badge/PDF-Hash_Extraction-yellow?style=for-the-badge)
![Password Security](https://img.shields.io/badge/Password_Security-Analysis-informational?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Hands--On_Practice-black?style=for-the-badge)



This repository documents my Week 3 practical tasks, focusing on password auditing, hash analysis, dictionary-based attacks, and password security.

The objective was to understand how password hashes work, explore password-cracking techniques, and gain practical experience with industry-relevant security tools.

---
## 📌 Tasks Overview

| Task ID | Practical | Tools |
|---|---|---|
| W3-PM1 | Password Cracking with John the Ripper | John the Ripper, Kali Linux |
| W3-PM2 | Password Cracking with NW Tools | NetworkWalks Hash Calculator, Password Cracker |

---
# W3-PM1: PDF Password Recovery Using John the Ripper (GUI)

### Objective
The aim of this practical was to understand how passwords of encrypted PDF documents can be recovered through hash analysis. The password hash was first extracted from each PDF and then processed using John the Ripper. Once the password was identified, the protected document was opened to find the hidden flag.

### Tools Used
- John the Ripper (GUI)
- John.exe
- OnlineHashCrack PDF Hash Extractor
- Notepad

### Practical Methodology

**Step 1: Setting Up John the Ripper**
- Installed and started the John the Ripper GUI application.
- Accessed the application settings to configure the required executable.
- Located the `john.exe` file on the system and added its path.
- This setup allowed the graphical interface to communicate with the password recovery tool.

**Step 2: Generating the PDF Hash**
- Selected and downloaded the first password-protected PDF supplied for the task.
- Visited the OnlineHashCrack PDF Hash Extractor website.
- Uploaded the document so the tool could read its password protection information.
- Generated and copied the hash value associated with the PDF.

Tool: https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

**Step 3: Preparing the Hash for Analysis**
- Opened Notepad and pasted the extracted hash into a new file.
- Saved the file as `hash1.txt`.
- Keeping the hash in a separate text file made it ready to be imported into John the Ripper.

**Step 4: Recovering the PDF Password**
- Imported `hash1.txt` into the John the Ripper GUI.
- Started the recovery operation on the extracted hash.
- The tool analysed the hash and attempted to find a matching password.
- Once the process returned a result, noted down the recovered password.

**Step 5: Accessing the PDF and Finding the Flag**
- Opened the password-protected PDF using the recovered password.
- Checked the document after gaining access.
- Found and recorded the flag mentioned inside the PDF.

**Step 6: Repeating the Practical**
- Applied the same workflow to the remaining two encrypted PDF files.
- Generated a separate hash for each document.
- Used John the Ripper to recover their passwords.
- Opened both PDFs with the corresponding passwords and collected their flags.

### Result
The password recovery process was completed for all three provided PDF files. Their password hashes were extracted and analysed using John the Ripper GUI. After recovering the passwords, all three documents were accessed and the flags were collected successfully.

# W3-PM2: Password Cracking using NetworkWalks Tools

### Objective
To explore browser-based PDF hash extraction and password-cracking utilities using NetworkWalks tools.

### Tools Used
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Encrypted PDF file

### Practical Methodology

**Step 1: PDF Hash Extraction**
- Accessed the NetworkWalks Hash Calculator.
- Uploaded the provided encrypted PDF file.
- Generated and extracted the PDF password hash.

Tool: https://networkwalks.com/hash-calculator/

**Step 2: Password Cracking**
- Copied the extracted hash value.
- Opened the NetworkWalks Password Cracker.
- Submitted the hash for password recovery.
- Executed the password-cracking process.
- Retrieved the recovered password.

Tool: https://networkwalks.com/password-cracker/

**Step 3: Flag Extraction**
- Opened the encrypted PDF using the recovered password.
- Accessed the document contents.
- Retrieved the flag contained inside the PDF.

### Result
Successfully recovered the encrypted PDF password using NetworkWalks tools and extracted the flag.

---



## Comparison of Both Practical Tasks

| Parameter | W3-PM1: John the Ripper | W3-PM2: NetworkWalks |
|---|---|---|
| Working Platform | Desktop application | Online web tools |
| Hash Generation | OnlineHashCrack PDF Hash Extractor | NetworkWalks Hash Calculator |
| Password Recovery Tool | John the Ripper GUI | NetworkWalks Password Cracker |
| Hash Submission | Imported through `hash1.txt` | Submitted directly on the website |
| Main Purpose | Recovering the PDF password | Recovering the PDF password |
| Final Output | Password recovered and flag collected | Password recovered and flag collected |

## Key Learnings

- Gained practical knowledge of how password hashes are obtained from protected PDF documents.
- Learned to use different tools for analysing and recovering PDF passwords.
- Understood how John the Ripper is configured and used through its graphical interface.
- Practised saving hash information in text files and importing it into an application.
- Explored online tools that provide hash calculation and password recovery features.
- Understood the different stages involved in recovering access to encrypted documents.
- Learned why using long, complex and unique passwords is important for file security.

## Disclaimer

All activities in this project were carried out for educational and learning purposes as part of the cybersecurity internship. The practical work was limited to the encrypted PDF files provided in the assigned tasks.

---

**Week 3 Practical Submission | PDF Password Recovery & Hash Analysis**
