# 📁 Sistem Arsip Digital dengan Notifikasi WhatsApp

Sistem manajemen arsip digital yang dibangun menggunakan Google Apps Script dengan fitur notifikasi WhatsApp terintegrasi. Solusi praktis untuk pengelolaan dan pengarsipan dokumen digital dengan antarmuka yang user-friendly.

## ✨ Fitur Utama

- 📝 Penomoran dokumen otomatis
- 📤 Upload multiple file (hingga 5 file sekaligus)
- 🔍 Pencarian real-time
- 📱 Notifikasi WhatsApp terintegrasi
- 🔒 Penyimpanan aman di Google Drive
- 📊 Tracking metadata di Google Sheets
- 🌐 Akses dari mana saja

## 🚀 Teknologi yang Digunakan

- Google Apps Script
- Google Drive API
- Google Sheets API
- WhatsApp API (MPedia)
- HTML/CSS (Tailwind CSS)
- JavaScript

## 📋 Prasyarat

- Akun Google
- Akun MPedia
- Google Drive
- Google Spreadsheet

## ⚙️ Cara Instalasi

1. Buat project baru di Google Apps Script
2. Salin kode dari repository ini ke project Anda:
   - Code.gs
   - Index.html
   - Search.html
   - CSS.html

3. Konfigurasi:
   - Set ID folder Google Drive
   - Set ID spreadsheet
   - Konfigurasi API WhatsApp
   - Sesuaikan format penomoran dokumen

4. Deploy sebagai web app

## 🛠️ Konfigurasi

### Struktur Spreadsheet
Buat spreadsheet dengan kolom berikut:
- Timestamp
- Nomor Arsip
- Judul Arsip
- Kategori
- Tanggal Arsip
- Tags
- File URL
- File ID
- Uploader

### Konfigurasi WhatsApp
```javascript
WHATSAPP_CONFIG: {
  API_KEY: 'YOUR_API_KEY',
  SENDER: 'SENDER_NUMBER',
  RECIPIENTS: 'RECIPIENT_NUMBERS',
  API_URL: 'API_ENDPOINT'
}
🎯 Penggunaan

Buka web app
Isi form upload:

Judul arsip
Kategori
Tanggal
Tags
Pilih file (max 5)


Klik upload
Notifikasi akan dikirim via WhatsApp
Gunakan halaman pencarian untuk menemukan arsip

📱 Format Notifikasi WhatsApp
Copy🏢 NOTIFIKASI ARSIP DIGITAL

📅 [Tanggal dan Waktu]

📋 Detail Arsip yang Diunggah:
[Detail Dokumen]

✨ Informasi Tambahan
[Info Tambahan]

🔍 Link Pencarian Arsip
[URL Pencarian]

🤝 Kontribusi
Kontribusi selalu diterima. Silakan buat pull request atau issue untuk perbaikan dan pengembangan.

📝 Lisensi
MIT License - Silakan gunakan dan modifikasi sesuai kebutuhan.

👨‍💻 Pengembang

Email: kontak@classy.id
GitHub: @classyid
