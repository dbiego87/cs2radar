# 🌐 CS2 WebRadar

> Undetected Counter-Strike 2 browser-based radar enhancement

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-1.0-blue)
![CS2](https://img.shields.io/badge/game-CS2-orange)
![Node.js](https://img.shields.io/badge/node.js-required-green)

## ⚠️ Important Notice

**This version is still supported, but we recommend checking out Hurracan:**

🎯 **Plug & Play Experience**  
🔄 **Instant Sharing**  
✨ **Completely New Responsive Interface**  
🖥️ **Custom Overlay for Seamless Integration**  
🔒 **Kernel-Level Security**


---

## 🚀 Quick Start

## USE start.exe

### 📋 Requirements

- Node.js
- Visual Studio Community

## 🌍 Network Sharing Guide

### 💡 Pro Tip
> For easier sharing, consider **Hurracan** which handles this process automatically with one-click setup.

---

### 🔧 Manual Sharing Configuration

Follow these steps to share your radar over the network:

#### **Step 1: Update Configuration Files**

1. **Usermode Configuration:**
   - After building the usermode project, open `config.json`
   - Change the setting: `"m_use_localhost": false`

2. **React Application Settings:**
   - Open `react project/App.jsx`
   - **Line 10:** Change `const USE_LOCALHOST = 1;` to `const USE_LOCALHOST = 0;`
   - **Line 12:** Update `const PUBLIC_IP = "your ip";` with your actual IP address

