📘 Library Management System

A lightweight and beginner-friendly Library Management System built with HTML, CSS, JavaScript, and a simple backend structure.
This project demonstrates user management, book management, and core CRUD functionality through a clean and modular folder structure.

🚀 Features

User Authentication

Sign up

Login

Session validation (frontend-based placeholder logic)

Book Management

Add a new book

Edit existing book

Delete book (UI only — backend can be attached)

View all books in a clean table layout

Clean UI

Separate HTML, CSS, and JS files for easy updates

Simple layout ready for future styling or frameworks

Frontend–Backend Structure

Organized folders for easy migration to any backend (Django, Node.js, ASP.NET, etc.)

📁 Project Structure
library/
│
├── backend/
│   └── placeholder for future API / database / controllers
│
├── frontend/
│   └── placeholder for advanced UI components
│
├── addbook/
│   ├── addbook.html
│   ├── style.css
│   └── app.js
│
├── editbook/
│   ├── editbook.html
│   ├── style.css
│   └── app.js
│
├── home/
│   ├── home.html
│   ├── style.css
│   └── app.js
│
├── login/
│   ├── login.html
│   ├── style.css
│   └── app.js
│
├── signup/
│   ├── signup.html
│   ├── style.css
│   └── app.js
│
└── viewbooks/
    ├── viewbooks.html
    ├── style.css
    └── app.js

🛠️ Technologies Used

HTML5 — page structure

CSS3 — styling and layout

JavaScript (Vanilla JS) — form handling, UI logic

Modular folder design — ready for future backend logic

📚 How It Works

The user signs up or logs in through the login and signup pages.

After authentication, the user is redirected to home.html.

From the home page, they can:

add new books

view the book list

edit book details

All pages follow a clean pattern:

page.html

style.css

app.js

This makes the project super easy to extend or connect to any backend.

🎯 Future Improvements

Here are some cool ideas you can add later:

Connect backend using Django or Node.js

Add database support (MySQL, SQLite, MongoDB)

Add admin roles

Add real authentication & JWT tokens

Add searching/filtering books

Add book categories

Dark mode UI 🌙

📸 Screenshots

Add images here later using:

![Home Page](images/home.png)

🎉 Why This Project?

This project is perfect for beginners who want to:

Learn frontend fundamentals

Understand modular project design

Build CRUD systems

Prepare for backend integration

Add a clean project to their GitHub portfolio

