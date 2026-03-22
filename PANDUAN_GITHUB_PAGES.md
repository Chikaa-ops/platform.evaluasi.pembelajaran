# PANDUAN POSTING KE GITHUB & GITHUB PAGES
## Platform Evaluasi Pembelajaran Berbasis Teknologi

---

## 📋 LANGKAH 1: PERSIAPAN

### A. Buat Akun GitHub (Jika Belum Ada)
1. Buka https://github.com
2. Klik "Sign Up"
3. Isi email, password, username
4. Verifikasi email
5. Done! ✓

### B. Install Git (Opsional, tapi Recommended)
**Windows:**
- Download: https://git-scm.com/download/win
- Install dengan default settings
- Buka Command Prompt/PowerShell

**Mac:**
- Download: https://git-scm.com/download/mac
- Atau gunakan Homebrew: `brew install git`

**Linux:**
- `sudo apt-get install git`

---

## 📦 LANGKAH 2: BUAT REPOSITORY DI GITHUB

### Opsi A: Via Website GitHub (Paling Mudah)

**Langkah:**
```
1. Login ke GitHub
2. Klik icon + (atas kanan) → "New Repository"
3. Isi detail:
   - Repository name: "platform-evaluasi-pembelajaran"
   - Description: "Platform Evaluasi Pembelajaran Berbasis Teknologi"
   - Pilih "Public" (supaya bisa diakses siapa saja)
   - ✓ Centang "Add a README file"
   - ✓ Centang "Add .gitignore" → pilih None
   - ✓ Centang "Choose a license" → MIT License (bagus untuk project open source)
4. Klik "Create Repository"
```

**Hasil:**
Kamu akan punya repository kosong dengan URL seperti:
```
https://github.com/[username]/platform-evaluasi-pembelajaran
```

### Opsi B: Via Git Command Line

```bash
# Buat folder baru
mkdir platform-evaluasi-pembelajaran
cd platform-evaluasi-pembelajaran

# Initialize git
git init

# Add files
git add .

# Commit
git commit -m "Initial commit: Platform Evaluasi Pembelajaran"

# Add remote repository
git remote add origin https://github.com/[username]/platform-evaluasi-pembelajaran.git

# Push ke GitHub
git branch -M main
git push -u origin main
```

---

## 📤 LANGKAH 3: UPLOAD FILES KE GITHUB

### Opsi A: Upload via Website (Paling Mudah)

**Langkah:**
```
1. Buka repository yang baru dibuat
2. Klik "Add file" → "Upload files"
3. Drag & drop atau pilih file:
   - platform-evaluasi-pembelajaran.html
   - DOKUMENTASI_PLATFORM.md
   - PANDUAN_IMPLEMENTASI_PRAKTIS.md
   - README.md (buat file ini)
4. Scroll ke bawah, klik "Commit changes"
```

### Opsi B: Upload via Git Command Line

```bash
# Navigate ke folder repository
cd [folder-path]

# Copy files ke folder ini
# (Copy ketiga file HTML dan MD ke sini)

# Add all files
git add .

# Commit dengan message
git commit -m "Add: Platform files, documentation, dan panduan implementasi"

# Push ke GitHub
git push origin main
```

---

## 📝 LANGKAH 4: BUAT FILE README.md

Buat file `README.md` di root repository (ini yang muncul di halaman utama repo):

```markdown
# Platform Evaluasi Pembelajaran Berbasis Teknologi

Sistem evaluasi pembelajaran yang komprehensif dan mudah digunakan untuk guru, siswa, dan institusi pendidikan.

## 🎯 Fitur Utama

✅ **Soal & Kuis** - Buat soal pilihan ganda, essay, dan matching
✅ **Rubrik Penilaian** - Penilaian terstruktur dengan kriteria jelas
✅ **Portofolio Pembelajaran** - Dokumentasi perkembangan siswa
✅ **Observasi & Checklist** - Pencatatan sistematis perilaku dan kehadiran
✅ **Self-Assessment** - Refleksi diri dan evaluasi diri siswa
✅ **Peer-Assessment** - Penilaian dari teman sebaya
✅ **Analytics & Dashboard** - Laporan dan insight data pembelajaran

## 🚀 Akses Platform

### ⚡ Cara Paling Mudah (Recommended):
**Klik di sini: [Buka Platform](https://[username].github.io/platform-evaluasi-pembelajaran/)**

(Tunggu dulu sampai selesai langkah GitHub Pages di bawah)

### Alternatif: Download & Buka Lokal
1. Download file `platform-evaluasi-pembelajaran.html`
2. Double-click file untuk membuka di browser
3. Platform siap digunakan!

## 📚 Dokumentasi

- **[DOKUMENTASI_PLATFORM.md](./DOKUMENTASI_PLATFORM.md)** - Dokumentasi lengkap untuk referensi buku
  - Konsep evaluasi pembelajaran
  - Penjelasan fitur detail
  - Kerangka teori dan best practices
  - Studi kasus implementasi

- **[PANDUAN_IMPLEMENTASI_PRAKTIS.md](./PANDUAN_IMPLEMENTASI_PRAKTIS.md)** - Panduan praktis implementasi
  - Tutorial step-by-step
  - Tips & trik
  - Troubleshooting
  - Contoh nyata penggunaan
  - Checklist implementasi

## 🔧 Cara Menggunakan

### Untuk Guru:
1. Buka platform
2. Buat soal/rubrik/instrumen evaluasi sesuai kebutuhan
3. Bagikan kepada siswa
4. Monitor progress di dashboard

### Untuk Siswa:
1. Akses platform
2. Kerjakan soal yang diberikan guru
3. Lakukan self-assessment
4. Lihat feedback dari guru

### Untuk Kepala Sekolah:
1. Monitor implementasi di sekolah
2. Lihat laporan keseluruhan pencapaian siswa
3. Identifikasi area untuk improvement

## 💾 Penyimpanan Data

Platform menggunakan **Local Storage** browser untuk menyimpan data:
- ✅ Data tersimpan otomatis saat input
- ✅ Data aman dan tidak dihapus saat refresh
- ✅ Akses cepat tanpa perlu internet
- ⚠️ Data hanya tersimpan di browser lokal (jika clear cache, data hilang)

**Tips:** Backup data secara berkala dengan export/download

## 📖 Untuk Penulis Buku

Dokumentasi lengkap dalam folder ini bisa digunakan sebagai referensi untuk menulis buku "Evaluasi Pembelajaran Berbasis Teknologi". 

File yang berguna:
- `DOKUMENTASI_PLATFORM.md` - Konten lengkap untuk bab-bab buku
- `PANDUAN_IMPLEMENTASI_PRAKTIS.md` - Konten untuk bab implementasi

## 🎓 Teori Pembelajaran yang Diintegrasikan

Platform ini didasarkan pada:
- Bloom's Taxonomy (Revisi)
- Multiple Intelligences (Kecerdasan Majemuk)
- Constructivism (Konstruktivisme)
- Assessment As Learning, For Learning, Of Learning
- Authentic Assessment (Penilaian Autentik)

## 📋 Contoh Penerapan

Platform cocok untuk:
- Penilaian formatif (selama pembelajaran)
- Penilaian sumatif (akhir periode)
- Dokumentasi portofolio
- Pembelajaran berbasis projek
- Pembelajaran kolaboratif
- Kelas hybrid/daring

## 🔐 Lisensi

MIT License - Bebas digunakan untuk keperluan komersial maupun non-komersial

## 👥 Kontribusi

Jika ingin memberikan saran atau kontribusi:
1. Fork repository ini
2. Buat branch baru: `git checkout -b feature/improvement`
3. Commit changes: `git commit -m 'Add: deskripsi improvement'`
4. Push ke branch: `git push origin feature/improvement`
5. Buat Pull Request

## ❓ FAQ

### Q: Apakah data aman?
A: Data tersimpan di browser lokal Anda. Lebih aman jika tidak ada koneksi internet.

### Q: Bisa pakai offline?
A: Ya! Buka file HTML sekali di online, setelah itu bisa digunakan offline.

### Q: Bisa add users/siswa?
A: Untuk versi ini baru bisa dipakai 1 perangkat. Untuk multi-user, perlu upgrade ke server backend.

### Q: Gimana kalau data hilang?
A: Backup data secara berkala. Jangan clear browser cache tanpa backup.

### Q: Bisa customize warna/design?
A: Bisa! Edit file CSS di bagian `<style>` di file HTML.

## 📞 Support

Untuk pertanyaan atau issue:
1. Buka GitHub Issues
2. Jelaskan masalah dengan detail
3. Sertakan screenshot jika perlu

## 🎯 Roadmap

- [ ] Multi-user support (login/dashboard per user)
- [ ] Export laporan ke PDF/Excel
- [ ] Mobile app version
- [ ] Backend dengan database
- [ ] Integration dengan LMS (Google Classroom, Moodle, dll)
- [ ] Advanced analytics
- [ ] Multi-language support

## 📄 Lisensi

MIT License - Lihat file [LICENSE](./LICENSE)

---

**Dibuat dengan ❤️ untuk meningkatkan kualitas evaluasi pembelajaran di Indonesia**

Platform ini adalah bagian dari buku:
**"Evaluasi Pembelajaran Berbasis Teknologi"**

Terakhir diupdate: [Tanggal Hari Ini]
```

**Cara menambah README.md:**
```
1. Di GitHub, klik "Add file" → "Create new file"
2. Nama file: README.md
3. Copy-paste isi di atas
4. Sesuaikan [username] dengan username GitHub kamu
5. Klik "Commit new file"
```

---

## 🌐 LANGKAH 5: ENABLE GITHUB PAGES (Buat URL)

Ini yang paling penting buat dapet URL! 

### Langkah:

**1. Buka Settings Repository**
```
Klik "Settings" di tab repository
```

**2. Scroll ke "Pages"**
```
Di sidebar sebelah kiri, cari "Pages"
```

**3. Setup GitHub Pages**
```
Build and deployment
├─ Source: Deploy from a branch
├─ Branch: main
└─ Folder: / (root)

Klik "Save"
```

**4. Tunggu beberapa menit...**
- GitHub akan build project kamu
- Nanti muncul message: "Your site is published at https://[username].github.io/platform-evaluasi-pembelajaran/"

**5. Akses Platform via URL**
```
https://[username].github.io/platform-evaluasi-pembelajaran/
```

### ⚠️ PENTING: Nama File HTML

Kalau nama file HTML bukan `index.html`, GitHub Pages mungkin error.

**Solusi:**
Rename file menjadi `index.html` ATAU akses dengan nama file lengkap:
```
https://[username].github.io/platform-evaluasi-pembelajaran/platform-evaluasi-pembelajaran.html
```

---

## ✅ LANGKAH 6: TEST & VERIFY

### Test URL:

**1. Akses via GitHub Pages**
```
https://[username].github.io/platform-evaluasi-pembelajaran/
```

**2. Test Fungsi Platform**
- ✓ Klik tab-tab menu
- ✓ Buat soal dan simpan
- ✓ Buat rubrik dan simpan
- ✓ Cek data tersimpan setelah refresh
- ✓ Lihat analytics

**3. Verifikasi Dokumentasi**
- ✓ README.md muncul di halaman depan repo
- ✓ DOKUMENTASI_PLATFORM.md bisa dibuka
- ✓ PANDUAN_IMPLEMENTASI_PRAKTIS.md bisa dibuka

---

## 🎯 LANGKAH 7: SHARE & SPREAD THE WORD

Setelah semuanya ready, kamu bisa share:

### A. Share Repository Link
```
Untuk developers/technical people:
https://github.com/[username]/platform-evaluasi-pembelajaran
```

### B. Share Platform Link
```
Untuk guru/siswa/umum:
https://[username].github.io/platform-evaluasi-pembelajaran/
```

### C. Share di Social Media
```
"🎓 Platform Evaluasi Pembelajaran Berbasis Teknologi siap dipakai!

✨ Fitur:
✅ Soal & Kuis
✅ Rubrik Penilaian
✅ Portofolio
✅ Self-Assessment
✅ Peer-Assessment
✅ Analytics

📱 Akses gratis di: [URL]
📚 Dokumentasi lengkap di GitHub

Cocok untuk guru, siswa, dan institusi pendidikan!

#Pendidikan #Teknologi #EvaluasiPembelajaran"
```

### D. Update Resume/Portfolio
```
Tambah di portfolio:

"Platform Evaluasi Pembelajaran Berbasis Teknologi"
- Built: HTML, CSS, JavaScript
- Features: Multi-method evaluation system
- GitHub: [link]
- Live Demo: [link]
```

---

## 📊 STATISTIK & MONITOR

Setelah publish, kamu bisa monitor:

### A. GitHub Insights
- Klik "Insights" di repo
- Lihat traffic, forks, stars, dll

### B. GitHub Pages Analytics
- Setting → Pages
- Lihat visitor stats (kalau di-enable)

### C. Recommendation
- Add "Star" button ke README
- Encourage people untuk fork dan contribute
- Maintain & update secara berkala

---

## 🔄 UPDATE & MAINTENANCE

### Jika mau update/edit file:

**Via Website:**
```
1. Buka file yang mau diedit
2. Klik icon pensil (Edit)
3. Edit konten
4. Klik "Commit changes"
```

**Via Git Command:**
```bash
# Edit file lokal
nano/edit platform-evaluasi-pembelajaran.html

# Commit & push
git add platform-evaluasi-pembelajaran.html
git commit -m "Update: perbaikan fitur X"
git push origin main
```

### Update akan langsung muncul di website!

---

## 🚀 BONUS: ADVANCED SETUP

### A. Custom Domain (Opsional)
```
Jika punya domain sendiri:
Settings → Pages → Custom domain
Contoh: evaluasi.namadomainmu.com
```

### B. Add License
```
Klik "Add file" → "Create new file"
Nama: LICENSE
Pilih template MIT (recommended untuk open source)
```

### C. Add Contributing Guidelines
```
Buat file CONTRIBUTING.md
Jelaskan cara contribute ke project
```

### D. Add Badges (Optional tapi Keren!)
```
Di README.md, tambah di atas:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-platform--evaluasi-blue)](https://github.com/[username]/platform-evaluasi-pembelajaran)

Ini muncul sebagai badge kecil yang keren di README
```

---

## 📋 CHECKLIST AKHIR

```
✓ Buat akun GitHub
✓ Buat repository "platform-evaluasi-pembelajaran"
✓ Upload 3 file (HTML, 2 MD)
✓ Buat README.md
✓ Enable GitHub Pages
✓ Test akses via URL
✓ Verify semua fitur berfungsi
✓ Share ke social media
✓ Add ke portfolio
✓ Monitor & maintain
```

---

## 🎉 DONE!

Sekarang kamu punya:
1. **Repository GitHub** - Tempat code tersimpan & version control
2. **Live Platform** - URL bisa diakses siapa saja
3. **Dokumentasi Lengkap** - Panduan untuk pengguna dan developer
4. **Portfolio Piece** - Bagus untuk CV dan interview

URL yang bisa di-share:
```
GitHub: https://github.com/[username]/platform-evaluasi-pembelajaran
Platform: https://[username].github.io/platform-evaluasi-pembelajaran/
```

---

## ❓ TROUBLESHOOTING GITHUB PAGES

### Masalah: "404 Not Found"
**Solusi:**
- Pastikan GitHub Pages di-enable di Settings
- Tunggu 2-3 menit setelah setup
- Nama file harus `index.html` atau akses dengan nama lengkap
- Clear cache browser (Ctrl+Shift+Delete)

### Masalah: "Site not found"
**Solusi:**
- Tunggu lebih lama (biasanya 5-10 menit)
- Check apakah folder benar (main branch)
- Lihat status di Settings → Pages

### Masalah: Fitur tidak bekerja
**Solusi:**
- Pastikan JavaScript enabled di browser
- Cek console (F12 → Console) untuk error
- Coba di browser lain
- Clear LocalStorage jika ada issue

---

**Selamat! Platform Evaluasi Pembelajaran Berbasis Teknologi kamu sekarang live di GitHub Pages!** 🚀

Bisa di-share, di-use, dan di-develop lebih lanjut! 🎉
