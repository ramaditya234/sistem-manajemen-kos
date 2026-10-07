# Naskah Diskusi Klien — Sistem Informasi Manajemen Kos Berbasis Web

**Tim:** Joya, Ridho, Masan  
**Tujuan:** Diskusi awal dengan pemilik kos untuk memahami kebutuhan dan menentukan arah pengembangan sistem  
**Gaya:** Semi santai, singkat, tidak terlalu formal

---

## 1. Pembukaan — Joya

> “Selamat siang, Bu. Terima kasih sudah meluangkan waktu buat ketemu kami.
>
> Perkenalkan, saya Joya, ini Ridho dan Masan. Kami bertiga satu tim.
>
> Tujuan kami ke sini sebenarnya mau diskusi soal proyek yang sedang kami kerjakan. Kami diminta membuat sistem informasi yang nantinya benar-benar bisa dipakai oleh mitra.
>
> Karena Ibu mengelola kos putri, kami kepikiran untuk mengembangkan **Sistem Informasi Manajemen Kos Berbasis Web** yang bisa membantu pengelolaan kos.
>
> Tapi kami belum mau langsung menentukan sistemnya harus seperti apa. Kami ingin tahu dulu bagaimana Ibu mengelola kos selama ini dan bagian mana yang memang perlu dibantu dengan sistem.”

---

## 2. Jika Pemilik Bertanya: “Sistemnya seperti apa?”

### Joya

> “Gambaran awalnya, Bu, sistem ini berbentuk website untuk membantu pengelolaan kos dalam satu tempat.
>
> Misalnya untuk melihat data kamar, data penghuni, kamar yang kosong atau terisi, pembayaran, dan kebutuhan lain yang memang penting untuk Ibu.”

### Ridho

> “Contohnya, kalau ada penghuni baru masuk ke kamar nomor 5, datanya bisa langsung dicatat di sistem dan kamar itu otomatis tercatat sebagai terisi.
>
> Kalau pembayaran memang perlu dimasukkan juga, nanti Ibu bisa lihat riwayat pembayaran dan siapa yang sudah atau belum membayar.
>
> Tapi fitur-fitur ini masih gambaran awal, Bu. Kami ingin menyesuaikannya dengan kebutuhan kos Ibu.”

---

## 3. Jika Pemilik Bertanya: “Kenapa harus pakai sistem?”

### Masan

> “Tujuannya bukan untuk mengubah semua cara kerja Ibu, Bu.
>
> Kami ingin membantu supaya informasi kos lebih rapi dan lebih gampang dicek. Jadi data kamar, penghuni, pembayaran, atau informasi penting lainnya tidak perlu dicari satu-satu dari tempat yang berbeda.”

---

## 4. Cara Kami Mengembangkan Sistem

### Masan

> “Kalau Ibu berkenan, tahap awalnya kami akan diskusi dan menggali kebutuhan dulu.
>
> Setelah itu kami buat rancangan awal sistem. Rancangannya nanti kami tunjukkan lagi ke Ibu supaya bisa dikoreksi sebelum masuk ke tahap pembuatan.
>
> Kalau sudah sesuai, baru kami lanjut ke pengembangan, pengujian, sampai nanti sistemnya bisa dicoba dan digunakan.”

---

## 5. Transisi ke Sesi Diskusi — Joya

> “Kurang lebih itu gambaran awal dari kami, Bu.
>
> Tapi supaya kami tidak salah merancang, kami ingin dengar langsung dari Ibu bagaimana pengelolaan kos yang sekarang.”

Lanjutkan dengan:

> “Kalau boleh tahu, selama ini untuk mencatat data kamar dan penghuni biasanya Ibu pakai apa?”

---

## Pertanyaan Diskusi untuk Pemilik Kos

Gunakan seperlunya mengikuti arah percakapan.

1. Selama ini data kamar dan penghuni dicatat menggunakan apa?
2. Ada berapa kamar dan berapa yang biasanya terisi?
3. Bagaimana Ibu mengetahui kamar yang kosong dan kamar yang terisi?
4. Kalau ada penghuni baru, data apa saja yang biasanya dicatat?
5. Sistem sewanya bulanan, tahunan, atau ada pilihan lain?
6. Pembayaran kos biasanya dilakukan lewat apa?
7. Bagaimana cara Ibu mencatat siapa yang sudah dan belum membayar?
8. Apakah pernah ada kesulitan mencari riwayat pembayaran penghuni?
9. Apakah ada uang deposit, denda, atau biaya tambahan lainnya?
10. Kalau ada penghuni keluar, bagaimana proses pencatatannya?
11. Kalau ada kerusakan atau keluhan fasilitas, biasanya penghuni melapor lewat apa?
12. Apakah Ibu membutuhkan riwayat keluhan atau perbaikan?
13. Apakah penghuni perlu punya akun sendiri di sistem?
14. Informasi apa yang paling ingin Ibu lihat ketika membuka sistem?
15. Menurut Ibu, bagian pengelolaan kos yang sekarang paling merepotkan apa?

---

## Gambaran Konsep Awal

```text
PEMILIK / ADMIN
      │
      ├── Data Kamar
      ├── Data Penghuni
      ├── Data Sewa
      ├── Pembayaran
      ├── Keluhan
      └── Laporan
```

Contoh alur sederhana:

```text
Kamar Kosong
    ↓
Penghuni Masuk
    ↓
Data Sewa Dibuat
    ↓
Kamar Menjadi Terisi
    ↓
Pembayaran Dicatat
    ↓
Riwayat / Laporan
```

---

## Pembagian Peran Tim

### Joya
- Membuka pertemuan
- Menjelaskan tujuan kedatangan
- Menjelaskan konsep secara umum
- Memimpin sesi diskusi
- Menutup pertemuan

### Ridho
- Memberikan contoh gambaran sistem
- Menjelaskan alur penggunaan dari sisi pemilik kos

### Masan
- Menjelaskan proses pengembangan
- Menggali proses kerja dan kebutuhan klien

---

## Penutup — Joya

> “Baik Bu, dari diskusi hari ini nanti kami akan rangkum kebutuhan yang sudah Ibu sampaikan.
>
> Setelah itu kami coba buat rancangan awal sistemnya. Nanti sebelum kami mulai membuat aplikasinya, rancangan itu akan kami tunjukkan lagi ke Ibu supaya kita bisa memastikan sudah sesuai.
>
> Terima kasih banyak, Bu, sudah bersedia berdiskusi dan membantu proyek kami.”

---

## Catatan untuk Tim

- Jangan langsung menjanjikan fitur.
- Hindari istilah teknis seperti database, API, Laravel, hosting, dan VPS saat diskusi awal kecuali ditanya.
- Fokus pada cara pemilik kos bekerja sekarang.
- Dengarkan lebih banyak daripada menjelaskan.
- Catat masalah yang benar-benar dirasakan klien.
- Setelah wawancara, baru tentukan fitur final dan perbarui PRD.
