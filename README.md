# Reunion 2026 Registration System (DevSecOps Edition)

A secure, automated event registration pipeline built for the Class of 95/97 Reunion. This project demonstrates a serverless architecture integrating a custom frontend with a Google Cloud backend, hardened through real-world troubleshooting.

## 🚀 Evolution of the Project
What started as a simple form evolved into a deep dive into **Cross-Origin Resource Sharing (CORS)**, **Deployment Versioning**, and **Identity Access Management (IAM)**. 

### Key Technical Challenges Solved:
* **Version Control & Deployment:** Managed multiple iterations of Google Apps Script (Version 1-7) to align frontend `fetch` requests with backend logic.
* **The "Silent Failure" Bug:** Debugged a critical issue where the frontend reported success while the backend remained empty due to restrictive IAM permissions (Apps Script access set to "Only me" instead of "Anyone").
* **State Management:** Resolved execution errors related to `undefined` event parameters by simulating real POST requests rather than manual script execution.
* **Security Integration:** Maintained a Checkov scan pipeline to ensure the public repository adheres to security best practices throughout the rapid debugging phase.

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+)
* **Backend:** Google Apps Script (JavaScript)
* **Database:** Google Sheets API
* **Security:** Bridgecrew Checkov (Static Analysis)

## 📂 Project Structure
* `index.html`: The main registration interface with integrated `fetch` logic.
* `.github/workflows/`: Automated security scanning pipelines.
* `Code.gs`: Serverless backend processing form data and triggering Gmail notifications.

**Lead Engineer:** Frank Fru  
**Role:** SOC Analyst / DevSecOps Engineer
