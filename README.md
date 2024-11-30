# **Custom Nuclei Templates**

![Nuclei](https://img.shields.io/badge/Nuclei-Templates-blue)  
A collection of custom **Nuclei templates** designed to identify web application vulnerabilities and assist in reconnaissance for web and API testing. These templates have been tailored for both beginner and intermediate use cases, offering robust detection capabilities and practical use.

---

## **📋 Table of Contents**
1. [Introduction](#introduction)
2. [Features](#features)
3. [Template List](#template-list)
4. [How to Use](#how-to-use)
5. [Prerequisites](#prerequisites)
6. [Contributing](#contributing)
7. [License](#license)

---

## **💡 Introduction**
This repository contains **custom Nuclei templates** that can be used to identify vulnerabilities in web applications and APIs. Each template is designed to detect specific security issues, making it easier for penetration testers and security researchers to perform accurate scans.

---

## **✨ Features**
- **Custom Templates**: Unique templates not available in the default Nuclei library.
- **Comprehensive Detection**: Focused on identifying misconfigurations, outdated software, missing security headers, and other vulnerabilities.
- **Beginner & Intermediate Use Cases**: Templates range from simple to more complex detection techniques.

---

## **📂 Template List**
Here are the templates included in this repository:

1. **HTTP Header Misconfiguration**  
   Detects sensitive information leaked through HTTP headers (e.g., `Server`, `X-Powered-By`).

2. **JWT Token Issues**  
   Identifies misconfigured or vulnerable JSON Web Tokens (JWTs) in applications.

3. **Outdated Software Versions**  
   Checks for outdated versions of popular web servers, frameworks, and libraries.

4. **CORS Misconfiguration**  
   Detects improper CORS configuration that could lead to unauthorized data sharing.

5. **Missing Security Headers**  
   Scans for missing HTTP security headers like `Content-Security-Policy`, `Strict-Transport-Security`, etc.

---

## **🚀 How to Use**
Follow these steps to use the templates:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/custom-nuclei-templates.git
   cd custom-nuclei-templates
   ```
2. Run Nuclei with the custom templates:
   ```bash
   nuclei -u <TARGET_URL> -t ./templates/
   ```
3. (Optional) Run a specific template:
   ```bash
   nuclei -u <TARGET_URL> -t ./templates/http-header-misconfiguration.yaml
   ```
   
---

## **⚙️ Prerequisites**
1. **Nuclei: Ensure Nuclei is installed on your system.**
2. **Installation Guide: Nuclei Documentation.**
3. **Python (Optional): For advanced template scripting with Nuclei.**
