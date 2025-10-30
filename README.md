# Employee Management Portal

Website statis untuk Employee Management Portal dengan desain modern dan corporate style.

## 📋 Daftar Isi

- [Fitur](#fitur)
- [Struktur Folder](#struktur-folder)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Cara Membuka](#cara-membuka)
- [Halaman Tersedia](#halaman-tersedia)
- [Palet Warna](#palet-warna)

## ✨ Fitur

- **Homepage** - Halaman utama dengan pengenalan portal dan fitur utama
- **Welcome** - Panduan onboarding dengan checklist lengkap untuk karyawan baru
- **Dokumen & Kebijakan** - Akses handbook, kebijakan, form, struktur organisasi, dan kontak penting
- **Pelatihan & E-Learning** - Modul pelatihan komprehensif dengan berbagai kategori pembelajaran
- **FAQ & Knowledge Base** - Tanya jawab kategori umum, HR, IT, dan benefit
- **Berita & Pengumuman** - Update berita perusahaan dan integrasi Microsoft Teams
- **Feedback & Survey** - Program feedback, survei aktif, dan analisis hasil survei

## 📁 Struktur Folder

```
website/
├── index.html              # Homepage utama
├── pages/
│   ├── welcome.html        # Halaman Welcome
│   ├── documents.html      # Halaman Dokumen & Kebijakan
│   ├── training.html       # Halaman Training & E-Learning
│   ├── faq.html           # Halaman FAQ & Knowledge Base
│   ├── news.html          # Halaman Berita & Pengumuman
│   └── feedback.html      # Halaman Feedback & Survey
└── assets/                # Folder untuk aset (opsional)
    └── (Dapat ditambahkan kemudian)
```

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur semantik
- **Tailwind CSS** - Framework CSS untuk styling modern
- **Bootstrap Icons** - Icon library dari Bootstrap
- **Placeholder Images** - Gambar placeholder dari placehold.co

## 🚀 Cara Membuka

### Metode 1: Membuka Langsung di Browser
1. Buka file `index.html` dengan double-click
2. Atau klik kanan pada file → "Open with" → pilih browser favorit Anda

### Metode 2: Menggunakan Local Server (Recommended)

#### Dengan Python
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

#### Dengan Node.js (jika ada http-server)
```bash
npx http-server
```

Kemudian buka browser dan akses `http://localhost:8000`

## 📄 Halaman Tersedia

### 1. **Homepage** (index.html)
- Selamat datang dengan hero section yang menarik
- 6 kartu fitur utama portal
- Statistik perusahaan
- Call-to-action untuk memulai
- Footer dengan informasi kontak

### 2. **Welcome** (pages/welcome.html)
- Sambutan untuk karyawan baru
- Checklist onboarding 6 langkah
- Link cepat ke halaman penting
- Informasi penting (durasi onboarding, kontak HR, IT support)

### 3. **Dokumen & Kebijakan** (pages/documents.html)
- Employee Handbook dengan download options
- 5 kebijakan perusahaan utama
- Form penting untuk diisi
- Struktur organisasi visual
- Kontak penting dari berbagai departemen (HR, IT, Finance, General)

### 4. **Pelatihan & E-Learning** (pages/training.html)
- Featured training untuk onboarding
- 6 modul pelatihan utama (Beginner, Intermediate, Advanced)
- 4 pelatihan khusus (Teams, Security, Diversity, Wellness)
- 4 sumber daya pembelajaran (E-Books, Video, Podcast, Community)

### 5. **FAQ & Knowledge Base** (pages/faq.html)
- 4 kategori FAQ (Umum, HR, IT, Benefit)
- Expandable questions dengan detail jawaban
- Search bar untuk pencarian
- Sidebar dengan daftar topik populer
- Quick help section

### 6. **Berita & Pengumuman** (pages/news.html)
- Featured news terbaru
- Grid berita 2x2
- Pengumuman terbaru dengan border status
- Kategori berita
- Newsletter subscription
- Integrasi Microsoft Teams

### 7. **Feedback & Survey** (pages/feedback.html)
- Pengenalan program feedback
- 3 survei aktif dengan progress bar
- 4 tipe formulir feedback
- Hasil survei sebelumnya
- Panduan dan guidelines

## 🎨 Palet Warna

Website menggunakan palet warna corporate modern dengan kombinasi:

- **Hijau Muda (Primary)**: `#10b981` - Warna utama untuk aksi dan highlight
- **Hijau Muda Light**: `#d1fae5` - Background dan hover states
- **Oranye (Secondary)**: `#f97316` - Warna accent dan alternatif
- **Putih**: `#ffffff` - Background utama
- **Abu-abu**: `#1f2937`, `#374151`, `#6b7280` - Text dan border
- **Dark**: `#1f2937` - Footer dan header

## 📱 Responsive Design

Website dirancang untuk responsif di semua ukuran layar:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (< 768px)

## 🔗 Navigasi

Semua halaman terhubung melalui navigation bar yang konsisten dengan link ke:
- Home
- Welcome
- Dokumen
- Training
- FAQ
- Berita
- Feedback

## 📝 Font dan Typography

Menggunakan font default Tailwind CSS dengan stack:
- Segoe UI
- Tahoma
- Geneva
- Verdana
- Sans-serif

## 🖼️ Gambar Placeholder

Semua gambar menggunakan layanan placehold.co dengan format:
- `https://placehold.co/[width]x[height]/[background-color]/[text-color]?text=[text]`

Contoh:
- `https://placehold.co/700x400/d1fae5/10b981?text=Employee+Portal`

## ⚡ Performa

- **Tidak ada JavaScript kompleks** - Website murni HTML & CSS
- **CDN untuk library** - Tailwind CSS dan Bootstrap Icons dari CDN
- **Lightweight** - Loading cepat dan responsif
- **SEO-friendly** - Struktur HTML semantik yang baik

## 📧 Kontak Support

Dalam portal, karyawan dapat menghubungi:
- **HR**: hr@company.com | +62 (0)21 1234 5678
- **IT Support**: support@company.com | +62 (0)21 1234 5679
- **Finance**: finance@company.com | +62 (0)21 1234 5680

## 📄 Lisensi

Corporate portal untuk penggunaan internal perusahaan.

---

**Dibuat dengan ❤️ menggunakan Tailwind CSS dan Bootstrap Icons**
**Last Updated: Oktober 2024**
