# 📦 Product Management System

Sistem manajemen produk ini dirancang untuk membantu dalam mengelola produk. Sistem ini dapat menambahkan produk, gambar, dan memiliki implementasi pengiriman email setelah adanya perubahan pada produk di database

---

## 🚀 Fitur Utama

- ✅ **Manajemen Produk** – Buat, edit, dan hapus produk.
- 💬 **Pengiriman Email** – Pengiriman email setelah adanya perubahan database produk.

---

## 🖼️ Cuplikan Tampilan

Berikut beberapa tampilan antarmuka dari proyek:

- **Halaman Utama**
![Screenshot 2025-05-17 164032](https://github.com/user-attachments/assets/872ddff0-a8df-4b1b-b70f-5b4e64b91fba)

- **Halaman Tambah Produk**
![Screenshot 2025-05-17 164039](https://github.com/user-attachments/assets/26a40693-c99c-4785-b6c5-b8685a6d80d0)

- **Halaman Edit Produk**
![Screenshot 2025-05-17 164053](https://github.com/user-attachments/assets/bee7d52c-50e8-407c-8217-1bc42d0d966b)

- **Halaman Penerimaan Email**
![Screenshot 2025-05-17 163959](https://github.com/user-attachments/assets/d26d440d-4514-4f1e-8c51-0d00f31b2818)



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

