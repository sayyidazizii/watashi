<h1 align="center">Watashi</h1>

<p align="center">
  <strong>WhatsApp Shipping - Laravel Wirechat with Namuio</strong>
</p>

---

## 🚀 Tentang Proyek

**Watashi** adalah aplikasi berbasis Laravel yang mengintegrasikan layanan pengiriman melalui WhatsApp dengan menggunakan Laravel Wirechat dan Namuio. Proyek ini bertujuan untuk mempermudah proses pengiriman dan komunikasi melalui WhatsApp secara efisien.

## 🛠️ Fitur Utama

- **Integrasi WhatsApp**: Menggunakan Laravel Wirechat untuk komunikasi melalui WhatsApp.
- **Manajemen Pengiriman**: Fitur untuk mengatur dan melacak pengiriman barang.
- **Antarmuka Pengguna Responsif**: Dibangun dengan Tailwind CSS untuk tampilan yang modern dan responsif.
- **Konfigurasi Mudah**: Menggunakan file `.env` untuk pengaturan konfigurasi aplikasi.

## 📸 Cuplikan Layar

<p align="center">
  <img src="https://github.com/sayyidazizii/watashi/blob/main/public/image/Screenshot1.JPG?raw=true" width="600" alt="Watashi Screenshot">
</p>

## ⚙️ Instalasi

1. **Clone repositori:**

   ```bash
   git clone https://github.com/sayyidazizii/watashi.git
   cd watashi
   ```

2. **Install dependensi:**

   ```bash
   composer install
   npm install
   npm run dev
   ```

3. **Salin file `.env` dan konfigurasi:**

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Migrasi database:**

   ```bash
   php artisan migrate
   ```

5. **Jalankan server pengembangan:**

   ```bash
   php artisan serve
   ```

## 🧪 Pengujian

Untuk menjalankan pengujian, gunakan perintah berikut:

```bash
php artisan test
```

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan fork repositori ini dan ajukan pull request untuk perbaikan atau penambahan fitur.

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT).

---

Jika Anda memiliki pertanyaan atau masukan, silakan buka [issue](https://github.com/sayyidazizii/watashi/issues) di repositori ini.
