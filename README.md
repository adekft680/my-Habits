# MY HABITS - Installable Web App (PWA)

Aplikasi ini sekarang dikonfigurasi sebagai **Progressive Web App (PWA)**, artinya aplikasi ini bisa diinstal langsung ke layar utama (Home Screen) HP seperti aplikasi asli.

## Cara Instal di HP Anda:

### Metode 1: Menggunakan Vercel, Netlify, atau GitHub Pages (Disarankan)
PWA mensyaratkan aplikasi berjalan di jaringan aman (HTTPS).
1. Upload folder ini ke hosting gratis seperti GitHub Pages, Vercel, atau Netlify.
2. Buka link web Anda di browser HP (Chrome/Safari).
3. Akan muncul tombol **"Instal Aplikasi"** di dalam aplikasi, ATAU browser akan menampilkan popup "Tambahkan ke Layar Utama".

### Metode 2: Uji Coba Lokal (Localhost)
Jika Anda menggunakan laptop/PC:
1. Anda memerlukan local server. Di terminal, jalankan: `npx serve` atau `python -m http.server`.
2. Buka `http://localhost:3000` atau `http://localhost:8000` di browser.
3. Klik ikon "Install" di pojok kanan address bar browser (Google Chrome).

## Fitur PWA:
- **Tampilan Fullscreen:** Hilangnya bar browser (URL bar) saat dibuka lewat shortcut.
- **Ikon Aplikasi:** Memiliki ikon di layar utama (home screen).
- **Service Worker:** Menyimpan cache aset agar loading lebih cepat.
