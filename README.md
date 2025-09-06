# ⚡ wFetch – Ultra-fast Windows Fetch Tool  

> A blazing fast, lightweight system information fetcher for Windows 10/11.  
> Think Task Manager’s performance tab, but instant and terminal-based(for all the cli fanboys), and without lower end devices overheating.  

## ✨ Features
- **Insanely fast** (~0.03s runtime)  
- CPU info (architecture, name, cores)  
- RAM stats (total + available)  
- OS detection (Windows 10/11, build numbers)  
- Disk usage (total + free space)  
- Network adapters (active interfaces, friendly names)  
- GPU detection (via DXGI, no integrated GPUs supported yet!!)  

## 📸 How it looks
<img width="1480" height="752" alt="image" src="https://github.com/user-attachments/assets/694d1ab9-8da1-4c4f-837e-3a0654b08765" />

## 📥 Installation
1. Download the latest release from [Releases](https://github.com/dogalesz/wFetch/releases).  
2. Run `wFetch.exe` from you where downloaded it to.

## ⚖️ Licensing
Licensed under the MIT License.
This means you can use, modify(if I drop the source code lol), and share wFetch freely.  

## 🌟 Why?
- Most “fetch” tools for Windows are slow (they use WMI under the hood).  
- wFetch is written purely in C and uses direct Windows APIs for **instantaneous results**.

## ⚡ Windows System Info Tools Comparison
 Feature                     | **wFetch (Yours)** | Fastfetch        | Neofetch         | Winfetch         |
|------------------------------|-----------------|-----------------|-----------------|-----------------|
| **Primary Language**         | C               | C               | Bash            | Powershell       |
| **Supported OS**             | Windows 10/11   | Linux / Win / Mac | Linux / Win / Mac | Windows 10/11    |
| **Runtime**                  | **~0.03s** ✅   | ~0.05s - 0.15s  | ~0.8s - 2.5s     | ~0.5s - 1.5s   |
| **CPU Information**          | ✅              | ✅              | ✅              | ✅              |
| **RAM Information**          | ✅              | ✅              | ✅              | ✅              |
| **GPU Information**          | ✅ (DirectX)       | ✅ (Vulkan, WMI, OpenGL) | ✅              | ✅              |
| **Disk Information**         | ✅              | ✅              | ✅              | ✅              |
| **Network Adapters**         | ✅              | ❌              | ❌              | ❌              |
| **Lightweight**              | **✅ Ultra-fast** | ✅              | ❌              | ❌              |
