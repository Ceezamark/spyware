# Keylogger Project

## Overview
This project is a simple keylogger written in Python. It is designed to record keystrokes on a target machine and send the captured data via email for later analysis. The main script is `ServiceHost.py`, and the code is obfuscated for added stealth.

## Features
- Captures all keystrokes made on the system
- Can run in the background
- Stores logs locally or can be extended to send logs remotely

## Requirements
- Python 3.x
- See `requirements.txt` for dependencies

**It is strongly recommended to use a virtual environment and run this script only on a virtual machine (VM) or a machine you do not use for personal or important work. For best compatibility, use a Linux or Kali machine.**

## Usage
1. Create and activate a virtual environment (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the keylogger:
   ```bash
   python ServiceHost.py
   ```

## Disclaimer
This software is for demonstration and authorized testing purposes only. It is not licensed for commercial or production use. Unauthorized use of this software to monitor or record others without their consent is illegal and unethical. The author assumes no responsibility for any misuse of this tool.

**Run this tool only in a controlled, isolated environment such as a VM or a non-personal machine, preferably running Linux or Kali. Do not use on your main or personal computer.**
