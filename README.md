# Laravel Project – Attachment Collaboration

This is a collaborative Laravel 11 project built by attachment students to gain real-world, production-ready development experience. The backend is built with Laravel, and the frontend will be powered by React. We use GitHub for version control and teamwork.

---

## 📦 Tech Stack

- **Backend**: Laravel 11 (PHP 8.2+)
- **Frontend**: React (via Vite)
- **Database**: MySQL
- **Authentication**: Laravel Sanctum (API token-based auth)
- **Version Control**: Git + GitHub

---

## ⚙️ Setup Instructions (For New Developers)

### 1 Clone the Repository
```bash
git clone https://github.com/LNjengaTech/Laravel-Project
cd Laravel-Project

### 2️⃣ Install PHP Dependencies
composer install

### 3️⃣ Install Node Modules
npm install
npm run dev

### 4️⃣ Configure Environment File
cp .env.example .env
php artisan key:generate

### Then edit .env to set your database:
DB_DATABASE=laravel_project_db
DB_USERNAME=root
DB_PASSWORD=

### 5️⃣ Create the MySQL Database
sql
CREATE DATABASE laravel_project_db;

### 6️⃣ Run Migrations and (Optional) Seeders
php artisan migrate
php artisan db:seed

### 7️⃣ Serve the Application
php artisan serve
