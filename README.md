# Task 1 – Network Port Scanning 🔍

## 🎯 Objective:
To discover open ports on a device in the local network using Nmap, to understand potential security exposure.

## 🛠️ Tools Used:
- Nmap 7.97
- Windows 10 Command Prompt

## 🌐 IP Scanned:
10.20.41.210 (my own device)

## 🔍 Command Used:
nmap -sS -Pn 10.20.41.210 -oN scan_results.txt

## 📄 Results Summary:
- Host was up and responded to scan
- Open Ports Detected:
  - 135/tcp – Microsoft RPC
  - 139/tcp – NetBIOS Session Service
  - 445/tcp – Microsoft-DS File Sharing


## 🔐 Security Notes:
These ports are commonly used in Windows environments and should be properly firewalled when not in use to avoid remote exploitation.

## 📁 Files Included:
- scan_results.txt – Nmap output
- README.md – Task description and analysis
