# Week 3: Password Cracking & Hash Analysis - NetworkWalks Internship

This repository documents my practical tasks for Week 3 of the Cybersecurity Internship at NetworkWalks, focusing on extracting hashes from encrypted files and executing dictionary attacks.

## Completed Modules

### 1. W3-PM1: Password Cracking with John the Ripper (Kali Linux)
- Extracted the PDF hash using `pdf2john`.
- Cracked the password (`good-luck`) using **John the Ripper** with the `rockyou.txt` wordlist.
- Verified access by unlocking the target file (`My Locked PDF1.pdf`) and retrieving the flag.

### 2. W3-PM2: Password Cracking with NetworkWalks Tools
- Extracted the file hash using the **NetworkWalks Hash Calculator**.
- Executed a custom dictionary attack using the **NetworkWalks Password Cracker** to recover the password.
