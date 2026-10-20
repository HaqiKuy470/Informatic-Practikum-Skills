# Panduan Gaya Penulisan

Standar bahasa dan penulisan untuk semua bagian laporan praktikum.

---

## Prinsip utama

**Formal tapi manusiawi.**
Tulis seperti mahasiswa yang paham materi dan bisa menjelaskan dengan jelas —
bukan seperti buku teks, bukan seperti chatting.

**To the point.**
Satu kalimat = satu ide. Tidak perlu memperpanjang kalau isinya sudah cukup.

**Tidak ada padding.**
Kalimat yang tidak menambah informasi = dihapus.

---

## Panduan kalimat per kalimat

### Definisi dan penjelasan konsep

```
# Terlalu kaku
"Linked list merupakan suatu struktur data linear yang terdiri dari
sekumpulan node yang saling terhubung satu sama lain melalui pointer
yang menunjuk ke node berikutnya dalam urutan."

# Tepat
"Linked list adalah struktur data yang terdiri dari node-node yang
saling terhubung lewat pointer. Setiap node menyimpan data dan alamat
node berikutnya."
```

### Penjelasan cara kerja

```
# Terlalu panjang
"Algoritma binary search bekerja dengan cara membagi array yang sudah
terurut menjadi dua bagian yang sama besar, kemudian membandingkan
nilai tengah dengan nilai yang dicari. Apabila nilai yang dicari lebih
kecil dari nilai tengah, maka pencarian dilanjutkan pada bagian kiri..."

# Tepat
"Binary search bekerja dengan membagi array terurut menjadi dua bagian.
Jika nilai yang dicari lebih kecil dari elemen tengah, pencarian lanjut
ke bagian kiri; jika lebih besar, ke bagian kanan. Proses ini diulang
sampai nilai ditemukan atau tidak ada lagi elemen yang bisa dibagi."
```

### Analisis hasil

```
# Hanya deskripsi (buruk)
"Hasil percobaan menunjukkan bahwa program telah berhasil berjalan
dan menghasilkan output yang diharapkan."

# Ada analisis (baik)
"Program berhasil mengurutkan 100 data dalam 0.003 detik. Waktu ini
sesuai dengan kompleksitas O(n log n) dari merge sort — jauh lebih
cepat dibanding bubble sort yang membutuhkan 0.047 detik untuk data
yang sama."
```

### Kesimpulan

```
# Mengulang dasar teori (buruk)
"Dari praktikum ini dapat disimpulkan bahwa binary search adalah
algoritma pencarian yang bekerja pada array terurut dengan membagi..."

# Menyimpulkan hasil (baik)
"Dari praktikum ini dapat disimpulkan bahwa:
1. Binary search terbukti lebih efisien dari linear search untuk data
   besar — pada 10.000 data, binary search hanya butuh 14 iterasi.
2. Kekurangan binary search adalah data harus sudah terurut terlebih dahulu.
3. Untuk dataset yang sering berubah, biaya sorting mungkin tidak sebanding
   dengan keuntungan kecepatan pencarian."
```

---

## Kata dan frasa yang dihindari

| Hindari | Ganti dengan |
|---------|-------------|
| "dapat diketahui bahwa" | langsung ke isinya |
| "berdasarkan hasil percobaan di atas" | "dari hasil percobaan" |
| "dengan demikian dapat disimpulkan" | "kesimpulannya," |
| "adapun" (di awal kalimat) | hilangkan atau ganti langsung |
| "di mana" sebagai penghubung kalimat | pisah jadi dua kalimat |
| "sangat penting sekali" | "sangat penting" atau "penting" |
| "merupakan salah satu" (jika hanya itu) | "adalah" |
| "pada dasarnya" | langsung ke penjelasannya |
| "sebagaimana telah disebutkan" | tidak perlu |
| Definisi yang copy-paste dari Wikipedia | tulis ulang dengan bahasa sendiri |

---

## Format kode program

Selalu gunakan code block dengan label bahasa:

````
```c
// Kode C
```

```python
# Kode Python
```

```java
// Kode Java
```

```sql
-- Query SQL
```

```bash
# Perintah terminal
```

```html
<!-- Kode HTML -->
```
````

Komentar dalam kode: gunakan Bahasa Indonesia yang singkat.

---

## Tabel data

Untuk hasil percobaan yang melibatkan pengukuran / perbandingan,
gunakan tabel Markdown:

```markdown
| Jumlah Data | Waktu (ms) | Iterasi |
|-------------|-----------|---------|
| 10          | 0.001     | 45      |
| 100         | 0.089     | 4950    |
| 1000        | 8.7       | 499500  |
```

---

## Penanganan data yang tidak tersedia

Jika user tidak memberikan data hasil percobaan:

**Jangan mengada-ada hasil spesifik.**

Yang boleh dilakukan:
1. Tulis template kosong yang bisa diisi user:
   ```
   | Input | Output | Waktu Eksekusi |
   |-------|--------|---------------|
   | [data percobaan 1] | [output 1] | [waktu 1] |
   ```

2. Beri tahu di catatan bawah:
   ```
   📋 Catatan: Bagian tabel hasil percobaan perlu diisi
   berdasarkan output yang kamu dapat saat menjalankan program.
   ```

3. Untuk pembahasan: tulis template dengan placeholder yang jelas:
   ```
   Program berhasil [describe hasil] dalam [X] ms.
   Hasil ini [sesuai/tidak sesuai] dengan ekspektasi karena...
   ```

---

## Penulisan istilah teknis

Istilah teknis dalam Bahasa Inggris yang sudah umum **tidak perlu diterjemahkan**
jika terjemahannya tidak lazim dipakai:

```
Boleh pakai langsung:
- sorting, searching, hashing, parsing
- array, linked list, tree, graph, stack, queue
- query, database, server, client, routing
- class, object, method, instance
- input, output, debug, compile, runtime

Terjemahkan jika ada padanan lazim:
- file → berkas (tapi "file" juga boleh)
- user → pengguna (lebih formal)
- data → data (sama)
```

Untuk singkatan: tulis lengkap dulu, baru singkatan dalam kurung.
Contoh: "Local Area Network (LAN)"
Setelahnya cukup tulis "LAN".

---

## Perujukan ke kode / lampiran

```
# Merujuk ke kode dalam laporan
"Implementasi lengkap dapat dilihat pada Kode 1 di bawah."

# Merujuk ke screenshot
"Hasil output program ditampilkan pada Gambar 1."

# Merujuk ke lampiran
"Kode program lengkap terlampir pada Lampiran A."
```
