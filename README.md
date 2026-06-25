# Exam Seat Finder

A lightweight web-based **Exam Seat Finder** application developed using **HTML, CSS, JavaScript, Bootstrap, and Local Storage**. This project allows students to securely view their assigned exam seat details, while providing an admin interface to search and manage seat allotment records.

> **Note:** This is a personal academic project created for learning and demonstration purposes. It is **not affiliated with or developed for any educational institution**.

---

## ✨ Features

### Student Module

* Secure student login using USN and password
* Authentication validation
* View assigned:

  * Student Name
  * USN
  * Hall
  * Block
  * Seat Number
* Logout functionality
* Automatic session validation

### Admin Module

* Secure admin login
* Search students using:

  * USN
  * Student Name
* View student exam seat details instantly
* Logout functionality

### User Interface

* Responsive design using Bootstrap 5
* Clean and modern layout
* Fixed header and footer
* Mobile-friendly interface
* Smooth hover animations

---

## 📂 Project Structure

```text
Exam-Seat-Finder/
│
├── index.html
├── student-login.html
├── student-dashboard.html
├── admin-login.html
├── admin-dashboard.html
│
├── style.css
├── data.js
├── n.jpg
│
└── README.md
```

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Bootstrap 5.3
* Browser Local Storage

---

## 🔐 Authentication

### Student Login

Students log in using their USN and password. Upon successful authentication, their USN is stored in Local Storage and they are redirected to the student dashboard where they can view their allotted exam seat details.

### Admin Login

The administrator logs in using predefined credentials. Once authenticated, the admin can search students by USN or name and view their assigned exam seating information.

---

## 📋 Sample Credentials

### Admin

```text
Username: admin
Password: admin123
```

### Students

| USN        | Password |
| ---------- | -------- |
| NNM24CS312 | 12345    |
| NNM24CS317 | abcd     |
| NNM24CS309 | pass309  |
| NNM24CS777 | sneha777 |
| NNM24CS399 | rohan399 |

---

## 🚀 Getting Started

### Option 1: Open Directly

1. Download or clone the repository.
2. Ensure all project files are in the same folder.
3. Open `index.html` in your web browser.

### Option 2: Run with VS Code

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## 🔮 Future Improvements

* Database integration (MySQL/MongoDB)
* Dynamic seat allocation
* Student registration
* Admin CRUD operations
* Export seat allotments to PDF/Excel
* Password encryption
* Backend authentication
* Role-based access control

---

## 📌 Project Purpose

This project was developed as a **personal web development project** to practice frontend development concepts, JavaScript-based authentication, Local Storage, responsive UI design, and basic data management. It demonstrates how a simple exam seat lookup system can be implemented using only client-side technologies.

---

## 📄 License

This project is intended for educational and personal learning purposes. Feel free to fork, modify, and improve it for your own learning.
