# Informatics Practicum

Skill untuk membantu mahasiswa Teknik Informatika mengerjakan laporan
praktikum — cepat, tepat, dan dengan bahasa yang manusiawi. Bisa dipakai di
Claude Code, Cursor, Codex, dan agent lain yang mendukung Agent Skills.

## Apa yang bisa dilakukan

| Fitur | Deskripsi |
|-------|-----------|
| **Format otomatis** | Ikuti template dari dosen, atau gunakan format standar |
| **Semua mata kuliah** | ASD, Basis Data, Jaringan, OS, OOP, Web, Mobile, AI/ML, dan lainnya |
| **Dasar teori** | Penjelasan singkat dan jelas — tidak terlalu akademis, tidak bertele-tele |
| **Kode program** | Lengkap dengan code block dan komentar yang relevan |
| **Analisis hasil** | Pembahasan yang nyambung ke teori, bukan hanya deskripsi |
| **Kesimpulan** | Poin-poin yang menyimpulkan hasil, bukan mengulang teori |

## Mata kuliah yang dicakup

- Algoritma dan Pemrograman / Dasar Pemrograman
- Algoritma dan Struktur Data (ASD)
- Basis Data / Database
- Jaringan Komputer
- Sistem Operasi
- Rekayasa Perangkat Lunak (RPL)
- Pemrograman Berorientasi Objek (OOP/PBO)
- Pemrograman Web
- Mobile Programming
- Kecerdasan Buatan / AI & Machine Learning
- Grafika Komputer / Multimedia
- Keamanan Informasi / Cybersecurity

## Instalasi

Cara tercepat, lewat [skills.sh](https://www.skills.sh/):

```bash
npx skills add HaqiKuy470/Informatic-Practikum-Skills
```

Atau manual:

```bash
git clone https://github.com/HaqiKuy470/Informatic-Practikum-Skills
cp -r Informatic-Practikum-Skills/. your-project/.claude/skills/informatics-practicum/
```

## Cara pakai

```
"Tolong buatkan laporan praktikum ASD tentang bubble sort"
"Bantu kerjain laporan ini" [paste soal praktikum]
"Buatkan dasar teori untuk praktikum linked list"
"Lengkapin bagian pembahasan laporan ini" [paste laporan]
"Ada template dari dosen, tolong ikuti formatnya" [upload template + soal]
```

## Setup per sesi

Skill akan tanya:
1. **Template** — ada dari dosen? Upload/paste kalau ada
2. **Mata kuliah dan topik** — misal: "ASD — Binary Search"
3. **Soal/modul** — upload atau paste
4. **Status pengerjaan** — mulai dari nol / melengkapi / memperbaiki

## Gaya bahasa

**Formal tapi manusiawi.** Seperti mahasiswa yang paham materi dan
bisa menjelaskan dengan jelas — bukan buku teks, bukan bahasa gaul.
To the point. Tidak ada padding atau kalimat berulang.

## Struktur file

```
SKILL.md                           ← entry point
references/
├── format-laporan.md              ← struktur dan panduan tiap bagian laporan
├── matkul-guide.md                ← panduan per mata kuliah
└── writing-style.md               ← standar bahasa dan penulisan
```

## Catatan penggunaan

Skill ini membantu menyusun draf laporan. Pastikan kamu memahami isinya,
melengkapi data hasil percobaan sendiri, dan mengikuti aturan akademik
kampusmu.

## Lisensi

[MIT](LICENSE) © 2026 LokaShaka
