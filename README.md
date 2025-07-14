# Prodigy_Task3 – Password Strength Checker

This task focuses on implementing a real-time password strength checker in Python. It evaluates passwords based on standard security criteria and provides direct user feedback for improvement. The tool simulates basic password validation features found in many authentication systems.

🎯 Objective

Build a tool that assesses password strength based on length, use of uppercase and lowercase letters, digits, and special characters. Provide helpful tips and feedback.

 🛠 Tools

- Python 3.x
  
📦 Deliverables

- `password_checker.py`: Python script for real-time password strength checking
- Live feedback for each missing password criterion
- Strength classification: Weak, Moderate, or Strong
- Loop to evaluate multiple passwords in one session

 🧭 Guide

1. Run the script using Python:
   ```bash
   python password_checker.py

📂 File Description
The script evaluates:

Criteria	Description
Length	Minimum 8 characters
Lowercase	At least one lowercase letter (a–z)
Uppercase	At least one uppercase letter (A–Z)
Numbers	At least one numeric digit (0–9)
Special Characters	At least one symbol (!@#$...)

📌 Strength Output
Strength Score	Message
0–2	🔴 Weak Password
3–4	🟡 Moderate Password
5	🟢 Strong Password

✅ Outcome
A functional and interactive password strength checker built in Python, offering guidance to create secure passwords.

