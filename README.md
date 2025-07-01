# Filament Dashboard - GoWorking Space

A modern, responsive dashboard built with [FilamentPHP](https://filamentphp.com/) for managing coworking spaces, reservations, events, and admins. The application offers analytics

![Dashboard Preview]

![alt text](<Capture d'écran 2025-06-20 175913.png>)

## ✨ Key Features

- 🔐 Role-based access (Admin / Superadmin)
- 🗓️ Manage **reservations** with import/export (CSV/XLSX)
- 🏢 Manage **coworking spaces** (images, prices, capacity, description)
- 📣 **Event management** with scheduling and images
- 📊 Interactive dashboard with unique views, bounce rate, and time-on-page stats
- 📂 File upload support (images for spaces/events)
- 📥 Data import/export support using Laravel Excel

## 🛠️ Technologies Used

- PHP 8.x
- Laravel 10+
- FilamentPHP (Admin Panel)
- Livewire
- MySQL
- TailwindCSS

## 🚀 Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/filament-goworking-dashboard.git
cd filament-goworking-dashboard
2. Install dependencies:
bash
Copy
Edit
composer install
npm install
3. Set up environment variables:
bash
Copy
Edit
cp .env.example .env
php artisan key:generate
Update .env with your database credentials.

4. Run migrations and seeders:
bash
Copy
Edit
php artisan migrate --seed
5. Build frontend assets:
bash
Copy
Edit
npm run dev

6. Start Laravel development server:
bash
Copy
Edit
php artisan serve
🔐 Default Admin Access
A default Superadmin account is created:

pgsql
Copy
Edit
Email: admin@example.com
Password: password
(You can change this in the database or seeders.)



🧱 Resources Overview
CoworkingResource: Manage coworking spaces (owner, address, logo, email, phone)

ReservationResource: Handle user reservations (price, type, time range, places)

EventResource: Organize and manage space-based events

SpaceResource: Create and configure bookable spaces with images and pricing

📤 Import & Export Support
ReservationImporter.php: Import reservations (CSV/XLSX)





