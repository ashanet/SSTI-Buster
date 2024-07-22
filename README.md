# SSTI-Buster
SSTI-Scanner detects server-side template injection vulnerabilities and tests for code injection capabilities. With various payloads and methods, this tool scans web pages to identify SSTI flaws, aiding security professionals in finding and exploiting template-related vulnerabilities effectively.

# **SSTI-Scanner**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Security](https://img.shields.io/badge/Security-Scanner-green.svg)

## 🚀 Introduction

**SSTI-Scanner** is a robust and versatile tool designed to identify and exploit Server-Side Template Injection (SSTI) vulnerabilities in web applications. This tool automates the detection of SSTI flaws, allowing security professionals and ethical hackers to perform in-depth security assessments and discover potential exploits effectively.

## 🌟 Features

- 🔍 **Comprehensive SSTI Detection:** Identifies a wide range of SSTI vulnerabilities using diverse payloads.
- 💡 **Payload Variety:** Utilizes numerous payloads from different projects to ensure thorough testing.
- 🛠 **Customizable Testing:** Easy to add or modify payloads to fit specific requirements.
- 📜 **Detailed Reports:** Provides detailed output on detected vulnerabilities and potential exploits.

## 📥 Installation

### Prerequisites

- Python 3.8 or higher
- Required libraries: `requests`, `beautifulsoup4`

### Install Libraries

```sh
pip install -r requirements.txt
```
1-Clone the Repository
  ```sh
git clone https://github.com/YourUsername/SSTI-Scanner.git
```
2-Navigate to Project Directory
```sh
cd SSTI-Scanner
```
3-🛠 Usage
To start scanning for SSTI vulnerabilities, use the following command:

```sh
python ssti_scanner.py <url>
```
⚙️ Configuration
You can customize the payloads by modifying the payloads.txt file. Each line should contain a different payload to be tested.

🔄 Updating Payloads
To add or update payloads, simply edit the payloads.txt file. Ensure that you test new payloads thoroughly.

📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

📧 Contact
For any questions or inquiries, please contact r90c09r@gmail.com .

Happy scanning!
