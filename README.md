# 💣 BOYKISSER.TROJAN

> ⚠️ **WARNING:** This program is **malicious software** designed for **educational purposes only**.  
> It mimics a Windows 10 update but **destroys the Master Boot Record (MBR)**, rendering the system **unbootable**.  
> **DO NOT RUN on your host machine or any production environment.**
---

## 🧪 Recommended Environment

This project must **only** be executed in an isolated virtual machine.  
I recommend using:

- [QEMU/KVM](https://www.qemu.org/)
- [VMware Workstation](https://www.vmware.com/products/workstation-pro.html)
- [VirtualBox](https://www.virtualbox.org/)

Make sure the VM has **no shared folders**, **no network access**, and **no critical data**.

---

## 🎯 Purpose

This project is intended for:

- Learning how malware interacts with low-level system components
- Understanding the risks of running untrusted executables
- Demonstrating the importance of system backups and boot protection

---

## ⚠️ Disclaimer

**I am not responsible for any damage caused by the misuse of this software.**  
By downloading, compiling, or executing this code, you agree that you are doing so at **your own risk** and in a **controlled environment**.

This software is provided **"as is"** without any warranty of any kind.  
Do not redistribute this program as legitimate software.

---

## 🖼️ Screenshot

![screenshot](screenshot.png)  
*Example of the fake Windows 10 updater interface before execution.*

---

## 🧠 Educational Takeaways

- Never run unknown executables, especially those claiming to be system updates
- Always verify the source and integrity of software
- Understand how bootkits and MBR viruses operate at a low level
- Use virtualization for malware analysis and reverse engineering

---
