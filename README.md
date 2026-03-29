# oss-audit-24BCE0187

# oss-audit-24BCE10187

**Student Name:** Tanish Tailor
**Roll Number:** 24BCE10187
**Chosen Software:** Python
**License:** PSF License 
**Submission Date:** March 2026

---

## About This Project

This repository is part of the Open Source Audit capstone project for the OSS NGMC course. 
-The project involves a structured audit of Python as an open-source software — covering its origin, license, ethics, Linux footprint, and ecosystem. Alongside the written report,
-five shell scripts are included that demonstrate practical Linux and bash scripting skills.

---

## Repository Structure
```
oss-audit-24BCE10187/
|
|── README.md
|──report/
  └── THE OPEN SOURCE AUDIT(python)
scripts/
   ├── script1.sh
   ├── script2.sh
   ├── script3.sh
   ├── script4.sh
   └── script5.sh
```

## The Scripts Overview provides an overview of each script file and what it does.

| Script | File | Description |
| ---- | ---- | ---- |
| 1 | script1_system_identity.sh | Display's (system info -kernel, user, uptime, date and license note) |
| 2 | script2_package_inspector.sh | Checks if Python is installed and prints out a philosophy note |
| 3 | script3_disk_auditor.sh | Audits key directories for (permissions, ownership and size) |
| 4 | script4_log_analyzer.sh | Scans (log file) for keyword(s) and counts occurrences |
| 5 | script5_manifesto.sh | Interactive Manifesto Generator saved to a .txt file.


## Dependencies

- **OS:** Any Linux distribution (tested on Ubuntu via WSL)
- **Bash:** Pre-installed on all Linux systems
- **Python 3:** Install using `sudo apt install python3`
- **Git:** Install using `sudo apt install git
- ---


### Running the scripts


### 1. Clone the repo
```bash
git clone https://github.com/your_github_username/oss-audit-[roll_number].git
cd oss-audit-[roll_number]
```


### 2. Make the scripts executable
```bash
chmod +x *.sh
```


### 3. Execute all scripts


**Script 1 - System Identity Report**
```bash
./script1_system_identity.sh
```


**Script 2 - FOSS Package Inspector**
```bash
./script2_package_inspector.sh
```


**Script 3 - Disk and Permissions Auditor**
```bash
./script3_disk_auditor.sh
```


**Script 4 - Log Analyzer**
```bash
./script4_log_analyzer.sh /var/log/syslog error
```
> Change `/var/log/syslog` to any log file path, change `error` to any word you want to use to search logs.


**Script 5 - Open Source Manifesto Generator**
```bash
./script5_manifesto.sh
```
> This is an interactive script — it will ask you three questions and create a `.txt` file containing your generated manifesto.


---
