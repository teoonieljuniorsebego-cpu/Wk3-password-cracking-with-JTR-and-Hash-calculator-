GitHub Repository Name suggestion: networkwalks-week3-password-cracking or password-cracking-jtr-nw-tools
Short GitHub Description (for the repo “About” section): Hands-on password cracking labs from Networkwalks Week 3 – cracking password-protected PDFs using John the Ripper (JTR) + Johnny GUI and Networkwalks’ own Hash Calculator + Password Cracker tools.

README.md
# Networkwalks Week 3 – Password Cracking Labs

Hands-on cybersecurity lab work completed as part of the **Networkwalks Cybersecurity Internship**.

This repository documents the successful completion of **Week 3 Project Modules** focused on password cracking techniques against password-protected PDF files.

## Modules Completed

### Essential Modules
- **W3-PM1**: Password Cracking with John the Ripper (JTR) + Johnny GUI  
- **W3-PM2**: Password Cracking with Networkwalks Tools (Hash Calculator + Password Cracker)

### Optional Modules (if completed)
- W3-OPTIONAL1: AI-assisted JTR Password Cracking Lab (Claude + Hexstrike MCP)
- W3-OPTIONAL2: Mediroza Hospital patient portal hacking

## What Was Done

1. Extracted the `$pdf$` hash from a password-protected PDF.
2. Used **John the Ripper** (with Johnny GUI) to perform a dictionary attack.
3. Used **Networkwalks’ own Hash Calculator + Password Cracker** tools to crack a second PDF.
4. Successfully recovered the plaintext password (`1qaz2wsx` in one of the labs).
5. Captured the completion flag: `nw{networkwalks_flag_260821_1}`

## Key Takeaways

- Password-protected files store a **hash**, not the plaintext password.
- Encryption is reversible with a key; **hashing is one-way**.
- Weak passwords (dictionary words or simple keyboard patterns) can be cracked very quickly.
- Tools like John the Ripper demonstrate why strong, unique passwords are critical.

## Tools Used

- John the Ripper (JTR)
- Johnny GUI
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- PDF hash extraction techniques

## Disclaimer

This work was performed **strictly for educational purposes** as part of a guided cybersecurity internship with Networkwalks under the mentorship of Waqas Karim (CCIE). All activities were conducted in controlled lab environments.

---

**Internship**: Networkwalks Cybersecurity Internship  
**Week**: 3 – Password Cracking  
**Status**: Completed

