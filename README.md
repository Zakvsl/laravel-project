# 📦 Product Management System

Sistem manajemen produk ini dirancang untuk membantu dalam mengelola produk. Sistem ini dapat menambahkan produk, gambar, dan memiliki implementasi pengiriman email setelah adanya perubahan pada produk di database

---

## 🚀 Fitur Utama

- ✅ **Manajemen Produk** – Buat, edit, dan hapus produk.
- 💬 **Pengiriman Email** – Pengiriman email setelah adanya perubahan database produk.

---
![Screenshot 2025-05-17 164032](https://github.com/user-attachments/assets/872ddff0-a8df-4b1b-b70f-5b4e64b91fba)

---

## 📦 Instalasi

```bash
git clone https://github.com/username/nama-repo.git
cd nama-repo

# Install dependensi backend
composer install

# Install dependensi frontend (jika menggunakan Vite, Laravel Mix, dll)
npm install && npm run dev

# Salin file environment dan konfigurasi
cp .env.example .env
php artisan key:generate

# Jalankan migrasi database
php artisan migrate

# Mulai server lokal
php artisan serve

