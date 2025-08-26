# OpenGrade — Minimal Teacher Gradebook

📘 **OpenGrade** is a lightweight gradebook web app designed for teachers.  
It’s built as a single HTML file with CSS and JavaScript — no server or database required.  
All data is stored locally in your browser using `localStorage`.

## ✨ Features
- Add multiple classes, students, and weekly grade columns
- Enter grades directly in the grid
- Automatic averages and letter grades (A–F)
- Export to **CSV** for spreadsheets
- Import/Export **JSON** backup files
- Reset to demo data anytime
- Works fully offline

## 🚀 How to Use
1. Open the app in your browser (GitHub Pages or locally).
2. Start with the demo data:
   - **Class:** Algebra I — Period 2
   - **Students:** Ava Thompson, Liam Hernandez
   - **Weeks:** Week 1 & Week 2
3. Add more classes, students, or weeks as needed.
4. Enter grades; averages and letters update instantly.
5. Export to CSV for reports, or download/upload JSON to back up your data.

## 📦 Deployment
- **GitHub Pages**: Upload `index.html` and enable Pages in repo settings.
- **Local use**: Just double-click `index.html` in a browser.
- **Optional**: Serve with a local web server for consistent localStorage:
  ```bash
  python -m http.server 8000
