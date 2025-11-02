# 💼 JobBoard JS  
**Interactive Job Offers Management Platform built with Vanilla JavaScript**

---

## 🏁 Mission  
Create a dynamic and responsive job management web application using **Vanilla JavaScript**, **HTML5**, and **CSS3**, allowing users to manage job offers, search and filter listings, save favorites, and maintain their personal profile — all with real-time validation and local data persistence.

---

## 🧠 Overview  

**JobBoard JS** is a front-end project that simulates a modern job platform where users can:  
- Create and manage job offers (CRUD operations)  
- Validate form inputs in real time  
- Search and filter offers dynamically  
- Mark jobs as favorites and keep them saved locally  
- Manage a personal profile (skills, preferences)  
- Enjoy a smooth, responsive experience across devices  

---

## ⚙️ Technologies Used  

| Technology | Purpose |
|-------------|----------|
| **JavaScript (ES6+)** | Core logic, form validation, CRUD operations, and event handling |
| **HTML5** | Structure and semantic elements |
| **CSS3 (Grid / Flexbox)** | Responsive and modern layout |
| **LocalStorage API** | Persistent storage for profile and favorites |
| **JSON** | Data handling and loading |
| **HTML5 Form Validation** | Native + custom input validation |

---

## 🚀 Features  

### 🧾 1. Form Validation  
- User Profile: Validate name, email, and skills  
- Job Offer Form: Check required fields (title, company, description)  
- Real-time feedback: Success/error messages while typing  

### 🔍 2. Advanced Search & Filtering  
- Keyword search (title, company, description)  
- Multiple filters (skills, contract type, location)  
- Combined filtering (search + filters)  
- Real-time results update  

### 🧮 3. Complete CRUD Operations  
- **Add:** Modal form for new job offers  
- **Edit:** Modify existing offers  
- **Delete:** Confirmation before deletion  
- **Display:** Responsive offer cards  

### ❤️ 4. Favorites System  
- Add/remove favorites with interactive button  
- Dedicated “Favorites” tab  
- Persistent storage via `localStorage`  

### 👤 5. Profile Management  
- Add/remove skills dynamically  
- Save preferred job type and location  
- Automatic persistence  

### ⚡ 6. Event Handling & UX Enhancements  
- Interactive tabs (All, Favorites, My Offers)  
- Dynamic feedback on actions (validation, saving, etc.)  
- Responsive design for mobile and desktop  

---

## 🧩 Project Structure  

JobBoard-JS/
│
├── index.html # Main HTML file
├── /css/
│ └── style.css # Main stylesheet
├── /js/
│ ├── main.js # Entry point and app logic
│ ├── validation.js # Form validation module
│ ├── crud.js # CRUD operations for offers
│ ├── filters.js # Search and filtering logic
│ ├── favorites.js # Favorite system logic
│ └── profile.js # User profile management
├── /data/
│ └── offers.json # Sample data
└── README.md