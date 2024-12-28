# BurpSuite Academy: Learning Web Application Security

Welcome to **BurpSuite Academy**, a repository documenting my progress and practice with web application security techniques through **PortSwigger Academy**. This repository contains hands-on exercises and notes on various security vulnerabilities, including SQL injection, clickjacking, and cross-site scripting (XSS).

---

## 📂 File Structure

Here’s an overview of the repository's contents:

### **1. SQL Injection**
- **File:** `SQL Injections.md`
- **Description:** A detailed markdown file containing:
  - Notes on different types of SQL injection attacks.
  - Techniques to identify and exploit SQL injection vulnerabilities.
  - Mitigation strategies for preventing SQL injections.
- **Use Case:** Serves as a reference for understanding SQL injection concepts and exercises from PortSwigger Academy.

---

### **2. Clickjacking**
- **File:** `clickjacing.html`
- **Description:** A simple example of a clickjacking attack, demonstrating how an attacker can trick users into clicking on hidden or disguised elements.
- **Use Case:** Learn how clickjacking works and how to identify it during pentesting.

- **File:** `clickjackingMultistep.html`
- **Description:** A multi-step clickjacking attack example, showcasing advanced techniques where users are tricked into performing multiple steps (e.g., confirming sensitive actions).
- **Use Case:** Explore the risks of clickjacking combined with multi-step actions in applications.

---

### **3. Clickjacking with XSS**
- **File:** `clickjackingwithxss.html`
- **Description:** Combines clickjacking techniques with XSS (cross-site scripting) to execute malicious scripts. This example illustrates how attackers can escalate clickjacking attacks by injecting scripts.
- **Use Case:** Understand how combining vulnerabilities can amplify their impact.

---

## 🚀 Quick Start

### Prerequisites
- A web browser to open `.html` files.
- Burp Suite Community or Professional edition for practicing web security.

### Running HTML Files
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BurpSuite-academy.git
   ```
2. Open the `.html` files in a browser to view examples of clickjacking attacks:
   - Double-click the file to open it in your default browser.
   - Alternatively, use:
     ```bash
     open filename.html
     ```

---

## 🎯 Purpose

This repository is part of my learning journey in web application security. By practicing and documenting these exercises, I aim to:
- Understand common web vulnerabilities like SQL injection and clickjacking.
- Learn exploitation techniques for ethical hacking and pentesting.
- Explore effective mitigation strategies to secure applications.

---

## ⚠️ Disclaimer

These materials are for educational purposes only. Use them responsibly and only on applications you are authorized to test. Unauthorized use of these techniques may violate laws and ethical guidelines.

---

## 🤝 Contributions

This repository is personal, but feedback and suggestions are welcome! If you have ideas for improvement or additional examples, feel free to reach out or open an issue.

---

## 📜 License

This repository is licensed under the [MIT License](LICENSE).

---

## 🌟 Acknowledgments

- [PortSwigger Academy](https://portswigger.net/web-security): For providing an excellent learning platform for web application security.
- The cybersecurity community for sharing knowledge and resources.

---

Happy learning! 🔒
