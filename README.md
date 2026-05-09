# Capture the Flag (CTF) Password Cracking Lab

## Overview
This project documents my approach to solving a Capture the Flag (CTF) cybersecurity challenge involving password hash extraction and password cracking within a Linux virtual machine environment.

The objective of the challenge was to locate the password hash for the user `cookiemonster` inside the `/etc/shadow` file and crack the hash using John the Ripper to recover the password.

---

## Skills Demonstrated
- Linux Command Line
- Password Hash Analysis
- John the Ripper
- Oracle VM VirtualBox
- Cybersecurity Investigation Techniques
- Security Documentation
- Problem Solving & Analysis

---

## Tools Used
- Oracle VM VirtualBox
- Linux
- John the Ripper
- grep command
- /etc/shadow file analysis

---

## Process
1. Logged into the vulnerable Linux virtual machine
2. Located the password hash inside `/etc/shadow`
3. Used `grep cookiemonster /etc/shadow`
4. Extracted the password hash into a separate file
5. Used John the Ripper to crack the hash
6. Verified the recovered password using `john --show`

---

## Key Takeaways
- Weak passwords remain vulnerable even when hashed
- Understanding Linux authentication systems is essential in cybersecurity
- Password auditing and security testing are important defensive practices
- CTF exercises help develop real-world cybersecurity skills

---

## Related Concepts
- Password Security
- Ethical Hacking
- Linux System Administration
- Security Awareness
- Risk Management

---

## Presentation
The full presentation for this project is included in this repository.

---

## Author
Latasha Kellon  
Cybersecurity Technology Student at UMGC

---

## Lab Screenshots

### Virtual Machine Environment
![VirtualBox Screenshot](screenshots/Screenshot%202026-04-25%20004840.png)

### Password Hash Extraction
![grep Output](screenshots/Screenshot%202026-04-25%20004913.png)

### John the Ripper Results
![John the Ripper](screenshots/Screenshot%202026-04-25%20010524.png)
