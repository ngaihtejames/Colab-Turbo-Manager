# 🚀 Colab Turbo Manager

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ngaihtejames/Colab-Turbo-Manager/blob/main/Colab_Turbo_Manager_Final.ipynb)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Type-Mobile--Friendly%20Tool-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Features-Downloader%20%7C%20Drive%20Manager-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

A **mobile-optimized, no-code Google Colab tool** that combines:

- 📥 High-speed file downloading  
- 📁 Google Drive file management  
- 📊 Storage monitoring  

> ⚡ Designed for **iPhone / mobile users** — simple, fast, and powerful.

---

## ✨ Features

### 📥 Downloader
- 🚀 Multi-threaded downloads  
- 📊 Live progress bar  
- 💾 Direct save to Google Drive  
- 🔄 Automatic fallback for unsupported servers  

---

### 📁 Drive Management
- Copy, move, rename, delete files  
- Compress files **and folders**  
- Safe delete confirmation  
- Progress feedback for operations  

---

### 📊 Storage Info
- Total / Used / Free space  
- Low storage warning  

---

## 📱 Mobile-Friendly Design

- ✅ No coding required  
- ✅ Clean collapsible UI (`#@title`)  
- ✅ Minimal input fields  
- ✅ Works smoothly on iPhone / Safari  

---

## ⚡ Quick Start

1. Click **Open in Colab** above  
2. Tap **Runtime → Run all**  
3. Allow Google Drive access  
4. Use each section:

### 🔗 Setup
- Mounts Drive  
- Installs dependencies  

### 📊 Drive Info
- Check available storage  

### 📁 Drive Management
- Enter paths  
- Select action from dropdown  

### 📥 Download
- Paste URL  
- Set filename  
- Start download  

---

## 🧪 Example Usage

### Download a file:
- URL → paste link  
- Name → `movie.mp4`  
- Run  

---

### Move a file:
- INPUT_PATH → source file  
- OUTPUT_PATH → new location  
- ACTION → `move`  

---

### Compress a folder:
- INPUT_PATH → folder path  
- OUTPUT_PATH → output name  
- ACTION → `compress`  

---

## ⚠️ Notes & Limitations

- Some servers may not support multi-thread downloads  
- Very large downloads depend on Colab session stability  
- Compression progress is file-based (not size-based)  
- Incorrect paths will result in errors  

---

## 💡 Tips

- Keep default settings if unsure  
- Always check storage before large downloads  
- Use correct full paths from Drive  

---

## 📦 Requirements

requests>=2.31.0  
tqdm>=4.66.0  

*(Automatically handled inside Colab)*

---

## 📜 License

This project is licensed under the MIT License — see the `LICENSE` file for details.
