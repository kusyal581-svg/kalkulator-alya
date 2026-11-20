# 🌸 Kalkulator Minimalist Swiss-Modern // Pastel Milk Edition

Aplikasi web kalkulator modern, elegan, dan responsif dengan filosofi desain *Minimalist Swiss-Modernism* yang terinspirasi oleh perangkat keras *Teenage Engineering* dan *Nothing OS*, dipadukan dengan palet warna lembut *Soft Pink & Pastel Milk*.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## ✨ Fitur Unggulan

- **Desain Estetis & Taktil:**
  - Latar belakang *soft pink pastel* (`#FCEEF1`) dengan pola arsitektural *subtle dot-grid* (`#EBD5DB`).
  - Bodi kalkulator putih gading lembut (`#FFFDF9`) dengan radius membulat halus (`28px`), garis tepi coklat susu muda (`#E8DFD5`), dan bayangan berlapis yang realistis.
  - Efek tekanan fisik (*tactile press effect*) pada tombol saat diklik.
  - Sintesis audio klik mikro mekanis (*Web Audio API*) murni tanpa file eksternal (dapat di-mute/unmute lewat tombol speaker).
- **Layar Ganda Presisi (*Dual Display*):**
  - Baris atas: Riwayat / ekspresi hitungan yang sedang berjalan (contoh: `1,500 × 4 +`).
  - Baris bawah: Hasil utama dengan fitur *auto-scaling font* otomatis agar angka panjang tidak terpotong.
- **Operasi Lengkap:**
  - Penjumlahan (`+`), pengurangan (`−`), perkalian (`×`), pembagian (`÷`), persentase (`%`), negasi tanda (`±`), hapus digit (`DEL`), dan reset (`AC`).
  - Penanganan eror elegan (*"Cannot divide by 0"*) tanpa *crash*.
  - Format ribuan otomatis dengan tanda koma (`1,000,000`).
  - Presisi titik kambang rapi tanpa *floating point noise* (contoh: `0.1 + 0.2 = 0.3`).
- **Fitur Salin Cepat (*Click to Copy*):**
  - Cukup klik area layar untuk menyalin hasil kalkulasi ke clipboard dengan notifikasi *toast* `"Tersalin!"`.
- **Mode Terang & Gelap (*Light & Dark Mode*):**
  - Saklar toggle di sudut atas dengan palet *Warm Espresso Plum & Slate Night* yang nyaman di mata.
- **Pintasan Keyboard Fisik Lengkap:**
  - Mendukung input angka `0-9`, operator `+ - * /`, `Enter` / `=` untuk hasil, `Backspace` untuk hapus, `Escape` / `C` untuk reset, dan `%`.

---

## ⌨️ Panduan Pintasan Keyboard

| Tombol Keyboard | Fungsi |
| :--- | :--- |
| **`0` – `9`** | Input angka |
| **`.`** atau **`,`** | Titik desimal |
| **`+`**, **`-`**, **`*`** (atau `x`), **`/`** | Operator matematika |
| **`Enter`** atau **`=`** | Menghitung hasil |
| **`Backspace`** | Hapus satu digit (`DEL`) |
| **`Escape`** atau **`C`** | Reset semua (`AC`) |
| **`%`** | Persentase |

---

## 🚀 Cara Menjalankan

Aplikasi ini dibuat secara mandiri dalam satu file `index.html` tanpa ketergantungan *build tool* atau pustaka eksternal.

1. *Clone* repositori ini:
   ```bash
   git clone https://github.com/kusyal581-svg/kalkulator-alya.git
   ```
2. Buka file `index.html` langsung di browser favorit Anda (Google Chrome, Microsoft Edge, Firefox, Safari).

---

Dibuat dengan ❤️ dan presisi Swiss-Modernism.
