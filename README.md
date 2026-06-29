# Linux Hardening Audit Tool

An automated Python-based security compliance auditing tool designed to assess the defensive posture of a Linux system.

## Features
* Audits critical system file permissions (`/etc/passwd` and `/etc/shadow`).
* Verifies the operational status of the Uncomplicated Firewall (UFW).
* Generates a real-time compliance score dashboard.

## Requirements
* Operating System: Linux (Tested on Kali Linux)
* Language: Python 3

## How to Run
Open your Linux terminal, navigate to the project directory, and execute the following command:

```bash
sudo python3 audit.tool.py
