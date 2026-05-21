# 📁 Struktur Folder Website Gema Gamping

```
gema_gamping_website/
│
├── index.html              ← Halaman utama website
├── README.md               ← File ini (panduan project)
│
├── assets/                 ← Semua aset media
│   ├── images/
│   │   ├── cover/          ← Gambar cover buku (depan, belakang, mockup 3D)
│   │   ├── hero/           ← Background hero section
│   │   ├── galeri/         ← Ilustrasi preview buku (min 6 gambar)
│   │   ├── penulis/        ← Foto profil penulis/ilustrator
│   │   ├── tradisi/        ← Foto dokumentasi tradisi Saparan Bekakak
│   │   └── testimoni/      ← Foto pemberi testimoni (opsional)
│   │
│   ├── icons/              ← Icon custom (favicon, logo, dll)
│   └── fonts/              ← Font lokal (jika tidak pakai Google Fonts CDN)
│
├── css/                    ← File CSS tambahan (jika diperlukan)
├── js/                     ← File JavaScript tambahan (jika diperlukan)
│
└── data/
    └── konten.json         ← Data konten website (teks, harga, kontak, dll)
```

---

## 📋 Checklist Konten yang Perlu Disiapkan

### Wajib (Harus Ada)
- [ ] **Cover buku** → taruh di `assets/images/cover/`
  - cover-depan.jpg (min 800x1200px)
- [ ] **Ilustrasi galeri** → taruh di `assets/images/galeri/`
  - Minimal 6 gambar (min 1200x900px)
- [ ] **Foto penulis** → taruh di `assets/images/penulis/`
  - foto-profil.jpg (min 500x500px, rasio 1:1)

### Opsional (Direkomendasikan)
- [ ] Background hero → `assets/images/hero/hero-bg.jpg`
- [ ] Foto tradisi → `assets/images/tradisi/`
- [ ] Foto testimoni → `assets/images/testimoni/`
- [ ] Favicon → `assets/icons/favicon.ico`

### Data yang Perlu Diupdate
Edit file `data/konten.json` untuk mengubah:
- [ ] Nama penulis
- [ ] Universitas & program studi
- [ ] Nomor WhatsApp
- [ ] Rekening bank
- [ ] Harga buku
- [ ] ISBN
- [ ] Link social media
- [ ] Teks testimoni

---

## 🔧 Cara Mengedit

1. **Ganti gambar**: Taruh file gambar di folder yang sesuai, lalu update path di `index.html`
2. **Ganti teks**: Edit langsung di `index.html` atau gunakan `data/konten.json` sebagai referensi
3. **Ganti nomor WhatsApp**: Cari `6281234567890` di `index.html` dan ganti dengan nomor Anda
4. **Ganti harga**: Cari `120.000` dan `150.000` di `index.html`

---

## 🚀 Cara Deploy

### Opsi 1: GitHub Pages (Gratis)
1. Upload folder ini ke GitHub repository
2. Settings → Pages → Source: main branch
3. Website akan live di `https://username.github.io/repo-name`

### Opsi 2: Netlify (Gratis)
1. Drag & drop folder ini ke netlify.com/drop
2. Website langsung live!

### Opsi 3: Buka Langsung
Double-klik `index.html` untuk preview di browser.

---

© 2026 Gema Gamping: Kisah Sang Bekakak
