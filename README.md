# Invoice Generator

A simple web-based **Invoice Generator** built with **Laravel (PHP + Blade)**. Create professional invoices, calculate totals, and export/print invoices for sharing with customers.

## Tech Stack
- **Backend:** Laravel (PHP)
- **Frontend:** Blade templates
- **Languages:** Blade (~61%), PHP (~38.5%)

## Features
- Create and manage invoices
- Add customer/client details
- Add multiple line items (description, quantity, rate)
- Automatic calculations (subtotal, taxes/discounts if applicable, grand total)
- Print-friendly invoice view / export (depending on implementation)

## Getting Started (Local Setup)

### Prerequisites
- PHP (compatible with the Laravel version in this repo)
- Composer
- A database (MySQL/MariaDB/SQLite)
- Node.js + npm (only if this project uses Vite/Mix for assets)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ankit-Shankhdhar/Invoice-Generator.git
   cd Invoice-Generator
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Create environment file:
   ```bash
   cp .env.example .env
   ```

4. Generate app key:
   ```bash
   php artisan key:generate
   ```

5. Configure database in `.env`, then run migrations:
   ```bash
   php artisan migrate
   ```

6. (Optional) Install and build frontend assets:
   ```bash
   npm install
   npm run build
   ```

7. Start the development server:
   ```bash
   php artisan serve
   ```

Open the app at:
- `http://127.0.0.1:8000`


## Folder Structure (Typical Laravel)
- `app/` – application logic
- `routes/` – route definitions
- `resources/views/` – Blade UI templates
- `database/` – migrations/seeders

