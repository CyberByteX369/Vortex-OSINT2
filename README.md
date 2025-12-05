# 🌪️ Vortex-OSINT

**Advanced Passive Intelligence Gathering Tool**

Vortex-OSINT is a Python-based reconnaissance tool designed for ethical hackers and security researchers. It automates the process of gathering public intelligence (OSINT) from social media and deep web sources without alerting the target.

## 🚀 Features

* **Tor Circuit Routing:** Options to route traffic through the Tor network to mask the investigator's IP address.
* **Metadata Extraction:** Retrieves permanent User IDs, verified status, and business category info.
* **Breach Detection:** Scans for username association in known data leaks (Simulated/API Ready).
* **Report Generation:** Automatically saves all intelligence to a local text file.
* **Passive Recon:** Designed to gather data without direct interaction (no pings/DMs).

## 📦 Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Vortex-OSINT.git](https://github.com/YOUR_USERNAME/Vortex-OSINT.git)
    cd Vortex-OSINT
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  (Optional) Start Tor Service:
    * Ensure Tor Browser or the Tor service is running on port 9050.

## 🛠️ Usage

Run the main script:

```bash
python src/vortex.py
