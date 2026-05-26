# 📄 Invoice Generator

A modern and professional **Invoice Generator** built with **Laravel (PHP + Blade)** that helps freelancers, startups, and businesses create clean, branded invoices in seconds.

The application allows users to create, manage, print, and share professional invoices with automatic calculations and a smooth user experience.

---

## ✨ Features

- ✅ Create and manage invoices
- ✅ Add customer/client details
- ✅ Add multiple invoice line items
- ✅ Automatic subtotal & grand total calculations
- ✅ Tax and discount support
- ✅ Professional print-friendly invoice layout
- ✅ Responsive and clean UI
- ✅ Fast and lightweight Laravel architecture

---

## 🚀 Tech Stack

### Backend
- Laravel (PHP)

### Frontend
- Blade Templates
- HTML5
- CSS3
- JavaScript

### Database
- MySQL / MariaDB / SQLite

---

## 📸 Preview

### Dashboard
- Clean and modern invoice management interface

### Invoice Creation
- Dynamic invoice item handling
- Real-time calculations

### Printable Invoice
- Professional invoice layout ready for printing/export

---

# ⚙️ Getting Started

## 📌 Prerequisites

Make sure you have installed:

- PHP
- Composer
- MySQL / MariaDB / SQLite
- Node.js & npm (optional for frontend assets)

---

# 🔧 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ankit-Shankhdhar/Invoice-Generator.git
cd Invoice-Generator
```

---

## 2️⃣ Install Dependencies

```bash
composer install
```

---

## 3️⃣ Create Environment File

```bash
cp .env.example .env
```

---

## 4️⃣ Generate Application Key

```bash
php artisan key:generate
```

---

## 5️⃣ Configure Database

Update your `.env` file:

```env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Run migrations:

```bash
php artisan migrate
```

---

## 6️⃣ Install Frontend Dependencies (Optional)

```bash
npm install
npm run build
```

---

## 7️⃣ Start Development Server

```bash
php artisan serve
```

Open the application in your browser:

```bash
http://127.0.0.1:8000
```

---

# 📂 Project Structure

```bash
app/                 # Application logic
routes/              # Route definitions
resources/views/     # Blade templates
database/            # Migrations & seeders
public/              # Public assets
config/              # Configuration files
```

---

# 🌟 Future Improvements

- PDF invoice export
- Email invoice sharing
- Authentication system
- Multi-user support
- Multi-currency support
- Analytics dashboard
- Dark mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push to the branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed with ❤️ using Laravel & Blade.
