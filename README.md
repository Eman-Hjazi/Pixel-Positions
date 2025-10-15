# Pixel-Positions – Laracasts Training Project

**A simple Laravel application to manage pixel positions, developed as part of the "30 Days to Learn Laravel" course on Laracasts.**

## 📌 Project Overview
Pixel-Positions is a **training project** designed to help learners understand the fundamentals of Laravel by building a **small web application**. The application allows managing pixel positions with basic CRUD operations while practicing **backend logic, Blade templating, routing, and database interactions**.

This project strengthened practical skills in **Laravel basics** and **frontend-backend integration**, bridging the gap between learning concepts and building a functional application.

## ⚙️ Technologies Used
- **Backend:** PHP, Laravel  
- **Frontend:** Blade, Tailwind CSS, Vite  
- **Database:** MySQL (via Eloquent ORM)  
- **Version Control:** Git, GitHub  

## 🧱 Key Features
- **Routing, Controllers, and Models:** Handle application logic and data flow  
- **Blade Templating:** Dynamic frontend rendering using Laravel Blade templates  
- **Database Migrations:** Setup and manage database tables with migrations  
- **Frontend Asset Management:** Manage CSS and JS assets using Vite and Tailwind CSS  
- **Authentication:** Simple user registration and login functionality  

## 📂 Project Structure
```plaintext
pixel-positions/
│
├── app/ # Laravel app logic (Controllers, Models)
├── resources/ # Blade templates, assets
├── database/ # Migrations and seeders
├── routes/ # Web and API routes
├── public/ # Public assets
└── README.md # Project documentation
```

## 📌 How to Run Locally
Make sure Node.js, npm, and PHP are installed on your system.

1. **Clone the repository**

```bash
git clone https://github.com/username/projectname.git
cd projectname
```

2. **Install backend dependencies**
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
```

3. **Run database migrations**
```bash
php artisan migrate
```
