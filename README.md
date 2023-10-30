# PowerShell-FIM

A File Integrity Monitoring (FIM) system, simply put, is a system that monitors computer files for the purpose of validating its integrity. It does so by comparing the cryptographic hash value of a known good baseline version of a file to its current state to ensure it hasn't been altered. If altered, it has the ability to notify users if the hash value calculated is different from what’s stored in the baseline.txt.

**Goal:** The purpose of this project will be to improve upon a FIM Powershell script. The script is currently capable of collecting new baselines, monitoring files with saved baseline, continuously monitoring files, and notifying users if a file is changed or deleted. 


*All thanks and credit for this lab goes to Josh Madakor*
