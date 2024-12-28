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
