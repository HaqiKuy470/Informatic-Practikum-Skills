# Format Laporan Standar

Digunakan jika tidak ada template dari dosen/kampus.
Format ini umum dipakai di mayoritas kampus informatika Indonesia.

---

## Struktur laporan standar

```
1. HALAMAN JUDUL
2. TUJUAN PRAKTIKUM
3. DASAR TEORI
4. ALAT DAN BAHAN
5. LANGKAH KERJA
6. HASIL DAN PEMBAHASAN
7. KESIMPULAN
8. DAFTAR PUSTAKA (jika diminta)
```

---

## Penjelasan tiap bagian

### 1. Halaman Judul
Berisi:
- Judul praktikum (misal: "Laporan Praktikum — Sorting Algorithm")
- Mata kuliah
- Nama mahasiswa + NIM
- Kelas / kelompok
- Nama dosen
- Program studi / jurusan
- Nama universitas
- Semester dan tahun

**Cara mengisi:** Tanya user data yang belum ada (nama, NIM, dosen, dll)
kalau tidak disediakan.

---

### 2. Tujuan Praktikum
Ditulis dalam poin-poin. Biasanya 2-4 poin.
Mulai dengan kata kerja: "Memahami...", "Mengimplementasikan...",
"Menganalisis...", "Membandingkan..."

**Contoh yang baik:**
```
Tujuan dari praktikum ini adalah:
1. Memahami konsep dan cara kerja algoritma bubble sort.
2. Mengimplementasikan algoritma bubble sort dalam bahasa C.
3. Menganalisis kompleksitas waktu algoritma berdasarkan hasil percobaan.
```

**Contoh yang buruk:**
```
Tujuan praktikum ini adalah untuk mempelajari dan memahami serta
mengimplementasikan algoritma bubble sort beserta cara kerjanya.
(→ Terlalu bertele-tele, gabungkan saja poinnya)
```

---

### 3. Dasar Teori
Penjelasan konsep yang relevan dengan topik praktikum.
Panjang ideal: 200-500 kata tergantung kompleksitas topik.

**Struktur dasar teori yang baik:**
1. Definisi singkat konsep utama
2. Cara kerja / mekanisme (bisa disertai contoh kecil)
3. Karakteristik penting (kelebihan, kekurangan, kapan digunakan)
4. Jika ada rumus atau notasi — jelaskan singkat

**Yang tidak perlu dimasukkan:**
- Sejarah panjang
- Variasi yang tidak dipakai di praktikum ini
- Kutipan definisi yang terlalu panjang dari buku

---

### 4. Alat dan Bahan
Daftar tools, software, dan hardware yang digunakan.

**Format standar:**
```
Hardware:
- Laptop/PC dengan spesifikasi minimal: [RAM], [OS]

Software:
- [Nama IDE / Text Editor] versi [X]
- [Bahasa pemrograman] versi [X]
- [Tools lain yang digunakan]
```

Jika user tidak menyebutkan spesifikasi → gunakan spesifikasi umum yang wajar
untuk praktikum tersebut, atau tanya user.

---

### 5. Langkah Kerja
Step-by-step apa yang dilakukan selama praktikum.
Ditulis dalam format bernomor, kalimat aktif, singkat.

**Format yang baik:**
```
1. Buka IDE dan buat project baru bernama "praktikum-sorting".
2. Buat file baru dengan nama "bubble_sort.c".
3. Tulis kode program sesuai modul (lihat Lampiran A).
4. Compile program menggunakan perintah: gcc bubble_sort.c -o bubble_sort
5. Jalankan program dengan input: [data]
6. Catat hasil output pada tabel pengamatan.
```

**Yang dihindari:**
- Langkah yang terlalu umum ("Buka komputer")
- Langkah yang menjelaskan teori (itu bagian Dasar Teori)

---

### 6. Hasil dan Pembahasan

**Bagian Hasil:**
- Tampilkan output program (dalam code block atau describe screenshot)
- Tabel data jika ada pengukuran/perbandingan
- Screenshot jika tersedia

**Bagian Pembahasan:**
Jelaskan apa yang terjadi dan kenapa. Kaitkan dengan dasar teori.
Jika ada perbedaan dengan ekspektasi → jelaskan kemungkinan penyebabnya.

**Contoh yang baik:**
```
Dari hasil percobaan, program berhasil mengurutkan 10 elemen data
dalam 45 perbandingan. Hasil ini sesuai dengan ekspektasi karena
bubble sort memiliki kompleksitas O(n²) — untuk n=10, jumlah
perbandingan maksimal adalah 45 (10×9/2).
```

**Contoh yang buruk:**
```
Hasil percobaan menunjukkan bahwa program telah berhasil dijalankan
dan menghasilkan output yang sesuai dengan yang diharapkan.
(→ Tidak ada analisis, hanya deskripsi)
```

---

### 7. Kesimpulan
Ringkasan dari apa yang dipelajari dan dibuktikan dalam praktikum.
Bukan pengulangan dasar teori.
Format: 3-5 poin singkat, atau 1 paragraf pendek.

**Contoh yang baik:**
```
Dari praktikum ini dapat disimpulkan:
1. Bubble sort bekerja dengan membandingkan elemen berdekatan secara berulang.
2. Algoritma ini memiliki kompleksitas O(n²) yang terbukti dari hasil percobaan.
3. Bubble sort cocok untuk dataset kecil, namun kurang efisien untuk data besar
   karena jumlah perbandingan meningkat kuadratik.
```

**Contoh yang buruk:**
```
Kesimpulan dari praktikum ini adalah bubble sort adalah algoritma
pengurutan yang bekerja dengan cara membandingkan dan menukar elemen
yang berdekatan. Bubble sort memiliki cara kerja yang...
(→ Mengulangi dasar teori, bukan menyimpulkan hasil praktikum)
```

---

### 8. Daftar Pustaka
Hanya jika diminta. Format yang umum dipakai:

**Buku:**
`Nama Penulis. (Tahun). Judul Buku. Penerbit.`

**Website:**
`Nama Penulis / Organisasi. (Tahun). Judul Halaman. Diakses dari [URL] pada [tanggal].`

Referensi yang aman digunakan:
- Buku teks algoritma (Cormen, Sedgewick, dll)
- Dokumentasi resmi bahasa pemrograman
- Geeksforgeeks, cppreference, w3schools (untuk referensi teknis)
