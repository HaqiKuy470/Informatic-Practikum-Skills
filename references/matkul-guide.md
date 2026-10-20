# Panduan Per Mata Kuliah

Referensi cepat untuk mengidentifikasi topik, konsep kunci, dan
pendekatan penulisan per mata kuliah informatika.

---

## Algoritma dan Pemrograman / Dasar Pemrograman

**Topik umum:** variabel, tipe data, kondisional, perulangan, fungsi,
rekursi, array, pointer

**Bahasa yang biasa dipakai:** C, Python, Pascal

**Fokus laporan:**
- Dasar teori: jelaskan konsep yang dipakai (misal: apa itu rekursi,
  bagaimana stack call bekerja)
- Langkah kerja: kode program + cara compile/run
- Hasil: output program dengan input yang diberikan
- Pembahasan: apakah output sesuai ekspektasi, kenapa

**Kode selalu dalam code block dengan bahasa yang benar:**
````
```c
#include <stdio.h>
int main() { ... }
```
````

---

## Algoritma dan Struktur Data (ASD)

**Topik umum:** array, linked list, stack, queue, tree, graph,
searching (linear, binary), sorting (bubble, selection, insertion,
merge, quick, heap), hashing, dynamic programming

**Fokus laporan:**
- Dasar teori: konsep struktur data + kompleksitas waktu (Big-O) yang relevan
- Langkah kerja: implementasi + langkah percobaan
- Hasil: output + tabel perbandingan jika ada multiple run
- Pembahasan: analisis kompleksitas dari hasil nyata vs teori

**Penting:** Selalu sebutkan kompleksitas O() di dasar teori dan
kaitkan dengan hasil di pembahasan.

---

## Basis Data / Database

**Topik umum:** DDL (CREATE, ALTER, DROP), DML (SELECT, INSERT, UPDATE, DELETE),
JOIN (INNER, LEFT, RIGHT, FULL), GROUP BY, HAVING, subquery, stored procedure,
trigger, normalisasi, ERD, relasi tabel

**DBMS yang biasa dipakai:** MySQL, PostgreSQL, Oracle, SQLite

**Fokus laporan:**
- Dasar teori: jelaskan perintah/konsep yang dipraktikkan
- Langkah kerja: query SQL yang dijalankan (dalam code block SQL)
- Hasil: screenshot tabel atau describe output query
- Pembahasan: apakah hasil query sesuai, kenapa menggunakan pendekatan ini

**Format kode SQL:**
````
```sql
SELECT nama, nilai
FROM mahasiswa
WHERE nilai >= 70
ORDER BY nilai DESC;
```
````

---

## Jaringan Komputer

**Topik umum:** model OSI, TCP/IP, IP addressing, subnetting, VLSM,
routing (static, dynamic — RIP, OSPF, EIGRP), switching, VLAN,
NAT, DHCP, DNS, HTTP, FTP, protokol transport (TCP vs UDP),
packet tracer, Wireshark

**Tools yang biasa dipakai:** Cisco Packet Tracer, GNS3, Wireshark

**Fokus laporan:**
- Dasar teori: konsep jaringan yang relevan (misal: cara kerja subnetting,
  perbedaan static vs dynamic routing)
- Langkah kerja: konfigurasi yang dilakukan (perintah CLI atau langkah di Packet Tracer)
- Hasil: topologi jaringan, hasil ping/traceroute, tabel routing
- Pembahasan: apakah komunikasi berhasil, kenapa, apa yang terjadi jika salah

**Format konfigurasi Cisco:**
````
```
Router(config)# ip route 192.168.2.0 255.255.255.0 192.168.1.2
```
````

---

## Sistem Operasi

**Topik umum:** proses dan thread, scheduling (FCFS, SJF, Round Robin,
Priority), sinkronisasi (mutex, semaphore, deadlock), manajemen memori
(paging, segmentasi, virtual memory), file system, shell scripting,
perintah Linux/Unix

**Fokus laporan:**
- Dasar teori: konsep OS yang dipraktikkan + cara kerjanya
- Langkah kerja: perintah shell / kode program yang dijalankan
- Hasil: output perintah atau program
- Pembahasan: interpretasi hasil, kaitkan dengan konsep scheduling/memory/dll

**Format shell command:**
````
```bash
ps aux | grep firefox
kill -9 1234
```
````

---

## Rekayasa Perangkat Lunak (RPL)

**Topik umum:** SDLC, model pengembangan (waterfall, agile, spiral),
UML (use case, class diagram, sequence diagram, activity diagram),
requirement analysis, testing (unit test, integration test),
design pattern, Git/version control

**Fokus laporan:**
- Dasar teori: metodologi atau konsep yang diterapkan
- Langkah kerja: proses yang dilakukan (analisis kebutuhan, pembuatan diagram, dll)
- Hasil: diagram UML, dokumen requirement, atau kode yang dibuat
- Pembahasan: keputusan desain yang diambil dan alasannya

---

## Pemrograman Berorientasi Objek (PBO / OOP)

**Topik umum:** class, object, encapsulation, inheritance, polymorphism,
abstraction, interface, constructor, destructor, overriding, overloading

**Bahasa yang biasa dipakai:** Java, C++, Python, C#

**Fokus laporan:**
- Dasar teori: prinsip OOP yang diterapkan (tidak perlu jelaskan semua 4 pilar
  kalau hanya 1-2 yang relevan)
- Langkah kerja: implementasi class dan hubungan antar class
- Hasil: output program, class diagram jika ada
- Pembahasan: bagaimana prinsip OOP diterapkan dalam kode

---

## Pemrograman Web

**Topik umum:** HTML, CSS, JavaScript, PHP, framework (Laravel, React,
Vue, Express), REST API, AJAX, JSON, session/cookie, autentikasi,
CRUD, deployment

**Fokus laporan:**
- Dasar teori: teknologi/konsep web yang dipakai
- Langkah kerja: setup environment + kode yang dibuat
- Hasil: screenshot tampilan web atau output API
- Pembahasan: cara kerja fitur yang dibuat, kendala yang ditemui

**Format kode web:**
````
```html
<!DOCTYPE html>
<html>...
```

```php
<?php
$data = $_POST['nama'];
```
````

---

## Mobile Programming / Pemrograman Mobile

**Topik umum:** Android (Java/Kotlin), iOS (Swift), React Native,
Flutter, activity lifecycle, intent, layout XML, RecyclerView,
SQLite mobile, API call, permission

**Fokus laporan:**
- Dasar teori: platform dan konsep yang dipakai (lifecycle, komponen utama)
- Langkah kerja: setup project + implementasi fitur
- Hasil: screenshot tampilan aplikasi di emulator/device
- Pembahasan: cara kerja fitur, perbedaan dengan web

---

## Kecerdasan Buatan / AI & Machine Learning

**Topik umum:** search algorithm (BFS, DFS, A*), knowledge representation,
logika fuzzy, algoritma genetika, neural network, regresi,
klasifikasi (Naive Bayes, KNN, Decision Tree, SVM), clustering (K-Means),
Python (NumPy, Pandas, Scikit-learn, TensorFlow)

**Fokus laporan:**
- Dasar teori: algoritma / model yang dipakai — cara kerja singkat, bukan
  derivasi matematis panjang kecuali diminta
- Langkah kerja: dataset yang dipakai + preprocessing + training + evaluasi
- Hasil: accuracy, confusion matrix, grafik training jika ada
- Pembahasan: interpretasi metrik, mengapa model perform seperti ini

---

## Grafika Komputer / Multimedia

**Topik umum:** transformasi 2D/3D (translasi, rotasi, scaling),
proyeksi, rasterisasi, OpenGL, rendering, warna (RGB, CMYK, HSV),
pengolahan citra (filter, histogram, deteksi tepi), kompresi

**Fokus laporan:**
- Dasar teori: transformasi/teknik yang dipakai beserta rumus matriksnya
- Langkah kerja: implementasi kode + langkah percobaan
- Hasil: output gambar atau render sebelum/sesudah
- Pembahasan: analisis hasil transformasi/filter

---

## Keamanan Informasi / Cybersecurity

**Topik umum:** kriptografi (simetris — AES, DES; asimetris — RSA),
hashing (MD5, SHA), digital signature, SSL/TLS, enkripsi file,
steganografi, keamanan jaringan, vulnerability assessment

**Fokus laporan:**
- Dasar teori: algoritma keamanan yang dipakai — prinsip kerja, bukan
  implementasi matematis detail kecuali diminta
- Langkah kerja: proses enkripsi/dekripsi atau konfigurasi keamanan
- Hasil: output ciphertext, hash, atau hasil scan
- Pembahasan: keamanan yang diberikan, kelemahan jika ada

---

## Cara identifikasi topik dari soal

Kalau soal/modul tidak menyebutkan mata kuliah dengan jelas,
identifikasi dari kata kunci:

```
Kata kunci → Kemungkinan mata kuliah
─────────────────────────────────────
array, sorting, linked list, tree → ASD
SELECT, JOIN, CREATE TABLE → Basis Data
subnet, routing, VLAN, ping → Jaringan
class, object, inheritance → OOP / PBO
process, thread, scheduling → Sistem Operasi
use case, UML, SDLC → RPL
HTML, CSS, PHP, JavaScript → Pemrograman Web
Android, activity, layout → Mobile Programming
neural network, accuracy, dataset → AI/ML
enkripsi, hash, kriptografi → Keamanan Informasi
```
