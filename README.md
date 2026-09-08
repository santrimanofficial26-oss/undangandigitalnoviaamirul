# Undangan Digital Novia & Amirul (Maron Black Luxury Theme)

Undangan pernikahan digital mewah bertema **Maron Black Luxury** untuk pernikahan **Novia Sri Lestari & Amirul Muthohar Ma'ruf** (Minggu, 20 September 2026).

---

## 🏛️ Arsitektur Sistem

1. **Vercel Frontend Wrapper (`index.html`)**:
   - Membungkus Google Apps Script Web App dalam iframe responsif 100% full-screen.
   - Dilengkapi **SEO Meta Tags Lengkap**, **OpenGraph WhatsApp/Facebook Card** beresolusi tinggi (1200x800), **Twitter Card**, dan **Theme Color** mobile browser.
   - Meneruskan query parameter nama tamu secara otomatis (`?to=Nama+Tamu`) ke dalam iframe.
   - Animasi splash loader mewah Maron Black monogram `N & A`.
2. **Google Apps Script Backend Engine (`kode.gs`)**:
   - Web App URL: `https://script.google.com/macros/s/AKfycbyO99Bnmm0Z_WXg6swRtcgDGiB-H9qmBoxsn3iRTah3-mT1wZXMa9M3nb6i3lIamOiptQ/exec`
   - Menyimpan konfirmasi kehadiran (RSVP) & ucapan doa restu ke Google Sheets.
3. **Template Standalone (`invitation.html`)**:
   - Kode sumber lengkap antarmuka undangan digital (Section Mempelai, Rangkaian Acara, Countdown Timer, Peta Lokasi, Galeri Foto WebP dengan Lightbox, Love Story, RSVP, dan Wedding Gift rekening BRI).
4. **Musik Latar**:
   - Lagu Pernikahan Kita (`audio-lagu-pernikahan-kita.mp3`).

---

## 🚀 Cara Hubungkan & Deploy ke Vercel

1. Buka dashboard Vercel di [vercel.com](https://vercel.com).
2. Klik **"Add New..."** -> **"Project"**.
3. Hubungkan akun GitHub Anda dan pilih repositori:
   `santrimanofficial26-oss/undangandigitalnoviaamirul`
4. Biarkan pengaturan **Framework Preset** default (`Other`) dan **Root Directory** (`./`).
5. Klik **"Deploy"**.
6. Website akan langsung aktif dalam beberapa detik dengan domain kustom Vercel, misalnya:
   `https://undangandigitalnoviaamirul.vercel.app`

---

## 📲 Format Link WhatsApp untuk Tamu Undangan

Gunakan format URL berikut saat membagikan undangan:

```text
https://undangandigitalnoviaamirul.vercel.app/?to=Nama+Tamu
```

Contoh:
- `https://undangandigitalnoviaamirul.vercel.app/?to=Budi+Santoso`
- `https://undangandigitalnoviaamirul.vercel.app/?to=Keluarga+Besar+Santriman`

Ketika link dibagikan di WhatsApp, kartu pratinjau (preview card) otomatis menampilkan foto prewedding besar, judul elegan, serta nama tamu otomatis masuk ke dalam undangan.
