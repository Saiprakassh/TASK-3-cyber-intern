# TASK-3-cyber-intern
# 🔐 Task 3: Basic Vulnerability Scan Using Nessus Essentials

## 🎯 Objective
Perform a vulnerability scan on your local machine using **Tenable Nessus Essentials** to identify potential security issues, understand their severity levels, and gain hands-on experience with vulnerability assessment tools.

---

## 🧰 Tools Used

- **Nessus Essentials** – A free vulnerability scanning tool by Tenable.
- **Localhost / Personal EC2 Instance** – Used as the scan target.
- **CVSS v3.0** – Common Vulnerability Scoring System for rating severity.

---

## 📸 Screenshot Summary

- **Target:** `ec2-3-228-249-3.us-west-2.compute.amazonaws.com`
- **Scan Policy:** Host Discovery
- **Scan Status:** ✅ Completed
- **Scanner:** Local Scanner
- **Start Time:** 11:35 AM
- **End Time:** 11:37 AM
- **Duration:** 2 minutes

---

## 🔍 Vulnerability Scan Results

| Severity | Detected | Description |
|----------|----------|-------------|
| 🔴 Critical | 0 | No critical vulnerabilities found |
| 🟠 High     | 0 | No high-severity issues |
| 🟡 Medium   | 0 | System appears free of mid-level risks |
| 🔵 Low      | 0 | No low-priority issues |
| ⚪ Info     | ✔️ Few | Informational alerts present |

### ✅ Interpretation:
- The scan found **no actionable vulnerabilities**, indicating the system is either very secure or the scan was limited (e.g., unauthenticated or shallow).
- A few **informational findings** suggest that basic fingerprinting and host data were collected, which is normal in a discovery scan.
- The scan was configured as **Host Discovery**, meaning it primarily checked whether the target host is alive and collected passive data. No deep vulnerability tests were run.

---

## 🧠 Learnings and Key Concepts

- **Vulnerability Scanning** identifies known flaws in software, configurations, or missing patches.
- **Penetration Testing** is a more advanced, manual process to exploit vulnerabilities.
- **CVSS** helps assess risk levels and prioritize patching efforts.
- **Informational results** are not dangerous but can assist attackers in gathering system details.
- It’s important to run **authenticated full scans** for deeper insights.

---

## 📁 Deliverables

- ✅ Completed Nessus Scan
- ✅ Screenshot of Results
- ✅ This README with Analysis and Explanation

---

## 📚 Suggestions for Improvement

- Upgrade the scan from “Host Discovery” to “Basic Network Scan” or “Advanced Scan.”
- Configure **authenticated scans** to detect vulnerabilities in installed software, services, and open ports.
- Research and address any informational alerts from the full report.

---

## 🔗 Submission

- Submit the GitHub repository containing:
  - 📸 Screenshots
  - 📄 README.md
  - 🔗 [Google Form Submission Link](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## ✅ Status: Completed and Submitted
