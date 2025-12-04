# ⏰ Current Time Viewer
![Deploy](https://github.com/dimasx010/current-time/actions/workflows/main.yml/badge.svg)
[![Website](https://img.shields.io/badge/Live_Site-Current_Time-blue?style=flat-square)](https://dimasx010.github.io/current-time/)

A simple, elegant web tool that displays the **current time** in your country and compares it with the times in several selected countries.  
Designed to be lightweight, fast, and easy to understand.

This project is a small demonstration of how to automatically deploy a static website using GitHub Actions and GitHub Pages.
It showcases a minimal CI/CD workflow where every push to the main branch triggers an automated deployment to GitHub Pages, ensuring the site stays continuously updated with no manual steps required.

---
## 🌐 Live Demo

You can view the deployed website here:  
👉 **https://dimasx010.github.io/current-time/**

## 🚀 Features

- Shows **current local time** in 24-hour format  
- Displays time for multiple countries with:
  - 🌍 Country code  
  - 🕒 Local time  
  - 🕑 UTC offset  
- Clean and minimal UI  
- Emoji flags for visual clarity  
- Fully client-side (HTML + CSS + JavaScript)

---

## 📷 Preview

*(Add a screenshot here if you want)*

## 🛠️ How It Works

- The page detects the user's current time using `Date()`.
- Each country has:
  - A `UTC offset`
  - A `country code`
  - A computed local time  
- JavaScript converts time into **24-hour format**.
- The list displays country data in this format:

## 🌎 Countries Included

- 🇵🇪 Peru  
- 🇻🇪 Venezuela  
- 🇨🇱 Chile  
- 🇨🇴 Colombia  
- 🇦🇷 Argentina  
- 🇲🇽 Mexico  

You can easily add more by updating the array inside the script.

---
## 💡 Customization
You can modify:

- Colors  
- Fonts  
- Countries  
- Time format  
- Flags  
- Layout  

Directly from the HTML file.

---

## 💻 Running the Project

Open the file: ``build/index.html``

No dependencies or build tools required.

## 📜 License

Released under the **MIT License**.  
You are free to use, modify, and distribute this project.

