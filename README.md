# Roadmap Investasi

Personal investment goal tracker dengan sistem tier unlock.

## Cara Deploy ke GitHub Pages

### 1. Buat repo baru di GitHub
- Buka https://github.com/new
- Nama repo: `roadmap-investasi` (atau bebas)
- Set ke **Public**
- Klik "Create repository"

### 2. Upload file
Di halaman repo yang baru dibuat:
- Klik **"uploading an existing file"**
- Drag & drop file `index.html` ke sana
- Klik **"Commit changes"**

### 3. Aktifkan GitHub Pages
- Buka tab **Settings** di repo
- Klik **Pages** di sidebar kiri
- Di bagian "Source", pilih **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Klik **Save**

### 4. Tunggu 1-2 menit
URL halaman kamu akan muncul di:
```
https://[username].github.io/roadmap-investasi/
```

---

## Cara pakai

### Update progress
Klik tombol **Update** di tiap kartu goal, masukkan jumlah yang sudah terkumpul dalam Rupiah penuh (contoh: 1500000 untuk Rp 1,5 juta).

### Tambah goal baru
Klik tombol **+ Tambah Goal** di pojok kanan atas. Pilih tier, isi nama, target, dan kategori.

### Edit / hapus goal
Klik tombol **Edit** di kartu goal manapun.

### Sistem tier unlock
- Tier 2 terbuka otomatis setelah **semua** goal Tier 1 mencapai 100%
- Tier 3 terbuka setelah semua Tier 2 selesai
- Tier 4 terbuka setelah semua Tier 3 selesai

### Penyimpanan
Progress tersimpan di `localStorage` browser. Artinya:
- Tersimpan permanen di device yang sama
- Tidak otomatis sync ke device lain
- Untuk update dari HP lain: update manual di masing-masing device

---

## Struktur goal default

| Tier | Goal | Target |
|------|------|--------|
| 1 | Kandang Benji baru | Rp 4 jt |
| 1 | Berobat kulit | Rp 500 rb |
| 1 | Outfit | Rp 1,5 jt |
| 1 | Setup kerja | Rp 5 jt |
| 2 | Investasi kopi | Rp 2 jt |
| 2 | Ganti modal Bali | Rp 10,7 jt |
| 2 | Modal ekspor | Rp 5 jt |
| 3 | Modal Emas | Rp 10 jt |
| 3 | Dana Darurat 3 Bulan | Rp 18 jt |
| 4 | Modal Nikah | Rp 100 jt |
| 4 | Diving | Rp 5 jt |
