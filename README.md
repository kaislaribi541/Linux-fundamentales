# 🐧 Linux Fundamentals Mastery - TryHackMe

This repository documents my journey and technical skills acquired during the **Linux Fundamentals** series on TryHackMe. As a Junior Cybersecurity Learner, mastering the Linux command line is the core of my operations, from server security to automation.

---

## 🛠️ Technical Skills Acquired

### 1. File Management & Navigation
* Advanced navigation using `cd`, `ls -la`, and `pwd`.
* Searching for specific data using `find` and `grep` with regex patterns.
* Managing file permissions (`chmod`) and ownership (`chown`) to secure sensitive data.

### 2. Networking & Data Transfer
* Transferring files securely between machines using **SCP** and **Wget**.
* Deploying a temporary web server for file sharing:
    ```bash
    python3 -m http.server 8000
    ```
* Analyzing network connections and remote access via **SSH**.

### 3. System Administration & Automation
* **Process Management:** Monitoring system health with `ps aux` and `top`.
* **Service Control:** Managing system daemons using `systemctl` (start, stop, enable).
* **Crontabs:** Automating tasks and scripts using Cron jobs:
    * Example: `@reboot /path/to/script.sh` for persistence.

### 4. Log Analysis (Forensics Basics)
* Investigating system and application logs in `/var/log`.
* Analyzing Apache access logs to identify intruder IPs and accessed resources.
* Understanding HTTP status codes (200 OK, 404 Not Found, 403 Forbidden).

---

## 🔍 Key Lab Highlights
* **Task:** Identifying a hidden process flag.
* **Method:** Used `ps aux | grep THM` to find a running process disguised as a flag.
* **Task:** Retrieving a hidden flag from a remote server.
* **Method:** Established an SSH tunnel, hosted the file via Python HTTP server, and retrieved it using `wget`.

---

## 🚀 Projects in Progress
* **insta-api:** A Python-based automation tool for Instagram, currently being optimized for Linux server deployment using the skills practiced here.

---

## 👤 Profile
* **Role:** Junior Cybersecurity
* **Location:** Tunisia 🇹🇳
* **Interests:** Automotive Engineering (BMW E39 S62), Aviation, and High-Performance Computing.
