# 💰 Mint Keuangan

Aplikasi web **keuangan pribadi** sederhana — satu file `index.html`, tanpa framework, tanpa dependensi, tanpa server. Cukup buka di browser dan langsung pakai.

## ✨ Fitur

### Tab Ringkasan
- ➕ Catat **pemasukan & pengeluaran** (tambah / edit / hapus dengan tombol *Urungkan*)
- 📊 Kartu ringkasan bulanan: pemasukan, pengeluaran, selisih, rasio tabungan — **terhitung otomatis**
- 🍩 Grafik donat **pengeluaran per kategori**
- 📈 Grafik batang **pemasukan vs pengeluaran 6 bulan terakhir**
- 🎯 **Anggaran bulanan** per kategori dengan indikator progres (hijau → kuning → merah)
- 🧾 Daftar transaksi dengan filter (Semua / Pemasukan / Pengeluaran), navigasi per bulan

### Tab Laporan
- 📅 **Laporan mingguan** (Senin–Minggu) dan **bulanan**
- 📊 Kartu statistik dengan **perbandingan % vs periode sebelumnya**
- 📈 Grafik tren harian + garis rata-rata per hari
- 📋 Rincian kategori (belanja, perubahan, porsi) & 5 **pengeluaran terbesar**
- 🗓️ Rincian **per minggu** dalam laporan bulanan
- 🤖 **Wawasan otomatis**: kategori terbesar, proyeksi akhir bulan, peringatan anggaran, dll.
- 🖨️ **Cetak / Simpan PDF** dengan tata letak khusus cetak

### Lainnya
- 💱 Pilihan mata uang (**default Rupiah — format Indonesia**, dukung $ € £ ₺ ₾)
- 💾 Data tersimpan otomatis di `localStorage` browser (privat, tidak dikirim ke mana pun)
- ⬇️⬆️ **Ekspor / Impor** data JSON & ekspor CSV
- 📱 Responsif untuk ponsel & desktop

## 🚀 Cara Pakai

**Cara termudah — buka langsung filenya:**

1. Unduh `index.html`
2. Klik dua kali untuk membuka di browser
3. Selesai — mulai catat keuangan Anda!

**Atau lewat GitHub Pages:**

1. Buka **Settings → Pages** di repositori ini
2. Pilih Source: **Deploy from a branch** → Branch: `main` / `(root)`
3. Aplikasi live di `https://azis0101.github.io/tesarena/`

> Karena semuanya client-side, data tetap tersimpan di browser masing-masing pengunjung.

## 🛠️ Teknologi

- HTML5 + CSS3 + JavaScript murni (vanilla) — **satu file**, tanpa build step
- Grafik = SVG yang dirender manual (tanpa library chart)
- Penyimpanan = `localStorage` (dengan fallback memori)

## 📄 Struktur

```
tesarena/
├── index.html   # seluruh aplikasi (HTML + CSS + JS)
└── README.md
```

---

Dibuat sebagai proyek belajar — bebas dipakai dan dimodifikasi. 🎉
