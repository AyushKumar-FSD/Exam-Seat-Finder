# 🎓 Exam Seat Finder

A lightweight and responsive **Exam Seat Finder** web application built using **HTML, CSS, JavaScript, Bootstrap, and Local Storage**. The application enables students to securely view their allotted examination seat details while providing an administrator interface to search student records quickly.

> **Note:** This is a personal project developed for learning and portfolio purposes. It is not affiliated with or developed for any educational institution.

---

## ✨ Features

### 👨‍🎓 Student Module

* Secure login using USN and password
* Authentication using JavaScript
* View allotted examination details:

  * Student Name
  * USN
  * Hall
  * Block
  * Seat Number
* Session management using Local Storage
* Logout functionality

### 👨‍💼 Admin Module

* Secure administrator login
* Search students by:

  * USN
  * Student Name
* View complete seat allotment details
* Instant search results
* Logout functionality

### 🎨 User Interface

* Responsive design with Bootstrap 5
* Clean and modern UI
* Fixed header and footer
* Mobile-friendly layout
* Smooth hover animations and transitions

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (ES6)
* Bootstrap 5
* Browser Local Storage

---

## 📁 Project Structure

```text
Exam-Seat-Finder/
│
├── index.html                # Home page
├── student-login.html        # Student login page
├── student-dashboard.html    # Student dashboard
├── admin-login.html          # Admin login page
├── admin-dashboard.html      # Admin dashboard
│
├── style.css                 # Shared styles
├── data.js                   # Student and admin data
├── n.jpg                     # Logo image
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge, etc.)
* Visual Studio Code (recommended)
* Live Server extension (optional but recommended)

### Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Exam-Seat-Finder.git
```

Navigate to the project directory:

```bash
cd Exam-Seat-Finder
```

---

## ▶️ Running the Project

### Method 1: Open Directly

Simply open the `index.html` file in your preferred web browser.

### Method 2: Using Live Server

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click on `index.html`.
4. Select **Open with Live Server**.

---

## 🔐 Authentication

### Student Login

Students log in using their **USN** and **password**. After successful authentication, the application stores the logged-in student's USN in Local Storage and redirects them to the Student Dashboard.

### Admin Login

The administrator logs in using predefined credentials. Once authenticated, the admin can search for students using either their USN or name.

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

## 📸 Screenshots

Add screenshots of the following pages to make the repository more informative:

* Home Page
* Student Login
* Student Dashboard
* Admin Login
* Admin Dashboard

Example:

```
screenshots/
├── home.png
├── student-login.png
├── student-dashboard.png
├── admin-login.png
└── admin-dashboard.png
```

---

## 📌 Future Enhancements

* Database integration (MySQL/MongoDB)
* Backend authentication
* Password hashing
* Student registration module
* Dynamic seat allocation
* Admin CRUD operations
* Export seat allotments to PDF/Excel
* Role-based access control
* Forgot password functionality
* Advanced search filters

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature/your-feature
```

3. Commit your changes.

```bash
git commit -m "Add your feature"
```

4. Push your branch.

```bash
git push origin feature/your-feature
```

5. Open a Pull Request.

---

## 🍴 Forking the Repository

To create your own copy of this project:

1. Click the **Fork** button on GitHub.
2. Clone your fork.

```bash
git clone https://github.com/<your-username>/Exam-Seat-Finder.git
```

3. Start making your own modifications.

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify and distribute this project under the terms of the license.

---

## 👨‍💻 Author

**Ayush Kumar**

GitHub: https://github.com/AyushKumar-FSD

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub. It helps others discover the project and motivates future improvements.
