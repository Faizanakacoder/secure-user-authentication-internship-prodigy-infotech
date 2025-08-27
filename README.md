# secure-user-authentication-internship-prodigy-infotech
Secure login and signup system (Frontend) built during Full Stack Web Development Internship at Prodigy Infotech.

```markdown
# User Authentication System (Frontend)

**Project done under internship at [Prodigy Infotech](https://www.prodigyinfotech.com/) as a Full Stack Web Developer.**

---

## 👨‍🎓 Student Details

- **Name:** FAIZAN FIROZ SHAH 
- **College:** Godavari Foundation's Godavari College of Engineering, Jalgaon  
- **Course:** B.Tech – Computer Engineering  
- **Year:** 2nd Year  

---

## 💡 Project Overview

A simple and **secure user authentication system** implemented using **HTML, CSS, and JavaScript**.  
This project allows users to **sign up, log in, and access protected routes** (Dashboard) using secure password hashing with **PBKDF2**.

---

## 🔑 Features

- **User Sign Up** – Create a new account with username & password.  
- **User Login** – Secure login with hashed password verification.  
- **Protected Dashboard** – Accessible only for authenticated users.  
- **Password Security** – Passwords hashed using **PBKDF2 + Salt**.  
- **Session Management** – Active session maintained with `sessionStorage`.  
- **Responsive Design** – Clean and mobile-friendly interface.  
- **On-page Instructions** – Info box for user guidance.  

---

## 📂 Project Structure

```

/auth-project
├── index.html       # Login & Signup forms
├── style.css        # Styling for forms and info box
├── app.js           # Authentication logic with hashing
└── dashboard.html   # Protected page for logged-in users
|__ presentation     # explanation about project

---

## ⚙️ How it Works

1. **Sign Up**  
   - User enters username & password.  
   - Password hashed using **PBKDF2 + Salt** via Web Crypto API.  
   - Hashed password & salt stored in **localStorage**.  

2. **Login**  
   - User inputs credentials.  
   - Password re-hashed with stored salt.  
   - If match → Login successful, session saved in **sessionStorage**.  

3. **Protected Dashboard**  
   - `dashboard.html` checks session.  
   - If not logged in → Redirects to `index.html`.  
   - Logout clears the session.  

---

## 📝 Instructions

1. Clone or download this repository.  
2. Open `index.html` in your browser.  
3. **Sign Up** with a new username & password.  
4. **Login** with the same credentials.  
5. Redirects to **Dashboard** on success.  
6. Use **Logout** to end the session.  

---

## ⚠️ Notes

- This is a **frontend-only demo** (data stored in browser storage).  
- For real-world production: use a **backend + database + secure session handling**.  

---

## 🎨 Screenshots

HOMEPAGE: ![Gameplay Example](https://github.com/Faizanakacoder/secure-user-authentication-internship-prodigy-infotech/blob/main/HOME%20PAGE.png)

SUCCESFUL SIGN-UP: ![Game Start Screen](https://github.com/Faizanakacoder/secure-user-authentication-internship-prodigy-infotech/blob/main/DASHBOARD%20%26%20LOGOUT.png)

LOG-IN FAILED: ![Game Start Screen](https://github.com/Faizanakacoder/secure-user-authentication-internship-prodigy-infotech/blob/main/LOGIN%20FAILED.png)

SUCCESFUL LOGIN: ![Win Detection](https://github.com/Faizanakacoder/secure-user-authentication-internship-prodigy-infotech/blob/main/SUCCESFUL%20LOGIN.png)

DASHBOARD: ![Game Start Screen](https://github.com/Faizanakacoder/secure-user-authentication-internship-prodigy-infotech/blob/main/DASHBOARD%20%26%20LOGOUT.png)




> 📌 Place all screenshots inside a folder named **`/screenshots`** in your repo.  
> Example path: `auth-project/screenshots/homepage.png`

---

## 🛠️ Technologies Used

- **HTML5** – Structure  
- **CSS3** – Styling  
- **JavaScript** – Logic & Authentication  
- **Web Crypto API** – Password Hashing  

---

## 👨‍💻 Contribution / Role During Internship  

During my **Full Stack Web Development Internship at [Prodigy Infotech](https://www.prodigyinfotech.com/)**, I actively contributed to building a secure **User Authentication System (Frontend)**.  

**My key responsibilities included:**  
- Developed responsive login & signup interfaces using **HTML, CSS, JS**.  
- Implemented **password hashing (PBKDF2 + Salt)** with Web Crypto API.  
- Managed **localStorage & sessionStorage** for secure session handling.  
- Designed a **clean and user-friendly interface** with clear instructions.  
- Created comprehensive **documentation (README, screenshots, guide)**.  

This internship improved my skills in **secure web development, frontend design, and project documentation**, while providing hands-on **real-world project experience**.  

---
