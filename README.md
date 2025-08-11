# PowerShell-Script-System-Info-Collector-
"PowerShell automation tool for quickly collecting key system details — OS version, CPU specs, and storage — useful for IT support, troubleshooting, and hardware inventory."
# 🖥️ System Info Collector (PowerShell Script)

## 📌 Overview
The **System Info Collector** is a PowerShell script that gathers key system details for IT troubleshooting, inventory tracking, and help desk support.  
It provides quick insights into:
- Operating System details  
- CPU specifications  
- Disk storage information  

This project is part of my IT home lab portfolio to demonstrate automation skills in PowerShell.

---

## ⚙️ Features
- Retrieves **OS name, version, architecture, and build number**.
- Displays **CPU model, core count, and clock speed**.
- Lists **storage devices with size and free space in GB**.
- Saves a **report to a text file** for easy reference.

---

## 🛠️ Step-by-Step Process

### **Step 1 – Creating the Script**
I wrote a PowerShell script named `SystemInfoCollector.ps1` that collects system information and formats it in an easy-to-read report.  

📷 *Screenshot 1: The script opened in VS Code or PowerShell ISE*  
<img width="949" height="619" alt="Screenshot 2025-08-11 at 12 32 02 PM" src="https://github.com/user-attachments/assets/3237c53a-ba6d-43b1-88dd-7501b4491533" />

<img width="1002" height="610" alt="Screenshot 2025-08-11 at 12 34 44 PM" src="https://github.com/user-attachments/assets/dcc47283-8e75-499e-ba3b-4b7463880b69" />

---

### **Step 2 – Saving the Script**
I saved the script to my Desktop for easy access:  

📷 *Screenshot 2: Script file saved on the Desktop*  
<img width="1002" height="610" alt="Screenshot 2025-08-11 at 12 34 44 PM" src="https://github.com/user-attachments/assets/ef105501-fa9c-42b3-ba7a-e80cf27db809" />

---

### **Step 3 – Running the Script**
To execute the script, I used:
```powershell & "C:\Users\Arif\Desktop\SystemInfoCollector.ps1"

*Screenshot 3:*
<img width="1020" height="623" alt="Screenshot 2025-08-11 at 12 39 06 PM" src="https://github.com/user-attachments/assets/8f683826-5d48-4528-b048-1a4c3d1e2af8" />

<img width="938" height="623" alt="Screenshot 2025-08-11 at 12 55 05 PM" src="https://github.com/user-attachments/assets/71abcaa8-8bcd-4988-aabd-3fbe76c04d08" />

---

### **Step 4 – Generating the Report File**
The script also saved the output to:
C:\Users\Arif\Desktop\SystemInfoReport.txt

📷 Screenshot 4: SystemInfoReport.txt file visible on Desktop

<img width="1028" height="659" alt="Screenshot 2025-08-11 at 1 07 05 PM" src="https://github.com/user-attachments/assets/abf183e8-5b45-4063-8659-6fd03432ae22" />


📷 Screenshot 5: Report opened in Notepad showing results
<img width="932" height="583" alt="Screenshot 2025-08-11 at 12 55 29 PM" src="https://github.com/user-attachments/assets/116fa493-7079-4135-8f21-609da64dfb8d" />
