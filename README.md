# 🌪️ VORTEX-OSINT
### Advanced Passive Intelligence & Digital Footprinting Framework

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-red?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20MacOS-lightgrey?style=for-the-badge)

```text
██╗   ██╗ ██████╗ ██████╗ ████████╗███████╗██╗  ██╗
██║   ██║██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝╚██╗██╔╝
██║   ██║██║   ██║██████╔╝   ██║   █████╗   ╚███╔╝ 
╚██╗ ██╔╝██║   ██║██╔══██╗   ██║   ██╔══╝   ██╔██╗ 
 ╚████╔╝ ╚██████╔╝██║  ██║   ██║   ███████╗██╔╝ ██╗
  ╚═══╝   ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝
                                       v1.0.0
```
📖 Overview
Vortex-OSINT is a specialized reconnaissance tool designed for Red Teamers, Security Analysts, and Ethical Hackers. Unlike noisy active scanners that alert targets, Vortex focuses on Passive Open Source Intelligence (OSINT).

It correlates data from social media, deep web breach databases, and public metadata to generate a comprehensive "Digital Identity" report without ever sending a direct packet to the target's personal device.

⚡ Features
🕵️‍♂️ Passive Reconnaissance: Gathers data without interacting with the target (No likes, follows, or DMs).

🧅 Tor Circuit Routing: Optional module to route requests through the Tor Network (Port 9050) for anonymity.

📊 Metadata Extraction: Retrieves permanent User IDs, active hours analysis, and account creation dates.

🔓 Breach Correlation: Cross-references usernames with known data leaks (simulated/API-ready).

📝 Auto-Reporting: Generates clean, timestamped .txt dossiers for evidence collection.

🚫 Anti-Phishing: Zero social engineering vectors. Pure data aggregation.

🛠️ Installation
Prerequisites
Python 3.8+

Tor Browser / Tor Service (Optional, for Dark Web module)

Setup
Bash

# 1. Clone the repository
```bsh
git clone https://github.com/CyberByteX369/Vortex-OSINT2.git
```

# 2. Enter the directory
```bash
cd Vortex-OSINT2
```

# 3. Install dependencies
``` bash
pip install -r requirements.txt
```

# 🚀 Usage
Run the main framework:

Bash
```bash
python src/vortex.py
```
The tool will check for a Tor connection.

Enter the target Username when prompted.

Wait for the Multi-Threaded Scan to complete.

Check the root directory for the generated report_[target].txt.

# 📂 Project Structure
Plaintext
``` plainext
Vortex-OSINT2/
├── src/
│   ├── vortex.py          # Core Logic & Scanner
│   └── modules/           # (Future) Pluggable modules
├── evidence/              # Downloaded Avatars/Logs
├── requirements.txt       # Dependencies
├── LICENSE                # MIT License
└── README.md              # Documentation
```
# 🗺️ Roadmap
[x] Instagram Metadata Extraction

[x] Tor Proxy Support

[ ] Twitter/X API Integration

[ ] Reverse Image Search Automation (PimEyes/TinEye)

[ ] PDF Report Generation

# ⚠️ LEGAL DISCLAIMER
PLEASE READ BEFORE USING

Vortex-OSINT is developed for EDUCATIONAL and RESEARCH purposes only.

Authorization: This tool is intended to be used by security professionals to audit their own footprints or by authorized Red Teams with explicit permission from the target.

Liability: The developer (Your Name) accepts no responsibility for any misuse of this software. The end-user is solely responsible for compliance with all local, state, and federal laws.

Prohibited Use:

Do not use this tool for cyberbullying, stalking, or harassment.

Do not use this tool to access accounts you do not own.

GDPR/Privacy: Respect the privacy of individuals. Collecting PII (Personally Identifiable Information) without consent may be illegal in your jurisdiction (e.g., GDPR in Europe, CCPA in California).

By cloning or downloading this repository, you agree to these terms.

<p align="center"> <sub>Built with 💀 and 🐍 by <a href="https://www.google.com/search?q=https://github.com/YOUR_USERNAME">CyberByteX</a></sub> </p>
