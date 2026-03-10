# الشركات - Iraqi Ministry of Defence Companies Management System

نظام إدارة الشركات - وزارة الدفاع العراقية

## 🌐 Live App
**https://readh1999.github.io/companies-app/**

## ✨ Features
- ✅ Auto-increment ID (التسلسل التلقائي)
- 🔍 Autocomplete for Company Name, Destination, Department
- 📋 All fields optional
- 🔴 Red overlay for expired entries (تم الدخول)
- 🟡 Yellow for active/available entries
- 🔴 Red for expired date entries
- 📊 Export to Excel
- 📄 Export to Word
- 🖨️ Print-friendly layout
- 💾 Backup & Restore (JSON)
- ⚙️ Add custom fields with types
- 📝 Notes field
- 📱 PWA - installable on Android/iOS/Windows
- 🔗 Company history grouping

## 🚀 Deploy to GitHub Pages

1. Create new repo named `companies-app`
2. Upload all files
3. Go to **Settings → Pages → Source: main branch / root**
4. Your app will be live at `https://readh1999.github.io/companies-app/`

## 📦 PWABuilder
After deploying to GitHub Pages:
1. Go to https://www.pwabuilder.com
2. Enter your GitHub Pages URL
3. Download packages for App Stores

## 📁 File Structure
```
companies-app/
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js               # Service Worker
├── README.md           # This file
└── icons/              # App icons
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```
