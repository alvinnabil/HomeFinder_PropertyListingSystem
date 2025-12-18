# 🏠 HomeFinder

HomeFinder is a full-stack **property listing and home discovery web application** built with **Laravel** and modern frontend tooling. This project is designed to demonstrate clean backend architecture, RESTful APIs, and a modern development workflow suitable for real-world applications and portfolio use.

---

## ✨ Features

* Browse and explore property listings
* Structured backend using Laravel MVC pattern
* RESTful API support
* Modern frontend asset bundling with Vite
* Ready for local development and deployment

---

## 🛠 Tech Stack

### Backend

* **Laravel** (PHP Framework)
* Composer (Dependency Management)
* MySQL / MariaDB (Database)

### Frontend

* Blade / Vite
* Node.js & NPM

### Tools & Environment

* PHP >= 8.1
* Node.js >= 18
* Composer
* Git

---

## 📁 Project Structure

```bash
app/            # Core application logic
api/            # API-related logic
config/         # Application configuration
database/       # Migrations & seeders
resources/      # Views, assets
routes/         # Web & API routes
storage/        # Logs & cache (ignored in Git)
public/         # Publicly accessible files
```

> Note: Folders like `vendor`, `node_modules`, and `storage` are intentionally excluded from the repository and must be generated locally.

---

## 🚀 Local Development Setup

Follow the steps below to run this project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/alvinnabil/HomeFinder.git
cd HomeFinder
```

---

### 2️⃣ Install Backend Dependencies

```bash
composer install
```

---

### 3️⃣ Install Frontend Dependencies

```bash
npm install
```

---

### 4️⃣ Environment Configuration

Copy the example environment file:

```bash
cp .env.example .env
```

Generate application key:

```bash
php artisan key:generate
```

Update `.env` with your database credentials:

```env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

---

### 5️⃣ Run Database Migration

```bash
php artisan migrate
```

(Optional: run seeders if available)

```bash
php artisan db:seed
```

---

### 6️⃣ Run the Application

Run backend server:

```bash
php artisan serve
```

Run frontend assets:

```bash
npm run dev
```

The application will be available at:

```
http://127.0.0.1:8000
```

---

## 🧪 Testing

Run automated tests using:

```bash
php artisan test
```

---

## 📦 Deployment Notes

* This project is configured for modern deployment platforms (e.g. Vercel for frontend).
* Ensure environment variables are properly set in production.
* Build frontend assets before deploying.

---

## 📌 Git Best Practices

The following files and folders are excluded from version control:

* `vendor/`
* `node_modules/`
* `storage/`
* `.env`

They can be generated locally using the setup steps above.

---

## 👨‍💻 Author

**Alvin Nabil Thoriq**
Software Engineering Student

* GitHub: [alvinnabil](https://github.com/alvinnabil)
* Portfolio: [vinndev.vercel.app](https://vinndev.vercel.app)
* LinkedIn : [Alvin Nabil](www.linkedin.com/in/alvin-nabil-8972792a7)

---

## 📄 License

This project is licensed for educational and portfolio purposes.

---

⭐ If you find this project useful or interesting, feel free to give it a star!
