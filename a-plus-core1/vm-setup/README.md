# VM Homelab Setup

## 📌 Summary
Install & configure virtualization platforms

## 🎯 Objectives
- Install VirtualBox
- Spin up Win 10/11 and a Linux VM
- Document with screenshots

## 🧰 Environment Setup
- ThinkPad T480
- VirtualBox 7.2.4
- Windows 10/11 VM - 2 CPU, 4GB RAM, 80GB disk  
- Ubuntu Desktop VM - 2 CPU, 4GB RAM, 25GB disk 



## 🧪 Step-by-Step Procedures
1. Download and install VirtualBox
2. Create a base VM template
3. Create two VMs

## 🖼️ Screenshots
<p align="center">
Download & Install VirtualBox: <br/>
<img src="https://i.imgur.com/cJAffZD.png" height="80%" width="80%">
<br/>
<br/>
Create Ubuntu virtual machine: <br/>
<img src="https://i.imgur.com/0rxc7F6.png" height="80%" width="80%">
<br/>
<br/>
Ubuntu clean install: <br/>
<img src="https://i.imgur.com/UDeALSi.png" height="80%" width="80%">
<br/>
<br/>
Create Windows virtual machine: <br/>
<img src="https://i.imgur.com/CS1TzVA.png" height="80%" width="80%">
<br/>
<br/>
Windows clean install: <br/>
<img src="https://i.imgur.com/4w5BCbT.png" height="80%" width="80%">
<br/>
<br/>

</p>

## ⚙️ Configurations

- IP:
- OS: Ubuntu Desktop
- Version: 24.04.3
- Notes:
- IP:
- OS: Windows
- Version: 11
- Notes:

## 🛠️ Troubleshooting Logs

Ubuntu Desktop
- Issue: Missing Microsoft Visual C++ 2019 Redistributable Package
- Symptom: Unable to install VirtualBox
- Root Cause: Visual C++ 2017 installed, VirtualBox requirement
- Fix: Download both x86 and x64 versions of the multi-installer Visual C++ 2015, 2017, 2019 and 2022 redistributable

## 📚 Lessons Learned
What you gained from this project.

## 🚀 Future Improvements
Ideas for expanding or refining the project.

