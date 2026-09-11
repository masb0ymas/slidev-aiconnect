# AI Builder Sprint — Dari Ide ke Prototype AI Tanpa Coding

Deck presentasi (Slidev) untuk sesi materi 90 menit sebelum sesi praktek.
Audiens: mahasiswa / pemula yang ingin belajar membangun asisten AI tanpa menulis kode.

## Menjalankan

```bash
npm install     # atau: bun install
npm run dev     # buka http://localhost:3030
```

## Perintah lain

```bash
npm run build      # build statis ke dist/ (untuk Netlify/Vercel)
npm run export     # ekspor PDF — perlu `playwright-chromium`
```

Untuk ekspor PDF, pasang dulu Playwright:

```bash
npm i -D playwright-chromium
```

## Cara presentasi

| Tombol | Fungsi |
|---|---|
| `p` | Mode presenter (catatan + timer) |
| `o` | Tampilan overview semua slide |
| `d` | Ganti mode gelap/terang |
| `f` | Layar penuh |
| `?` | Daftar semua pintasan |

Deck ini dikunci ke **mode terang** (`colorSchema: light`) supaya tampilan tetap
sama walaupun laptop presenter memakai mode gelap. Jangan hapus setelan itu.

Setiap slide demo (Demo A–D) punya **catatan presenter berupa skrip**: langkah
yang diklik, prompt yang diketik, dan poin yang harus diucapkan. Tekan `p` untuk
membacanya.

## Struktur deck (35 slide)

| Slide | Bagian | Durasi |
|---|---|---|
| 1–3 | Pembuka: hook + peta sesi | 6 menit |
| 4–11 | Fundamental: enam cara berpikir dasar | 13 menit |
| 12–17 | Mindset: kenapa sekarang, peran baru, skill stack + slide gambar | 10 menit |
| 18–23 | Anatomi AI Builder: peta tool, cara kerja, batas aman | 11 menit |
| 24–30 | Framework Sprint 5 langkah | 16 menit |
| 31–37 | Live demo (4 tahap + rekap) | 21 menit |
| 38–44 | Penutup: roadmap, etika, checklist, cheat sheet | 11 menit |

Total 88 menit, menyisakan 2 menit untuk jeda dan tanya jawab.

### Bagian Fundamental (4–11)

Enam cara berpikir yang menjadi fondasi sebelum menyentuh tool apa pun.
Semua contohnya memakai kasus warung/POS yang sama dengan demo, supaya
peserta melihat benang merahnya.

| Slide | Topik |
|---|---|
| 5 | Definisi Masalah — gejala vs akar masalah |
| 6 | Pemodelan Data — tentukan data sebelum tampilan |
| 7 | Berpikir Sistem — dampak perubahan antar komponen |
| 8 | Penerjemahan Niat Pengguna — kata sifat jadi angka |
| 9 | Penalaran Trade-off — konsekuensi tiap pilihan |
| 10 | Dekomposisi Masalah — pecah jadi langkah kecil |
| 11 | Penutup bagian: kenapa ini lebih dulu |

Kalau waktu mepet, percepat bagian ini: bahas Definisi Masalah dan
Dekomposisi, lalu sebut empat lainnya sekilas.

## Struktur berkas

```
slides.md            # seluruh isi deck + catatan presenter
styles/index.css     # design system (palet rose, kartu, callout, tabel)
components/          # Card.vue, PromptBox.vue, StepFlow.vue
global-bottom.vue    # footer nomor slide
public/              # aset gambar (mindset-visual.jpg)
```

## Aset gambar

Gambar lokal diletakkan di `public/` dan dirujuk dengan garis miring di depan
(`/mindset-visual.jpg`) — bukan path relatif. Folder ini otomatis tersalin ke
`dist/` saat build.

Slide gambar ada di nomor 17, setelah bagian Mindset, memakai `layout: image`
dengan `backgroundSize: contain` supaya gambar tidak terpotong. Footer nomor
slide sengaja disembunyikan di sana (lihat `global-bottom.vue`).

Untuk mengganti gambar: timpa `public/mindset-visual.jpg`, atau ubah
`image:` pada slide 17 di `slides.md`.

## Palet warna

Monokrom rose, diambil dari
[Coolors](https://coolors.co/palette/590d22-800f2f-a4133c-c9184a-ff4d6d-ff758f-ff8fa3-ffb3c1-ffccd5-fff0f3).

Nuansa gelap (`#590d22`, `#800f2f`, `#a4133c`) dipakai untuk teks; nuansa terang
(`#ff4d6d` ke atas) hanya untuk dekorasi seperti gradient dan latar kartu. Warna
terang tidak lolos ambang kontras WCAG untuk teks kecil.

Karena paletnya monokrom, status **lulus / peringatan / gagal** dibedakan lewat
intensitas isian badge, ketebalan garis, dan ikon — bukan lewat warna saja.

## Yang perlu diisi sebelum tampil

- Nama presenter dan afiliasi (slide 1)
- Nama dan tanggal event (slide 1)
- Tautan yang ingin dicantumkan (slide 35)
