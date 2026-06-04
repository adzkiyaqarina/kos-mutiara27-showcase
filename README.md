<div align="center">

# 🏠 KosMutiara27 — Sistem Manajemen Kos

**Aplikasi web full-stack untuk mendigitalkan operasional kos/boarding house end-to-end.**

[![Live](https://img.shields.io/badge/🌐_Live_Demo-mutiara27.eightspace.cloud-10B981?style=for-the-badge)](https://mutiara27.eightspace.cloud)

`Laravel 12` · `PHP 8.2` · `Tailwind CSS` · `Alpine.js` · `MySQL` · `Vite` · `Google Gemini API`

</div>

---

> [!NOTE]
> Repositori ini adalah **etalase (showcase)** dari proyek. **Kode sumbernya privat** untuk menjaga keamanan data dan kredensial.
---

## ✨ Tentang Proyek

**KosMutiara27** adalah sistem manajemen kos yang saya bangun dari nol — mulai dari rancangan database, alur bisnis, hingga UI yang rapi. Aplikasi ini sudah **dipakai secara nyata** dan ter-deploy di production dengan domain sendiri, lengkap dengan landing page ber-SEO dan panel admin yang ramah untuk pengelola non-teknis.

🔗 **Lihat langsung:** [mutiara27.eightspace.cloud](https://mutiara27.eightspace.cloud)

## 🎯 Fitur Utama

- **Multi-peran (3 level akses):** Admin · Pemilik Kos · Penyewa, masing-masing dengan dashboard & hak akses sendiri.
- **Landing page dinamis & ber-SEO:** hero, galeri foto, fasilitas, tipe kamar, lokasi (Google Maps) — semua dapat dikelola dari panel admin tanpa menyentuh kode. Dilengkapi sitemap, Open Graph, dan data terstruktur (schema.org).
- **Manajemen kamar & tipe kamar:** master harga, kapasitas, status ketersediaan otomatis.
- **Alur reservasi penyewa:** booking online, unggah bukti bayar (disimpan di *private storage*), verifikasi pembayaran.
- **Tagihan & transaksi:** pencatatan tagihan bulanan dan riwayat pembayaran.
- **Laporan PDF & Excel:** ekspor data operasional (DomPDF & PhpSpreadsheet).
- **AI Assistant (Google Gemini):** asisten untuk analisis data bagi pemilik kos.
- **Keamanan:** otorisasi berlapis, file sensitif (KTP, bukti bayar) di storage privat, hardening menyeluruh.

## 🛠️ Tech Stack

| Kategori | Teknologi |
|---|---|
| Backend | Laravel 12, PHP 8.2 |
| Frontend | Blade, Tailwind CSS, Alpine.js, Vite |
| Database | MySQL |
| Laporan | DomPDF (PDF), PhpSpreadsheet (Excel) |
| AI | Google Gemini API |
| Deployment | VPS (Nginx + PHP-FPM), auto-deploy via Git webhook |

## 📸 Tampilan

> _Screenshot menyusul — sementara silakan kunjungi [demo live](https://mutiara27.eightspace.cloud)._

<!--
Tips: tambahkan screenshot di sini, mis:
![Landing Page](docs/landing.png)
![Dashboard Admin](docs/dashboard.png)
-->

---

<div align="center">

**Dibuat oleh [Adzkiya Qarina Salsabila](https://github.com/adzkiyaqarina)**
🌐 [Portfolio](https://adzkiyaqarinas.com) · 💼 [LinkedIn](https://www.linkedin.com/in/adzkiya-qarina-salsabila-612511410/)

</div>
