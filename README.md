# Reunion 2026 Registration System

A secure, automated event registration pipeline built for the Class of 95/97 Reunion. This project demonstrates a serverless architecture integrating a custom frontend with a Google Cloud backend.

## 🚀 Features
- **Serverless Backend:** Uses Google Apps Script to process form data.
- **Automated Database:** Real-time data synchronization with Google Sheets.
- **Security First:** Implements a secret-pin authentication layer on the frontend.
- **CI/CD Security:** Integrated **Checkov** via GitHub Actions to scan for infrastructure-as-code misconfigurations.
- **Responsive Design:** Built with Tailwind CSS for mobile and desktop compatibility.

## 🛠️ Tech Stack
- **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6)
- **Backend:** Google Apps Script (JavaScript)
- **Hosting:** GitHub Pages
- **Security Scans:** Bridgecrew Checkov

## 🔒 Security Implementation
The project includes a GitHub Action workflow located in `.github/workflows/security-scan.yml` that runs a **Checkov scan** on every push. This ensures that the code follows security best practices for public repositories.

## 📂 Project Structure
- `index.html`: The main registration interface.
- `.github/workflows/`: Automated security scanning pipelines.
- `README.md`: Project documentation.

---
**Lead Engineer:** [Frank Fru](https://github.com/chifru19)  
**Role:** SOC Analyst / DevSecOps Engineer