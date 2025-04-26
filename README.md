# Educational Python Keylogger

> ⚠️ This project is for **educational purposes only**. Do not use it for malicious activities.

## 📄 About
This is a simple Python-based keylogger designed to demonstrate:
- How attackers capture keyboard inputs.
- How antivirus software detects (or misses) basic malware.
- How to defend systems by understanding attacker techniques.

The logs are encrypted before saving to disk to simulate realistic malware behavior.

---

## 🛠️ Technologies Used
- Python 3
- pynput (for keyboard event capture)
- cryptography (for encryption)

---

## 🚀 How to Run
1. Install required libraries:
    ```
    pip install -r requirements.txt
    ```
2. Run the script:
    ```
    python improved_keylogger.py
    ```
3. (Optional) Convert to `.exe` using PyInstaller:
    ```
    pyinstaller --onefile --noconsole improved_keylogger.py
    ```

---

## 🔥 Educational Value
- Understanding basic malware behavior.
- Learning Python packaging and obfuscation basics.
- How antivirus software analyzes binaries.
- Ethics in cybersecurity and malware development.

---

## ⚡ Important
- **DO NOT use this tool maliciously.** 
- **Only for learning, analysis, and defensive security research.**
- Violations can lead to serious legal consequences.

