---
name: informatics-practicum
description: >
  Skill untuk mengerjakan laporan praktikum mahasiswa Teknik Informatika.
  Aktifkan SELALU saat diminta membuat, melengkapi, atau memperbaiki laporan
  praktikum; menulis dasar teori; menjelaskan langkah kerja; menganalisis
  hasil percobaan; membuat kesimpulan; atau mengerjakan tugas yang berkaitan
  dengan praktikum informatika. Juga aktif saat: "buat laporan", "kerjain
  laporan", "tolong laporan praktikum", "dasar teori", "analisis hasil",
  "kesimpulan praktikum", "bantu tugas praktikum", bahkan jika tidak
  disebutkan secara eksplisit.
---

# Informatics Practicum — Laporan Praktikum

Skill untuk membantu mahasiswa Teknik Informatika mengerjakan laporan
praktikum dengan cepat, tepat, dan manusiawi.

---

## Step 0 — Setup (TANYA DULU setiap sesi baru)

Sebelum mengerjakan apapun, tanya semua sekaligus dalam satu pesan:

> **Sebelum mulai, beberapa pertanyaan singkat:**
>
> **1. Ada template laporan dari dosen/kampus?**
> - Kalau ada → upload atau paste templatenya, saya ikuti formatnya
> - Kalau tidak ada → saya pakai format standar umum
>
> **2. Mata kuliah dan topik praktikumnya apa?**
> Contoh: "Algoritma dan Struktur Data — Sorting", "Basis Data — JOIN query",
> "Jaringan Komputer — Subnetting", dll.
>
> **3. Ada soal atau modul praktikumnya?**
> - Kalau ada → upload atau paste, saya baca dulu sebelum mengerjakan
> - Kalau tidak ada → ceritakan apa yang harus dikerjakan
>
> **4. Apa yang sudah ada / belum ada?**
> - Mulai dari nol (semua bagian perlu dibuat)
> - Sudah ada sebagian (sebutkan bagian mana yang perlu dilengkapi)
> - Minta perbaikan (paste bagian yang perlu diperbaiki)

---

## Step 1 — Baca semua material

Setelah user menjawab, baca semua yang diberikan:
- Template format (jika ada)
- Soal / modul praktikum
- Kode program (jika ada)
- Hasil percobaan / screenshot (jika ada)

Identifikasi:
- Mata kuliah dan topik spesifik
- Bagian laporan yang perlu dikerjakan
- Terminologi dan konsep kunci yang perlu dijelaskan
- Output / hasil yang diharapkan dari praktikum ini

---

## Step 2 — Kerjakan laporan

→ Baca `references/format-laporan.md` untuk struktur default jika tidak ada template
→ Baca `references/matkul-guide.md` untuk panduan per mata kuliah
→ Baca `references/writing-style.md` untuk standar penulisan

Kerjakan bagian per bagian sesuai urutan template atau format standar.
Tanya jika ada informasi yang kurang sebelum menulis bagian yang butuh data spesifik
(misal: hasil percobaan, spesifikasi alat, screenshot output).

---

## Aturan penulisan — berlaku di semua bagian

### Gaya bahasa yang benar
Formal tapi manusiawi. Seperti mahasiswa yang paham materi dan bisa menjelaskan
dengan jelas — bukan seperti buku teks atau paper akademis.

```
# Terlalu kaku / akademis (hindari)
"Algoritma bubble sort merupakan suatu metode pengurutan yang bekerja
dengan cara melakukan komparasi secara berulang-ulang terhadap elemen-elemen
yang bersebelahan di dalam suatu struktur data larik."

# Terlalu santai (hindari)
"Jadi bubble sort itu basicnya bandingin dua angka yang berdekatan terus
kalau kebalik dituker deh."

# Tepat sasaran (gunakan ini)
"Bubble sort adalah algoritma pengurutan yang bekerja dengan membandingkan
dua elemen yang berdekatan, lalu menukarnya jika urutannya salah. Proses
ini diulangi sampai seluruh data terurut."
```

### Panjang penjelasan
- Dasar teori: cukup sampai pembaca paham konsepnya — tidak perlu jelaskan
  sejarah penemuan atau variasi yang tidak relevan dengan praktikum
- Langkah kerja: singkat dan jelas — 1 langkah = 1 kalimat atau 1 blok pendek
- Analisis hasil: fokus pada apa yang terjadi dan kenapa — bukan deskripsi ulang soal
- Kesimpulan: 3-5 poin yang langsung ke inti, tidak bertele-tele

### Yang TIDAK BOLEH dilakukan
- Kalimat berulang atau padding untuk memanjangkan laporan
- Definisi yang terlalu panjang untuk konsep sederhana
- Bahasa gaul atau informal
- Kalimat pasif yang berlebihan ("dapat diketahui bahwa", "dapat dilihat bahwa")
- Kesimpulan yang hanya mengulang dasar teori tanpa mengaitkan dengan hasil praktikum
- Mengada-ada hasil percobaan jika data tidak diberikan — tanya dulu ke user

---

## Output format

Tulis laporan langsung dalam format Markdown yang rapi.
Gunakan heading, subheading, dan code block sesuai kebutuhan.
Kode program selalu dalam code block dengan bahasa yang tepat.

Setelah selesai, tambahkan:
```
---
📋 Catatan:
- Bagian yang perlu data dari kamu: [sebutkan jika ada]
- Bagian yang perlu screenshot: [sebutkan jika ada]
- Bagian yang perlu disesuaikan: [sebutkan jika ada]
```
