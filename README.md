# Slip Superapp (Generator Slip Gaji Online)

> **Generator Slip Gaji Karyawan Praktis, Cepat, dan 100% Gratis**  
> Dibuat untuk ekosistem **CHARISNA SuperApp**. Terinspirasi dari alat generator slip gaji [slip.gajihub.com](https://slip.gajihub.com/), direkayasa secara bersih (*clean-room reverse-engineered*) menggunakan tool **REA (Reverse Engineer Anything)**.

---

## ✨ Fitur Utama

- **Live In-Place Editing**: Edit nama perusahaan, identitas karyawan, tanggal periode, dan rincian gaji langsung di atas lembar slip.
- **Dukungan Logo Perusahaan**: Unggah logo perusahaan Anda secara instan (tersimpan aman di memori lokal peramban tanpa kirim ke server luar).
- **Tabel Pendapatan Dinamis**: Tambah, ubah nilai, atau hapus baris tunjangan dan bonus semaumu.
- **Tabel Potongan Dinamis**: Atur BPJS, PPh 21, kasbon, dan potongan lainnya secara otomatis.
- **Auto Calculation & Terbilang Bahasa Indonesia**: Kalkulasi *Take Home Pay* instan lengkap dengan ejaan teks resmi Rupiah (contoh: *"Enam Juta Enam Ratus Tujuh Puluh Lima Ribu Rupiah"*).
- **Theme Color Palette Switcher**: Pilihan 23 warna tema presisi (termasuk pink Gajihub `#E53F6A`, biru korporat, emerald, indigo, hingga custom color hex picker).
- **100% Client-Side Privacy**: Data gaji bersifat rahasia perusahaan (*confidential*). Sistem ini berjalan 100% di browser pengguna tanpa mengirim atau menyimpan data apa pun ke database/cloud eksternal.
- **Download PDF & Cetak A4**: Cetak langsung via browser atau unduh berkas PDF kualitas tinggi sekali klik.
- **Integrasi Kirim WhatsApp**: Salin dan bagikan ringkasan slip gaji ke WhatsApp karyawan secara terformat rapi.

---

## 🚀 Cara Menjalankan

Cukup buka berkas `index.html` langsung di peramban web apa pun (Google Chrome, Edge, Safari, Firefox), atau jalankan server lokal:

```bash
# Menggunakan Python
python -m http.server 8080

# Atau menggunakan Node / npx
npx serve .
```

Akses di `http://localhost:8080`.

---

## 🎨 Palet Warna Tema Resmi

Tersedia 23 palet warna tema yang dapat disesuaikan dengan identitas brand perusahaan Anda:
- `#E53F6A` (Default Gajihub Pink)
- `#3B82F6` (Royal Blue)
- `#10B981` (Emerald Green)
- `#F59E0B` (Amber Gold)
- `#8B5CF6` (Violet Purple)
- dan pemilih warna kustom HEX!

---

## 📜 Lisensi & Atribusi

- Dikembangkan untuk **CHARISNA SuperApp Ecosystem**.
- Dirancang khusus sesuai kebutuhan operasional UMKM, HR, dan manajemen usaha mandiri.
