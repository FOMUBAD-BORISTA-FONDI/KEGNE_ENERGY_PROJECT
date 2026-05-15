# KEGNE ENERGY PROJECT

A Laravel-based web application for the KEGNE ENERGY PROJECT.
This project was Forked from "https://github.com/Kegne-oli/KEGNE_ENERGY_PROJECT"

---

## 📌 Requirements

Before running this project locally, make sure you have the following installed:

- PHP 8.x or later
- Composer
- Node.js & npm
- MySQL or MariaDB
- Git

---

# 🚀 Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Kegne-oli/KEGNE_ENERGY_PROJECT.git
```

Move into the project directory:

```bash
cd KEGNE_ENERGY_PROJECT
```

---

## 2️⃣ Install PHP Dependencies

```bash
composer install
```

---

## 3️⃣ Install Frontend Dependencies

```bash
npm install
```

---

## 4️⃣ Create the Environment File

### Windows PowerShell

```powershell
copy .env.example .env
```

### CMD

```cmd
copy .env.example .env
```

### Linux / Git Bash

```bash
cp .env.example .env
```

---

## 5️⃣ Generate the Application Key

```bash
php artisan key:generate
```

---

## 6️⃣ Configure the Database

Create a database in MySQL.

Example:

```text
kegne_energy
```

Open the `.env` file and update the database credentials:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=kegne_energy
DB_USERNAME=root
DB_PASSWORD=
```

Replace the values with your actual MySQL credentials.

---

## 7️⃣ Run Database Migrations

```bash
php artisan migrate
```

If seeders exist:

```bash
php artisan db:seed
```

Or run both together:

```bash
php artisan migrate --seed
```

---

## 8️⃣ Create Storage Link

```bash
php artisan storage:link
```

---

## 9️⃣ Compile Frontend Assets

For development:

```bash
npm run dev
```

For production build:

```bash
npm run build
```

---

## 🔟 Start the Development Server

```bash
php artisan serve
```

The application should now be running at:

```text
http://127.0.0.1:8000
```

---

# 🛠 Recommended Development Workflow

Use two terminals:

### Terminal 1

```bash
php artisan serve
```

### Terminal 2

```bash
npm run dev
```

---

# 🧹 Useful Laravel Commands

Clear caches:

```bash
php artisan config:clear
php artisan cache:clear
php artisan route:clear
php artisan view:clear
```

Rebuild autoload files:

```bash
composer dump-autoload
```

---

# ❗ Common Issues

## Vite Manifest Not Found

Run:

```bash
npm run dev
```

or

```bash
npm run build
```

---

## Application Key Missing

Run:

```bash
php artisan key:generate
```

---

## Database Connection Errors

Verify:

- MySQL server is running
- Database exists
- `.env` credentials are correct

---

# 📂 Tech Stack

- Laravel
- PHP
- MySQL
- Vite
- JavaScript
- HTML/CSS

---

# 👨‍💻 Author

Developed by **KEGNE OLI**

GitHub Repository:  
https://github.com/Kegne-oli/KEGNE_ENERGY_PROJECT

---

# 📄 License

This project is open-source and available under the MIT License.