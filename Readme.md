# 🍴 Foodzy — Restaurant Food Website (Minor Project)

**Foodzy** is a responsive mini food-ordering frontend built as a 6th-semester minor project. It demonstrates clean UI/UX for browsing a restaurant menu and a working **Add-to-Cart** feature implemented in plain HTML, CSS and JavaScript.

---

## 🔎 Project Summary
- **Type:** Frontend (client-side) mini project — *no backend integrated yet*  
- **Course:** Minor Project (6th Semester, B.Tech)  
- **Purpose:** Provide a responsive menu, let users add items to a cart, preview orders, and visualize basic restaurant pages (Home, Menu, Gallery, Blog, Contact).

---

## ✨ Features
- Responsive homepage with hero section and brand/UI animations  
- Categorized menu (Breakfast / Lunch / Dinner) with filters  
- Dish details (name, price, veg/non-veg indicator, rating)  
- Add-to-Cart functionality (client-side) with dynamic total calculation  
- Image sliders (Swiper.js), lightbox (Fancybox) and small UI animations (GSAP)  
- Clean modern design using CSS + Bootstrap utilities

---

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6)  
- **Libraries:** Bootstrap, Swiper.js, Fancybox, GSAP (animations)  
- **Icons:** Unicons / Font icons  
- **Note:** Backend (billing, order persistence) is planned as a future enhancement.

---

## 📁 Project Structure (example)
```
foodzy/
├─ index.html
├─ style.css
├─ main.js
├─ logo.png
├─ media/                  # put screenshots here before pushing
│   ├─ screenshot1.png
│   └─ screenshot2.png
├─ README.md
└─ .gitignore
```

---

## 🚀 Run Locally (quick)
1. **Open the project folder** in VS Code (File → Open Folder → select `foodzy/`).  
2. Open `index.html` in a browser (double-click) OR use VS Code Live Server extension for live reload:  
   - Install "Live Server" extension, right-click `index.html` → "Open with Live Server".

---

## 📸 Add Screenshots to README
1. Create a `media/` folder inside your `foodzy` project.  
2. Put screenshots named like `screenshot1.png`, `screenshot2.png` into `media/`.  
3. Use this markdown in README to display them:
```md
## Screenshots
![Homepage](media/screenshot1.png)
![Menu / Cart](media/screenshot2.png)
```

---

## 📤 Push to GitHub (exact commands)
1. Create a **new repo** on GitHub named `foodzy` (Description: *A frontend food-ordering website built with HTML, CSS, JS*).  
   - **Don’t** check “Add README” (you already have one).  
2. In VS Code terminal (inside `foodzy/`), run:
```bash
git init
git add .
git commit -m "Initial commit - Foodzy (frontend)"
git branch -M main
git remote add origin https://github.com/<your-username>/foodzy.git
git push -u origin main
```
(Replace `<your-username>` with your GitHub username)

---

## 🌐 Deploy with GitHub Pages (optional - static site)
1. Push the repo to GitHub (steps above).  
2. On GitHub repo → **Settings** → **Pages** → Source: `main` branch / root (`/`) → Save.  
3. After a minute, your site will be available at: `https://<your-username>.github.io/foodzy/`

---

## ✅ What to include in the GitHub repo BEFORE applying
- `index.html`, `style.css`, `main.js`, `logo.png` (already present)  
- `media/` folder with screenshots (homepage, cart, menu)  
- `README.md` (this file) and `.gitignore` (see below)  
- Optional: `/docs/ProjectReport.pdf` (a PDF of your PPT or final report).

---

## ♻️ Future Enhancements (good to mention on resume)
- Integrate backend (Spring Boot / Node.js) for cart persistence & billing  
- Add user authentication and order history (DB: MySQL / MongoDB)  
- Payment gateway (Stripe / Razorpay) & invoice generation (PDF)  
- Deploy a live demo (GitHub Pages or simple hosting)

---

## 👩‍💻 Authors / Credits
- Minor project (6th Semester, B.Tech) — **Keerthana A** and **Harshath KC** 
- Project guide / faculty: **Mrs.Swetha A**
---

## 📜 License
MIT License — see `LICENSE` (optional)

---
*If you want, I can also convert your PPT into a PDF and place it in `/docs/` for you to upload to the repo.*
