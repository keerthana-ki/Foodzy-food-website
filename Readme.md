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
├─ images/                  
│   ├─ foodzy ss1.png
│   ├─ foodzy ss2.png
│   └─ foodzy ss10.png
├─ README.md
└─ .gitignore
```

---

## 🚀 Run Locally (quick)
1. **Open the project folder** in VS Code (File → Open Folder → select `foodzy/`).  
2. Open `index.html` in a browser (double-click) OR use VS Code Live Server extension for live reload:  
   - Install "Live Server" extension, right-click `index.html` → "Open with Live Server".

---

## 📸 Screenshots  

### Screenshot 1 – Homepage  
This is the Homepage of the website, featuring the main banner and hero section.  
![Homepage](images/foodzy%20ss1.png)  

### Screenshot 2 – About Us  
This shows the About Us section, where the restaurant's story is told.  
![About Us](images/foodzy%20ss2.png)  

### Screenshot 3 – Menu  
This is the Menu section, displaying various food categories and dishes.  
![Menu](images/foodzy%20ss3.png)  

### Screenshot 4 – Menu / Gallery Focus  
This screenshot also shows part of the Menu or Gallery, focusing on specific dishes like pizza and sushi.  
![Menu Focus](images/foodzy%20ss4.png)  

### Screenshot 5 – Gallery & Table Booking  
This shows the Gallery and Table Booking section, highlighting the opening hours and an image gallery.  
![Gallery & Booking](images/foodzy%20ss5.png)  

### Screenshot 6 – Chefs Section  
This is the Chefs Section, introducing the culinary team.  
![Chefs](images/foodzy%20ss6.png)  

### Screenshot 7 – Testimonials  
This shows the Testimonials section, where customer reviews are displayed.  
![Testimonials](images/foodzy%20ss7.png)  

### Screenshot 8 – Testimonials + FAQ  
This screenshot includes both the Testimonials and the FAQ (Frequently Asked Questions) section.  
![Testimonials & FAQ](images/foodzy%20ss8.png)  

### Screenshot 9 – Blog & Newsletter  
This displays the Blog and Newsletter Subscription section.  
![Blog & Newsletter](images/foodzy%20ss9.png)  

### Screenshot 10 – Newsletter & Footer  
This shows the Newsletter and Footer section of the website.  
![Footer](images/foodzy%20ss10.png)  

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
git remote add origin https://github.com/<keerthana-ki>/foodzy.git
git push -u origin main
```

---

## 🌐 Deploy with GitHub Pages (optional - static site)
1. Push the repo to GitHub (steps above).  
2. On GitHub repo → **Settings** → **Pages** → Source: `main` branch / root (`/`) → Save.  
3. After a minute, your site will be available at:  
   `https://<your-username>.github.io/foodzy/`

---

## ✅ What to include in the GitHub repo BEFORE applying
- `index.html`, `style.css`, `main.js`, `logo.png` (already present)  
- `images/` folder with screenshots (homepage, cart, menu, etc.)  
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
- Project guide / faculty: **Mrs. Swetha A**

---

## 📜 License
MIT License — see `LICENSE` (optional)
