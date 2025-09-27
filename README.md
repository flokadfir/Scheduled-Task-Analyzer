# 🕵️‍♂️ Scheduled Task Analyzer
**Scheduled Task Analyzer** is a Windows tool that parses and analyzes Scheduled Tasks, identifies suspicious or unusual tasks, and helps with security auditing and forensic investigations.  


---

## ⚙️ Features

- 🔍 Scans all **Scheduled Tasks**  
- ⚠️ Flags **suspicious or unusual tasks**  
- 📄 Generates **CSV export or Html Export** for further analysis  
- 💻 Lightweight and **GUI friendly**  

---

## 📝 Usage
Download And run TaskAnalyzer.exe and chose a full scan or quick scan

---

## 🚨 Detections meanings

**triggers:** 

**CUSTOM ( flagged when a user makes a custom event filter or condition)** 

**TIME ( flagged when a user sets it to trigger at a specific date/time)** 

**REGISTRATION ( triggers when the task is created / made )** 

**BOOT ( when a user sets it to trigger when the system is booting up)** 

**LOGON ( same as above )**

------------------------
~Status~

**READY ( waiting for set trigger )** 

**RUNNING ( the task is running )** 

**DISABLED ( the task exists but is turned of )** 

**QUEUED ( task is waiting to run)** 

**FAILED ( task failed to run )**



