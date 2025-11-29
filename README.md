## 🐍 Python Reverse Shell (Basic Reverse Shell Backdoor)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Socket-TCP-green?style=for-the-badge&logo=pypi">
  <img src="https://img.shields.io/badge/Purpose-Educational-red?style=for-the-badge">
</p>

---

## 💡 Project Overview

This repository contains the code for a basic **Reverse Shell** (Backdoor) developed using the **Python `socket`** module. This project is designed to demonstrate how an attacker's machine (the Listener) can receive a connection from a target machine (the Backdoor) and remotely execute commands.

The primary goal is to **increase cybersecurity awareness** by illustrating the core mechanics of such tools, which is crucial for building effective defensive measures.

### Key Features
* **Simple TCP Connection:** Establishes a reliable connection using Python's standard `socket` library.
* **Remote Command Execution:** Executes shell commands on the target system using the `subprocess` module.
* **JSON Data Transfer:** Commands and output are transmitted using the JSON format to ensure data integrity during transfer.
* **Change Directory (CD) Support:** Ability to change the working directory on the target machine using the `os` module.

---

## 🚨 Legal Disclaimer and Responsibility

<p align="center">
    <b>THIS SOFTWARE IS STRICTLY FOR CYBERSECURITY EDUCATION AND AWARENESS ONLY.</b>
</p>

* The purpose of this code is to **educate on cybersecurity principles** and show how malicious software operates.
* The use of this software against any system, network, or device **without explicit, prior authorization is illegal and punishable by law.**
* The developer/contributor of this project **is not responsible** for any misuse or malicious actions resulting from the use of this code.
* The user is **solely responsible** for the ethical and legal implications of using this software.

---

## 🛠️ Requirements & Setup

* **Python 3.x**
* Standard Python Libraries (`socket`, `json`, `subprocess`, `os`)

### Usage (Simulated)

1.  **Start the Listener** (Attacker Machine):
    ```bash
    python listener.py
    ```
2.  **Execute the Backdoor** (Target Machine):
    ```bash
    python backdoor.py
    # or the executable created via PyInstaller
    ./backdoor_executable
    ```
3.  **Enter commands** through the Listener terminal once a connection is established.

---

## 📺 Detailed Explanation: YouTube Video

The complete development process and a detailed explanation of the code, titled **"Python İle Kendi Virüsümü Yazdım | Eğitim Amaçlı"** (I Wrote My Own Virus With Python | For Educational Purposes) by the **Furares** channel, are covered in the video below.

<p align="center">
  <a href="https://youtu.be/wj76ClEge_s">
     
  </a>
  <br>
  <a href="https://youtu.be/wj76ClEge_s">
    <h3>▶️ PYTHON İLE KENDİ VİRÜSÜMÜ YAZDIM | EĞİTİM AMAÇLI</h3>
  </a>
  <br>
  **Channel:** Furares | **Published:** 2025-11-26 | **Duration:** 23:29
</p>
