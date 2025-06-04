# 📊 Experiment Data Search App

A cross-platform desktop application to **search structured Excel data easily**, built using **React + Tauri**.  
Designed for light, offline use with features like dark mode, live search, copy, and upload new Excel files.

---

## ✨ Features

- 🔍 Search by:
  - 👥 Customer Name
  - 🛰 Hostname OLT
  - 📝 Service ID
  - 📍 ID FAT
  - 💻 SN ONT
- 🌗 Light / Dark Mode Toggle
- 📁 Upload new Excel data
- 🧼 Clear form
- 📋 Copy result
- 🎬 Splash screen with logo

---

## 🖼️ Preview

![screenshot](public/splash.png)

---

## 🛠 Setup & Run

```bash
npm install
npm run dev
```

To build as Tauri `.exe`:

```bash
npm run build
npm run tauri build
```

---

## 📦 Build Output

Installer and executables will be in:
```
src-tauri/target/release/bundle/
```

---

## 📁 Upload Format

Ensure your Excel file includes these headers:

- `Customer Name`
- `Hostname OLT`
- `Service ID`
- `ID FAT`
- `SN ONT`

---

## 🔖 License

MIT License  
© RZ Corp. All Rights Reserved
