<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4CAF50,100:2196F3&height=200&section=header&text=Restaurant%20Web%20App%20–%20Module%205%20Solution&fontSize=40&fontColor=ffffff" alt="header"/>

<h2 align="center">🍽️ Module 5 Solution — Johns Hopkins Coursera</h2>

<p align="center">
  <a href="https://github.com/saqib54/Module5_Solution">
    <img src="https://img.shields.io/badge/GitHub-Repository-blue?logo=github" />
  </a>
  <img src="https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-green?logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/AJAX-yellow?logo=javascript&logoColor=white" />
</p>

---

## 📖 Overview  

This repository contains the **solution for the Module 5 Coding Assignment** of the Coursera course *HTML, CSS, and Javascript for Web Developers* by Johns Hopkins University.  

It’s a **restaurant web application** featuring a dynamic home page with clickable tiles for **Menu**, **Specials**, and **Map**.  
The **Specials tile** randomly redirects users to a menu category (Lunch, Dinner, Sushi, etc.) adding an element of fun.

---

## ✨ Features  

- 🖥️ **Dynamic Home Page:** Three responsive tiles (Menu, Specials, Map) using Bootstrap.  
- 🎲 **Random Specials Category:** Specials tile loads a random menu category.  
- ⚡ **AJAX Data Loading:** Menu categories/items fetched dynamically from JSON files.  
- 📱 **Responsive Design:** Mobile-friendly and styled with Bootstrap.  
- 🌐 **GitHub Pages Deployment:** Hosted on GitHub Pages for easy access.  

---

## 🖼️ Screenshots  

<img width="1348" height="632" alt="image" src="https://github.com/user-attachments/assets/209afc43-ed33-4f83-8eed-9cfb68a00a36" />

<img width="1365" height="604" alt="image" src="https://github.com/user-attachments/assets/80fe9414-a831-40bb-b8ce-0c7232b34162" />

<img width="1353" height="624" alt="image" src="https://github.com/user-attachments/assets/a1e9e6c5-fca3-4145-a465-11235bc0442b" />

<img width="1366" height="634" alt="image" src="https://github.com/user-attachments/assets/3d06db8f-f92d-4ea5-b93f-ab3ef95955e3" />

### 📱 Mobile Version  

<img width="632" height="632" alt="image" src="https://github.com/user-attachments/assets/80ed5114-0e97-4cfa-8a00-a039ea72856f" />

---

## 📂 Repository Structure  

```text
module5-solution/
├── css/
│   └── styles.css          # Custom CSS for styling
├── data/
│   ├── categories.json     # Menu categories data
│   ├── menu_items_*.json   # Menu items for each category
├── js/
│   ├── ajax-utils.js       # AJAX utility functions
│   └── script.js           # Main JavaScript logic
├── snippets/
│   └── home-snippet.html   # HTML snippet for the home page
├── index.html              # Main entry point of the application
└── README.md               # This file
'''
git clone https://github.com/saqib54/Module5_Solution.git
cd Module5_Solution/module5-solution
2️⃣ Get the Starter Files (if needed)

bash
Copy code
git clone https://github.com/jhu-ep-coursera/fullstack-course4.git
# or if already cloned:
cd fullstack-course4 && git pull
Copy the contents of
fullstack-course4/assignments/assignment5/assignment5-solution-starter
into your module5-solution folder.

3️⃣ Local Development (Optional)

Install Browser Sync for live reloading:

bash
Copy code
npm install -g browser-sync
browser-sync start --server --files "*.html, css/*.css, js/*.js"
Open http://localhost:3000 in your browser.

4️⃣ Deploy to GitHub Pages

bash
Copy code
git add .
git commit -m "Module 5 solution"
git push origin main
Then enable GitHub Pages in Settings > Pages of your repository.

🚀 Usage
Open the deployed site or local server in a browser.

The home page displays three tiles: Menu, Specials, and Map.

Click the Specials tile to view a randomly selected menu category.

Click the restaurant logo to return to the home page.

📝 Implementation Details
Random Category Selection: script.js contains an array of category short names and a function to select one randomly. This short name replaces {{randomCategoryShortName}} in home-snippet.html.

AJAX Requests: The app uses AJAX to load categories.json and menu_items_*.json dynamically.

HTML Snippet Unchanged: Per assignment requirements, home-snippet.html stays unmodified; all logic is in script.js.

✅ Testing
Load the home page.

Click the Specials tile to ensure a random category page loads.

Return to the home page by clicking the logo.

Repeat clicking Specials to confirm random behavior.

⚠️ Known Issues
Ensure the data folder contains all necessary JSON files. Missing files will cause AJAX errors.

Random category selection may occasionally repeat due to randomness.

🙌 Credits
Course: HTML, CSS, and Javascript for Web Developers (Johns Hopkins University, Coursera)

Starter Code: Provided by jhu-ep-coursera/fullstack-course4

Framework: Bootstrap for responsive design

AJAX Utility: Provided in ajax-utils.js from the starter code

📜 License
This project is for educational purposes and uses starter code provided by the Coursera course. No additional license specified.

php-template
Copy code

If you add your GitHub Pages URL later (e.g. `https://saqib54.github.io/Module5_Solution/`), you can insert a **green Live Demo badge** right under the heading:

```html
<p align="center">
  <a href="https://saqib54.github.io/Module5_Solution/">
    <img src="https://img.shields.io/badge/Live%20Demo-Click%20Here-green?style=for-the-badge" />
  </a>
</p>
