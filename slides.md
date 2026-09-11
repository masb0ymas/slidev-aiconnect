---
theme: default
title: 'AI Builder Sprint: Dari Ide ke Prototype AI Tanpa Coding'
info: |
  ## AI Builder Sprint
  Dari Ide ke Prototype AI Tanpa Coding

  Sesi materi 90 menit untuk pemula — sebelum masuk sesi praktek.
author: AI Connect
keywords: ai, prototype, prompt, no-code, mahasiswa
# Deck ini dirancang untuk proyektor: kunci ke mode terang agar tampilan tidak
# berubah mengikuti pengaturan gelap/terang sistem operasi presenter.
colorSchema: light
fonts:
  sans: Inter
  mono: JetBrains Mono
  provider: google
drawings:
  persist: false
comark: true
duration: 90min
layout: cover
class: abs-cover
transition: slide-left
---

<div class="abs-eyebrow">Sesi Materi · 90 Menit</div>

# AI Builder Sprint

<div class="abs-cover-rule" />

<p class="abs-lead">
Dari <strong>Ide</strong> ke <strong>Prototype AI</strong> — tanpa menulis kode.
</p>

<div class="mt-12 abs-muted abs-small">
Disusun untuk sesi praktek <strong>AI Connect</strong>
</div>

<!--
CATATAN PEMBUKA (2 menit)

Sapa peserta, lalu langsung nyatakan janji sesi ini:
"Hari ini kita tidak akan belajar coding. Kita akan belajar menerjemahkan ide
menjadi produk AI yang benar-benar jalan — dalam satu sesi."

Sebutkan bahwa 90 menit ini adalah bekal sebelum sesi praktek, dan di akhir
peserta akan punya satu asisten AI buatan sendiri.

Isi nama presenter dan tanggal event di sini sebelum tampil.
-->

---
layout: default
---

# Apa yang bisa kamu bangun dalam satu sesi?

<div class="grid grid-cols-3 gap-4 mt-8 abs-card-row">

<Card icon="i-carbon-document" title="Asisten Belajar">
<p>Menjawab pertanyaan dari materi kuliahmu sendiri, lengkap dengan rujukan halaman.</p>
</Card>

<Card icon="i-carbon-edit" title="Reviewer Tulisan">
<p>Memberi catatan struktur, argumen, dan tata bahasa pada draft skripsi atau esai.</p>
</Card>

<Card icon="i-carbon-flow" title="Otomasi Kecil">
<p>Merapikan data pendaftaran, menyusun ringkasan, atau membalas pertanyaan berulang.</p>
</Card>

</div>

<div class="mt-10 abs-callout" v-click>

**Pertanyaan pembuka:** sebutkan satu tugas yang paling sering bikin kamu buang waktu. Simpan jawabannya — itu calon ide praktekmu nanti.

</div>

<!--
Catatan: 3 menit. Jangan langsung menjawab; biarkan 2-3 peserta menyebut tugas
masing-masing. Tujuannya memancing contoh nyata supaya sesi terasa relevan.
Tegaskan: ketiga contoh tadi dibuat orang yang bukan programmer.
-->

---
layout: default
---

# Peta sesi hari ini

<div class="grid grid-cols-2 gap-x-10 gap-y-1 mt-6">

<div>

### <span class="abs-accent">Bagian 1</span> — Mindset
Cara berpikir yang berubah, dan peran baru yang kamu pegang.

### <span class="abs-accent">Bagian 2</span> — Anatomi AI Builder
Cara AI bekerja, jenis-jenis tool, dan kenapa AI sering ngawur.

### <span class="abs-accent">Bagian 3</span> — Framework Sprint
Lima langkah baku: Ide → Spesifikasi → Instruksi → Bangun → Uji.

</div>

<div>

### <span class="abs-accent">Bagian 4</span> — Live Demo
Saya bangun satu asisten AI dari nol di depan kalian.

### <span class="abs-accent">Bagian 5</span> — Persiapan Praktek
Checklist, cheat sheet prompt, dan daftar ide.

<div class="abs-callout mt-6">

**Aturan main:** tidak ada pertanyaan yang terlalu dasar. Semua ide boleh. Kita di sini untuk membuat, bukan menghafal.

</div>

</div>

</div>

<!--
Catatan: 1 menit. Bacakan cepat, jangan berhenti di tiap poin. Tekankan bahwa
sesi praktek adalah bagian utamanya, dan materi ini hanya menyiapkan bekal.
-->

---
layout: section
class: abs-dark
---

<div class="abs-eyebrow">Bagian 1 dari 5</div>

# Mindset

Semua orang kini bisa membangun. Yang membedakan adalah cara berpikir.

<!--
Pembatas bagian. 10 menit untuk bagian ini.
-->

---
layout: default
---

# Pergeseran besar

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## Sebelumnya

<div class="abs-prompt" v-click>
<div class="abs-prompt-label is-bad">Cara lama</div>
<div class="abs-prompt-body">
Kamu harus menguasai <strong>sintaks</strong>: bahasa pemrograman, framework, konfigurasi server, dan database — bertahun-tahun belajar sebelum bisa membuat sesuatu yang dipakai orang.
</div>
</div>

</div>

<div>

## Sekarang

<div class="abs-prompt" v-click>
<div class="abs-prompt-label is-good">Cara baru</div>
<div class="abs-prompt-body">
Kamu harus menguasai <strong>kejelasan maksud</strong>: mendefinisikan masalah, menggambarkan hasil yang diinginkan, dan menilai apakah hasilnya sudah benar.
</div>
</div>

</div>

</div>

<div class="abs-callout mt-10" v-click>

**Yang tidak berubah:** kamus tetap perlu tahu masalah apa yang layak diselesaikan. AI mempercepat eksekusi, bukan menggantikan penilaian.

</div>

<!--
Catatan: 3 menit. Ini slide inti dari Bagian 1.

Tekankan: hambatan utama bukan lagi "bisa coding atau tidak", tapi
"cukup jelas atau tidak ide kamu". Banyak orang gagal bukan karena AI-nya lemah,
tapi karena instruksinya kabur.

Analogi yang berguna: AI seperti kontraktor yang sangat cepat dan sangat
percaya diri. Kalau gambar bangunannya kabur, dia tetap akan membangun —
dan hasilnya bukan yang kamu mau.
-->

---
layout: default
---

# Tiga peran baru kamu

<div class="grid grid-cols-3 gap-4 mt-8 abs-card-row">

<Card num="1" title="Ide Owner">
<p>Kamu pemilik masalah dan pemilik keputusan. AI tidak tahu apa yang penting bagimu — hanya kamu yang tahu.</p>
<ul>
<li>Menentukan masalah</li>
<li>Memilih prioritas</li>
<li>Menjaga visi</li>
</ul>
</Card>

<Card num="2" title="AI Orchestrator">
<p>Kamu mengarahkan, bukan mengeksekusi. Tugasmu mengubah niat menjadi instruksi yang bisa dikerjakan.</p>
<ul>
<li>Menulis instruksi</li>
<li>Menyusun konteks</li>
<li>Memecah pekerjaan</li>
</ul>
</Card>

<Card num="3" title="Quality Checker">
<p>Kamu yang menilai hasil. AI bisa sangat meyakinkan sekaligus sangat salah — di sinilah kamu dibutuhkan.</p>
<ul>
<li>Menguji output</li>
<li>Menemukan cacat</li>
<li>Memutuskan layak/tidak</li>
</ul>
</Card>

</div>

<div class="abs-callout mt-8" v-click>

Peran <strong>Quality Checker</strong> paling sering dilewatkan pemula — dan paling sering jadi penyebab prototype yang terlihat bagus tapi salah isi.

</div>

<!--
Catatan: 3 menit. Tanya peserta: "Dari tiga peran ini, mana yang paling kamu
andalkan sekarang?" Biasanya kebanyakan menjawab Orchestrator.

Pesan kunci: peran penilaian tidak bisa didelegasikan ke AI. Kalau kamu tidak
bisa menilai jawaban benar atau salah, kamu tidak bisa memperbaikinya.
-->

---
layout: default
---

# Yang realistis — dan yang belum

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

<h3 class="flex items-center gap-2"><span class="abs-icon"><span class="i-carbon-checkmark" /></span> Sudah bisa sekarang</h3>

<ul class="abs-check is-done mt-4">
<li>Asisten tanya-jawab dari dokumenmu sendiri</li>
<li>Alat bantu tulis, ringkas, dan terjemah</li>
<li>Prototype antarmuka yang bisa diklik</li>
<li>Otomasi alur kerja sederhana</li>
<li>Alat bantu analisis data skala kecil</li>
</ul>

</div>

<div>

<h3 class="flex items-center gap-2"><span class="abs-icon" style="color:var(--abs-danger)"><span class="i-carbon-warning-alt" /></span> Belum realistis</h3>

<ul class="abs-check is-cross mt-4">
<li>Sistem yang menangani data sensitif tanpa pengawasan</li>
<li>Keputusan penting tanpa verifikasi manusia</li>
<li>Produk siap pakai jutaan orang tanpa pengujian serius</li>
<li>Pengganti penuh keahlian profesional</li>
<li>Jaminan bahwa jawaban AI selalu benar</li>
</ul>

</div>

</div>

<div class="abs-callout-warn abs-callout mt-8" v-click>

Untuk sesi praktek kita, targetnya ada di kolom kiri: <strong>satu asisten AI yang benar-benar berguna untuk satu tugas spesifik.</strong>

</div>

<!--
Catatan: 3 menit. Slide ini mencegah dua kesalahan umum:

1. Terlalu ambisius — ingin langsung membangun "aplikasi besar" lalu gagal
   dan kecewa.
2. Terlalu pesimis — menganggap AI hanya mainan.

Tekankan: kita sengaja memilih target kecil yang pasti selesai dalam satu sesi.
-->

---
layout: default
class: abs-dense
---

# Skill stack yang baru

<div class="mt-6">

<table>
<thead>
<tr><th style="width:28%">Keterampilan</th><th style="width:36%">Bentuknya seperti apa</th><th>Latihannya</th></tr>
</thead>
<tbody>
<tr v-click>
<td><strong>Kejelasan masalah</strong></td>
<td>Menyatakan satu masalah dalam satu kalimat tanpa kata "dan"</td>
<td>Tulis 10 masalah, pilih 1 yang paling sempit</td>
</tr>
<tr v-click>
<td><strong>Penulisan instruksi</strong></td>
<td>Memberi peran, tujuan, batasan, dan format keluaran</td>
<td>Ubah satu permintaan kabur jadi instruksi lengkap</td>
</tr>
<tr v-click>
<td><strong>Penilaian output</strong></td>
<td>Membedakan jawaban yang meyakinkan dan yang benar</td>
<td>Minta AI menjawab, lalu cari satu kesalahannya</td>
</tr>
<tr v-click>
<td><strong>Iterasi</strong></td>
<td>Memperbaiki sedikit demi sedikit, bukan mengulang dari nol</td>
<td>Catat perubahan tiap versi dan bandingkan</td>
</tr>
<tr v-click>
<td><strong>Pengetahuan domain</strong></td>
<td>Paham isi bidangmu — AI hanya tahu permukaan</td>
<td>Jadikan materi kuliahmu sebagai sumber rujukan</td>
</tr>
</tbody>
</table>

</div>

<div class="abs-callout mt-6" v-click>

Perhatikan: <strong>tidak ada satu pun</strong> yang berupa hafalan sintaks. Semuanya bisa dilatih mulai hari ini.

</div>

<!--
Catatan: 2 menit. Poin penting: keterampilan ini transferable — berguna
walaupun nanti kamu tidak jadi pengguna tool AI.

Kalau peserta bertanya "jadi tidak perlu belajar coding sama sekali?" —
jawab: tetap berguna, tapi bukan lagi prasyarat untuk membuat sesuatu.
-->

---
layout: section
class: abs-dark
---

<div class="abs-eyebrow">Bagian 2 dari 5</div>

# Anatomi AI Builder

Sebelum menyetir, kenali dulu kendaraannya.

<!--
Pembatas bagian. 12 menit untuk bagian ini.
-->

---
layout: default
---

# Peta tool: tiga kategori

<div class="grid grid-cols-3 gap-4 mt-6 abs-card-row">

<Card icon="i-carbon-chat" title="1. Chat Assistant">
<p>Berbincang untuk berpikir, menulis, dan menganalisis. Membangun asisten dari instruksi dan dokumen.</p>
<div class="mt-3">
<span class="abs-pill">ChatGPT</span>
<span class="abs-pill">Claude</span>
<span class="abs-pill">Gemini</span>
</div>
<p class="mt-3 abs-small abs-muted">Untuk: membuat asisten, menyusun ide, mengolah teks. <strong>Ini fokus praktek kita.</strong></p>
</Card>

<Card icon="i-carbon-terminal" title="2. AI Coding Agent">
<p>Menjalankan perintah di komputermu: membuat berkas, menjalankan program, memperbaiki error.</p>
<div class="mt-3">
<span class="abs-pill">ZCode</span>
<span class="abs-pill">Gemini CLI</span>
<span class="abs-pill">Antigravity</span>
</div>
<p class="mt-3 abs-small abs-muted">Untuk: membangun aplikasi utuh. Jalur lanjutan setelah sesi ini.</p>
</Card>

<Card icon="i-carbon-application" title="3. App Builder">
<p>Antarmuka visual yang menghasilkan aplikasi web dari deskripsi dan mockup.</p>
<div class="mt-3">
<span class="abs-pill">Lovable</span>
<span class="abs-pill">Bolt</span>
<span class="abs-pill">v0</span>
</div>
<p class="mt-3 abs-small abs-muted">Untuk: tampilan cepat. Perlu pemahaman tambahan untuk dipakai serius.</p>
</Card>

</div>

<div class="abs-callout mt-8" v-click>

Kita mulai dari <strong>kategori 1</strong> karena paling cepat memberi hasil dan paling rendah risikonya. Kategori 2 dan 3 akan saya tunjukkan di akhir demo.

</div>

<!--
Catatan: 3 menit. Jangan terjebak membandingkan merek. Pesan yang ingin
ditanamkan: pilih tool sesuai tahap, bukan sesuai yang paling ramai dibicarakan.

Sebut bahwa ketiganya berbagi keterampilan yang sama — menulis instruksi yang
jelas. Jadi belajar satu, terbawa ke semuanya.
-->

---
layout: default
---

# Bagaimana AI sebenarnya bekerja

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

<h3>Cara sederhananya</h3>

<ul class="abs-list">
<li><strong>Memprediksi</strong> — AI menebak kata berikutnya yang paling masuk akal, berulang-ulang.</li>
<li><strong>Berdasarkan pola</strong> — tebakannya berasal dari pola raksasa dalam teks yang pernah ia baca.</li>
<li><strong>Dipandu konteks</strong> — arah tebakannya ditentukan oleh apa yang kamu berikan di percakapan itu.</li>
</ul>

<div class="abs-callout mt-6" v-click>

Konsekuensinya: hasil AI <strong>dipengaruhi kuat oleh apa yang kamu berikan</strong>. Konteks kabur, hasil kabur.

</div>

</div>

<div>

<h3>Analogi yang berguna</h3>

<div class="abs-card abs-card-accent">
<p><strong>AI itu seperti penulis sangat berpengalaman yang baru pertama kali masuk ke perusahaanku.</strong></p>
<p class="mt-2">Dia menulis dengan sangat lancar dan sangat percaya diri. Tapi dia belum tahu:</p>
<ul class="mt-2">
<li>siapa pembacanya,</li>
<li>aturan dan gaya perusahaanmu,</li>
<li>data dan fakta terbaru,</li>
<li>apa yang tidak boleh dilakukan.</li>
</ul>
<p class="mt-2">Tugasmu: memberi briefing yang jelas sebelum dia mulai menulis.</p>
</div>

</div>

</div>

<!--
Catatan: 3 menit. Hindari istilah teknis seperti "transformer" atau "token".
Yang penting peserta paham: AI bukan mesin pencari fakta, tapi mesin
penerus pola. Ini menjelaskan kenapa ia bisa salah dengan sangat meyakinkan.

Analogi ini akan dipakai terus sepanjang deck — kalau nanti peserta bingung,
kembali ke "briefing ke penulis baru".
-->

---
layout: default
---

# Anatomi satu asisten AI

<div class="grid grid-cols-4 gap-3 mt-6 abs-card-row">

<Card icon="i-carbon-settings" title="Instruksi">
<p><strong>Otaknya.</strong> Aturan main: siapa dia, tugasnya apa, apa yang dilarang.</p>
<p class="mt-2 abs-small abs-muted">Di ChatGPT: kolom Instructions.</p>
</Card>

<Card icon="i-carbon-notebook" title="Knowledge">
<p><strong>Memori.</strong> Dokumen rujukan yang hanya boleh ia pakai untuk menjawab.</p>
<p class="mt-2 abs-small abs-muted">Di ChatGPT: kolom Knowledge (unggah file).</p>
</Card>

<Card icon="i-carbon-list-checked" title="Contoh">
<p><strong>Kebiasaannya.</strong> Beberapa contoh jawaban ideal supaya gayanya konsisten.</p>
<p class="mt-2 abs-small abs-muted">Ditaruh di dalam instruksi.</p>
</Card>

<Card icon="i-carbon-tools" title="Tools">
<p><strong>Tangannya.</strong> Kemampuan tambahan seperti mencari web atau menjalankan kode.</p>
<p class="mt-2 abs-small abs-muted">Aktifkan hanya bila perlu.</p>
</Card>

</div>

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="abs-callout">
<strong>Empat komponen ini menjelaskan 90% masalah.</strong> Kalau asistenmu menjawab ngawur, hampir selalu penyebabnya ada di salah satu dari empat kotak di atas — bukan pada AI-nya.
</div>

<div class="abs-callout-ok abs-callout">
<strong>Urutan prioritas saat memperbaiki:</strong> Instruksi dulu, lalu Contoh, lalu Knowledge, terakhir Tools. Perbaiki satu per satu, jangan sekaligus.
</div>

</div>

<!--
Catatan: 3 menit. Slide ini adalah peta untuk seluruh sesi praktek nanti.
Minta peserta mengingat empat kata: Instruksi, Knowledge, Contoh, Tools.

Tekankan urutan prioritas perbaikan — pemula biasanya langsung menambah
dokumen padahal masalahnya ada di instruksi yang ambigu.
-->

---
layout: default
class: abs-dense
---

# Kenapa AI sering "ngawur"

<div class="mt-4">

<table>
<thead>
<tr><th style="width:26%">Gejala</th><th style="width:30%">Penyebabnya</th><th>Yang kamu lakukan</th></tr>
</thead>
<tbody>
<tr v-click>
<td><strong>Halusinasi</strong><br><span class="abs-small abs-muted">Mengarang fakta, kutipan, atau angka</span></td>
<td>AI mengejar kelancaran kalimat, bukan kebenaran</td>
<td>Minta sumber, lalu <strong>verifikasi sendiri</strong> untuk hal penting</td>
</tr>
<tr v-click>
<td><strong>Informasi usang</strong><br><span class="abs-small abs-muted">Data terasa ketinggalan zaman</span></td>
<td>Pengetahuannya berhenti di satu titik waktu</td>
<td>Berikan dokumen terbaru lewat Knowledge</td>
</tr>
<tr v-click>
<td><strong>Jawaban melenceng</strong><br><span class="abs-small abs-muted">Tidak sesuai yang kamu bayangkan</span></td>
<td>Instruksimu ambigu atau kurang batasan</td>
<td>Perbaiki instruksi: tambah peran, tujuan, format</td>
</tr>
<tr v-click>
<td><strong>Terlalu panjang</strong><br><span class="abs-small abs-muted">Bertele-tele, intinya tenggelam</span></td>
<td>Tidak ada batasan panjang dan format</td>
<td>Sebutkan format: "maksimal 5 poin" atau "3 paragraf"</td>
</tr>
<tr v-click>
<td><strong>Sok yakin</strong><br><span class="abs-small abs-muted">Salah tapi disampaikan dengan lancar</span></td>
<td>Gaya bahasa AI tidak mencerminkan keyakinan</td>
<td>Tambahkan: "sebutkan bagian yang kamu tidak yakin"</td>
</tr>
</tbody>
</table>

</div>

<div class="abs-callout mt-6" v-click>

Pola umumnya sama: <strong>gejalanya terlihat di jawaban, tapi penyebabnya hampir selalu di instruksi.</strong>

</div>

<!--
Catatan: 3 menit. Minta peserta mengingat baris ketiga dan terakhir — dua itu
yang paling sering terjadi di praktek nanti.

Baris "sok yakin" adalah alasan kenapa peran Quality Checker tidak bisa
didelegasikan. Ulangi poin itu.
-->

---
layout: default
---

# Batas aman yang wajib dijaga

<div class="grid grid-cols-3 gap-4 mt-6 abs-card-row">

<Card icon="i-carbon-locked" title="Jangan unggah data sensitif">
<ul>
<li>Nomor identitas, rekening, atau kata sandi</li>
<li>Data pribadi orang lain tanpa izin</li>
<li>Dokumen internal yang belum boleh tersebar</li>
<li>Data kesehatan atau keuangan pribadi</li>
</ul>
</Card>

<Card icon="i-carbon-search" title="Verifikasi sebelum percaya">
<ul>
<li>Angka, kutipan, dan rujukan — cek ulang ke sumbernya</li>
<li>Jangan menyalin ke pekerjaan akademik tanpa membaca</li>
<li>Perlakukan keluaran AI sebagai <strong>draft</strong>, bukan hasil akhir</li>
</ul>
</Card>

<Card icon="i-carbon-certificate" title="Jujur soal penggunaan AI">
<ul>
<li>Ikuti aturan kampus tentang penggunaan AI</li>
<li>Sebutkan bahwa AI membantu prosesmu</li>
<li>Kamu tetap penanggung jawab isinya</li>
</ul>
</Card>

</div>

<div class="abs-callout-danger abs-callout mt-8" v-click>

Aturan praktisnya: <strong>kalau kamu tidak mau data itu dibaca orang asing, jangan diunggah ke tool AI mana pun.</strong>

</div>

<!--
Catatan: 2 menit. Ini bagian yang sering dilewatkan pemateri, padahal penting
untuk audiens mahasiswa.

Sampaikan tanpa menakut-nakuti: intinya kebiasaan berpikir, bukan larangan.
-->

---
layout: section
class: abs-dark
---

<div class="abs-eyebrow">Bagian 3 dari 5</div>

# Framework Sprint

Lima langkah yang sama, dari ide apa pun.

<!--
Pembatas bagian. 15 menit. Ini bagian terpenting untuk sesi praktek —
ajak peserta memperhatikan dengan serius.
-->

---
layout: default
---

# Alur sprint: lima langkah

<div class="mt-4">

```mermaid {scale: 0.72, theme: 'base', themeVariables: {primaryColor: '#ffccd5', primaryTextColor: '#590d22', primaryBorderColor: '#a4133c', lineColor: '#a4133c', textColor: '#590d22', secondaryColor: '#ffb3c1', tertiaryColor: '#fff0f3', edgeLabelBackground: '#ffffff', fontFamily: 'Inter, ui-sans-serif, sans-serif', fontSize: '15px'}}
flowchart LR
    A["1. Ide<br/><small>masalah nyata</small>"] --> B["2. Spesifikasi<br/><small>hasil & batasan</small>"]
    B --> C["3. Instruksi<br/><small>peran & aturan</small>"]
    C --> D["4. Bangun<br/><small>+ knowledge</small>"]
    D --> E["5. Uji<br/><small>5 kasus</small>"]
    E -.->|"perbaiki"| C
```

</div>

<div class="grid grid-cols-3 gap-4 mt-4">

<div class="abs-callout">
<strong>Langkah 1–2</strong> dikerjakan <strong>tanpa AI</strong>. Ini murni pekerjaan berpikir — dan paling menentukan hasil akhir.
</div>

<div class="abs-callout">
<strong>Langkah 3–4</strong> adalah bagian berinteraksi dengan AI. Di sinilah iterasi paling banyak terjadi.
</div>

<div class="abs-callout">
<strong>Langkah 5</strong> menentukan apakah karyamu layak dipakai orang lain. Jangan dilewatkan.
</div>

</div>

<!--
Catatan: 2 menit untuk slide ini. Perhatikan panah putus-putus dari langkah 5
kembali ke langkah 3 — itu inti dari "sprint": berputar cepat, bukan sekali jadi.

Sebutkan bahwa sebagian besar pemula menghabiskan waktu di langkah 4, padahal
yang menentukan kualitas adalah langkah 1 dan 2.
-->

---
layout: default
---

# Langkah 1 — Ide

<div class="abs-step-head">
<span class="abs-pill">Langkah 1 dari 5</span>
<span class="abs-eyebrow">Dikerjakan tanpa AI</span>
</div>

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3 class="flex items-center gap-2"><span class="abs-icon" style="color:var(--abs-ok)"><span class="i-carbon-checkmark" /></span> Kriteria ide yang baik</h3>

<ul class="abs-check is-done mt-4">
<li><strong>Masalah nyata</strong> — kamu sendiri mengalaminya</li>
<li><strong>Satu pengguna jelas</strong> — bukan "semua orang"</li>
<li><strong>Satu pekerjaan</strong> — tanpa kata "dan"</li>
<li><strong>Cukup kecil</strong> — selesai dalam satu sesi</li>
<li><strong>Bisa dinilai</strong> — kamu tahu jawaban benar itu seperti apa</li>
</ul>

</div>

<div>

<h3 class="flex items-center gap-2"><span class="abs-icon" style="color:var(--abs-danger)"><span class="i-carbon-close-outline" /></span> Ide yang perlu dipersempit</h3>

<div class="abs-prompt mt-4">
<div class="abs-prompt-label is-bad">Terlalu luas</div>
<div class="abs-prompt-body">
"Aplikasi yang bisa membantu semua mahasiswa mengatur jadwal, belajar, keuangan, dan organisasi."
</div>
</div>

<div class="abs-prompt mt-3">
<div class="abs-prompt-label is-good">Cukup spesifik</div>
<div class="abs-prompt-body">
"Asisten yang menjawab pertanyaan tentang isi modul kuliah Struktur Data, dengan rujukan halaman."
</div>
</div>

</div>

</div>

<div class="abs-callout mt-6" v-click>

Uji cepat: kalau kamu tidak bisa menjelaskan idemu dalam <strong>satu kalimat tanpa koma</strong>, berarti masih terlalu luas.

</div>

<!--
Catatan: 3 menit. Latihan singkat: minta peserta menulis satu kalimat ide di
catatan masing-masing. Beri 45 detik. Lalu minta 2 orang membacakannya dan
bantu persempit bersama-sama.

Kesalahan paling umum: memilih masalah yang tidak pernah dialami sendiri.
Dorong mereka memilih dari pengalaman pribadi.
-->

---
layout: default
class: abs-dense
---

# Langkah 2 — Spesifikasi satu halaman

<div class="abs-step-head">
<span class="abs-pill">Langkah 2 dari 5</span>
<span class="abs-eyebrow">Dikerjakan tanpa AI</span>
</div>

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

Tulis enam hal ini. Tidak perlu lebih.

<table class="mt-2">
<tbody>
<tr><td><strong>1. Masalah</strong></td><td>Satu kalimat</td></tr>
<tr><td><strong>2. Pengguna</strong></td><td>Siapa persisnya</td></tr>
<tr><td><strong>3. Masukan</strong></td><td>Yang diberikan pengguna</td></tr>
<tr><td><strong>4. Keluaran</strong></td><td>Yang diterima pengguna</td></tr>
<tr><td><strong>5. Batasan</strong></td><td>Panjang, gaya, bahasa, larangan</td></tr>
<tr><td><strong>6. Kriteria sukses</strong></td><td>Cara tahu ini berhasil</td></tr>
</tbody>
</table>

</div>

<div>

<h3 class="abs-small">Contoh terisi</h3>

<div class="abs-card abs-card-accent" style="font-size:0.82rem">

<p class="abs-small"><strong>Masalah</strong><br>Mahasiswa sulit menemukan kembali penjelasan dosen saat belajar ulang.</p>

<p class="abs-small mt-2"><strong>Pengguna</strong><br>Mahasiswa yang mengambil mata kuliah Struktur Data.</p>

<p class="abs-small mt-2"><strong>Masukan</strong><br>Pertanyaan bebas dalam bahasa Indonesia.</p>

<p class="abs-small mt-2"><strong>Keluaran</strong><br>Jawaban 3–5 kalimat + rujukan halaman modul.</p>

<p class="abs-small mt-2"><strong>Batasan</strong><br>Hanya dari modul yang diunggah. Tidak mengarang. Maksimal 120 kata.</p>

<p class="abs-small mt-2"><strong>Kriteria sukses</strong><br>4 dari 5 pertanyaan uji dijawab benar dan menyebut halaman.</p>

</div>

</div>

</div>

<!--
Catatan: 4 menit. Slide ini yang paling sering diskip peserta, padahal paling
menentukan. Tekankan: enam baris ini nanti langsung menjadi bahan untuk
menulis instruksi di langkah 3.

Tips: kerjakan di kertas atau catatan, bukan di dalam AI. Kalau dikerjakan
di dalam AI, jawabannya akan didikte oleh AI, bukan oleh pikiranmu.
-->

---
layout: default
class: abs-dense
---

# Langkah 3 — Menulis instruksi

<div class="abs-step-head">
<span class="abs-pill">Langkah 3 dari 5</span>
<span class="abs-eyebrow">Mulai berinteraksi dengan AI</span>
</div>

<div class="grid grid-cols-5 gap-2 mt-3">

<div class="abs-card" style="padding:0.6rem">
<h3 style="font-size:0.86rem">Peran</h3>
<p class="abs-small">Kamu siapa</p>
</div>

<div class="abs-card" style="padding:0.6rem">
<h3 style="font-size:0.86rem">Tugas</h3>
<p class="abs-small">Lakukan apa</p>
</div>

<div class="abs-card" style="padding:0.6rem">
<h3 style="font-size:0.86rem">Batasan</h3>
<p class="abs-small">Jangan apa</p>
</div>

<div class="abs-card" style="padding:0.6rem">
<h3 style="font-size:0.86rem">Format</h3>
<p class="abs-small">Bentuk hasilnya</p>
</div>

<div class="abs-card" style="padding:0.6rem">
<h3 style="font-size:0.86rem">Contoh</h3>
<p class="abs-small">Satu acuan</p>
</div>

</div>

<div class="grid grid-cols-2 gap-6 mt-5 abs-card-row">

<div>

<PromptBox label="Sebelum — instruksi kabur" tone="bad">

Kamu adalah asisten yang membantu mahasiswa belajar Struktur Data.
Jawab pertanyaan mereka dengan jelas dan ramah.

</PromptBox>

<p class="abs-small abs-muted mt-2">
AI akan menjawab dengan benar, tapi <strong>gaya, panjang, dan sumbernya tidak bisa diprediksi</strong>. Tidak ada cara menilai hasilnya.
</p>

</div>

<div>

<PromptBox label="Sesudah — instruksi lengkap" tone="good">

**Peran:** Asisten belajar Struktur Data untuk mahasiswa semester 3.

**Tugas:** Menjawab pertanyaan berdasarkan HANYA isi modul yang diunggah.

**Batasan:**

- Maksimal 120 kata.
- Jika jawaban tidak ada di modul, katakan "tidak ada di modul", jangan mengarang.
- Selalu sebutkan nomor halaman.

**Format:** 3-5 kalimat, lalu baris terpisah: "Rujukan: halaman X".

**Contoh:** Pertanyaan "Apa itu stack?" - Jawab: "Stack adalah struktur data..." Rujukan: halaman 12.

</PromptBox>

</div>

</div>

<!--
Catatan: 4 menit. Ini slide paling praktis di Bagian 3.

Bacakan instruksi "sesudah" dengan lantang, lalu tunjuk setiap komponennya.
Tegaskan: bagian "jika jawaban tidak ada di modul, katakan tidak ada" adalah
satu baris yang paling banyak menyelamatkan kualitas jawaban.

Ingatkan: instruksi ini belum final. Nanti di langkah 5 akan diperbaiki lagi.
-->

---
layout: default
class: abs-dense
---

# Langkah 4 — Menyusun knowledge

<div class="abs-step-head">
<span class="abs-pill">Langkah 4 dari 5</span>
<span class="abs-eyebrow">Di sinilah AI mengenal konteksmu</span>
</div>

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3>Yang perlu diperhatikan</h3>

<ul class="abs-list">
<li><strong>Kualitas di atas kuantitas</strong> — 3 dokumen relevan lebih baik daripada 30 dokumen campur.</li>
<li><strong>Satu topik satu kumpulan</strong> — jangan campur materi kuliah dengan dokumen organisasi.</li>
<li><strong>Format yang mudah dibaca</strong> — teks atau PDF dengan teks asli, bukan hasil pindai gambar.</li>
<li><strong>Beri nama yang jelas</strong> — AI dan kamu sama-sama perlu tahu isi tiap berkas.</li>
<li><strong>Perbarui secara berkala</strong> — dokumen lama akan terus dianggap benar.</li>
</ul>

</div>

<div>

<h3>Contoh untuk studi kasus kita</h3>

<div class="abs-card abs-card-accent">

<p><strong>Sumber yang dipakai</strong></p>
<ul class="abs-small">
<li>Modul kuliah Struktur Data (PDF, 48 halaman)</li>
<li>Kumpulan 20 soal latihan beserta pembahasan</li>
<li>Ringkasan istilah penting (2 halaman)</li>
</ul>

<p class="mt-3"><strong>Yang sengaja tidak dipakai</strong></p>
<ul class="abs-small">
<li>Materi mata kuliah lain</li>
<li>Catatan pribadi yang belum rapi</li>
<li>Website luar tanpa tanggal dan penulis</li>
</ul>

</div>

<div class="abs-callout mt-4">

<strong>Prinsipnya:</strong> knowledge bukan tempat menyimpan semua hal. Ini tempat membatasi AI pada sumber yang kamu percaya.

</div>

</div>

</div>

<!--
Catatan: 3 menit. Poin yang paling sering salah dipahami: peserta mengira
semakin banyak dokumen semakin pintar. Jelaskan sebaliknya — dokumen yang
tidak relevan justru membuat AI melenceng.

Kalau peserta bertanya soal batas ukuran unggahan, jawab: mulai kecil, uji
dulu, baru tambah bila jawabannya kurang.
-->

---
layout: default
class: abs-dense
---

# Langkah 5 — Menguji sebelum dipakai

<div class="abs-step-head">
<span class="abs-pill">Langkah 5 dari 5</span>
<span class="abs-eyebrow">Jangan dilewatkan</span>
</div>

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3>Siapkan 5 kasus uji</h3>

<div class="abs-card">
<p><strong>1. Kasus normal</strong> — pertanyaan biasa yang kamu harapkan</p>
<p class="mt-2"><strong>2. Kasus normal kedua</strong> — variasi yang berbeda</p>
<p class="mt-2"><strong>3. Kasus sulit</strong> — pertanyaan yang butuh dua halaman untuk menjawab</p>
<p class="mt-2"><strong>4. Kasus di luar cakupan</strong> — pertanyaan yang jawabannya tidak ada di dokumen</p>
<p class="mt-2"><strong>5. Kasus jebakan</strong> — pertanyaan yang jawabannya salah kalau AI mengarang</p>
</div>

<p class="abs-small abs-muted mt-3">Kasus 4 dan 5 adalah yang paling penting — di situ kualitas asistenmu diuji.</p>

</div>

<div>

<h3>Cara menilai</h3>

<div class="abs-callout mt-3">
<strong>Lulus</strong> jika: jawaban benar, format sesuai, panjang sesuai, dan sumber disebutkan bila diminta.
</div>

<div class="abs-callout-warn abs-callout mt-3">
<strong>Tidak lulus</strong> jika: mengarang, melenceng dari topik, terlalu panjang, atau tidak mengakui ketidaktahuannya.
</div>

<h3 class="mt-5">Siklus perbaikan</h3>

<div class="abs-flow">
<div class="abs-flow-item">Uji</div>
<div class="abs-flow-item">Catat cacat</div>
<div class="abs-flow-item is-active">Perbaiki instruksi</div>
<div class="abs-flow-item">Uji ulang</div>
</div>

<p class="abs-small abs-muted mt-3">Perbaiki <strong>satu hal per iterasi</strong>, lalu catat apa yang berubah. Kalau memperbaiki banyak hal sekaligus, kamu tidak akan tahu mana yang bekerja.</p>

</div>

</div>

<!--
Catatan: 3 menit. Tunjukkan bahwa kasus 4 dan 5 itu mudah dibuat dan
sangat membongkar kelemahan.

Pesan penutup bagian ini: asisten yang mengakui ketidaktahuannya lebih
berguna daripada asisten yang selalu menjawab.
-->

---
layout: section
class: abs-dark
---

<div class="abs-eyebrow">Bagian 4 dari 5</div>

# Live Demo

Sekarang saya bangun satu asisten dari nol di depan kalian.

<!--
Pembatas bagian. 20 menit. Sebelum mulai, pastikan:

- Tab browser sudah siap dengan akun yang sudah login
- Koneksi internet stabil (siapkan hotspot cadangan)
- Zoom browser 110-125% agar terlihat dari baris belakang
- Notifikasi desktop dimatikan
- File modul untuk knowledge sudah ada di desktop, siap diunggah

Kalau ada peserta yang tertinggal, minta mereka mencatat dulu dan bertanya
di akhir — jangan hentikan demo di tengah.
-->

---
layout: default
class: abs-dense
---

# Studi kasus demo

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3>Asisten Reviewer Proposal Skripsi</h3>

<p class="abs-lead" style="font-size:1.05rem">
Membantu mahasiswa mengecek draft proposal sebelum diserahkan ke dosen pembimbing.
</p>

<div class="abs-card mt-4">

<p><strong>Masalah</strong></p>
<p class="abs-small">Mahasiswa sering tidak sadar bagian proposalnya lemah sampai dikembalikan dosen.</p>

<p class="mt-3"><strong>Pengguna</strong></p>
<p class="abs-small">Mahasiswa tingkat akhir yang sedang menyusun proposal.</p>

<p class="mt-3"><strong>Masukan</strong></p>
<p class="abs-small">Teks atau potongan draft proposal.</p>

<p class="mt-3"><strong>Keluaran</strong></p>
<p class="abs-small">Daftar kelemahan spesifik + saran perbaikan, per bagian.</p>

</div>

</div>

<div>

<h3>Yang akan saya perlihatkan</h3>

<div class="abs-flow" style="flex-direction:column;gap:0.5rem">

<div class="abs-demo-item">
<span class="abs-demo-tag">A</span> Ide → Spesifikasi (tanpa AI)
</div>

<div class="abs-demo-item">
<span class="abs-demo-tag">B</span> Instruksi versi 1 → kritik diri → versi 2
</div>

<div class="abs-demo-item">
<span class="abs-demo-tag">C</span> Menambahkan knowledge dan contoh
</div>

<div class="abs-demo-item">
<span class="abs-demo-tag">D</span> Uji 3 kasus → temukan cacat → perbaiki
</div>

</div>

<div class="abs-callout mt-4">

<strong>Perhatikan yang saya lakukan, bukan hanya hasilnya.</strong> Yang paling berharga di demo ini adalah bagian saya memperbaiki instruksi setelah hasilnya kurang tepat.

</div>

</div>

</div>

<!--
Catatan: 2 menit. Bacakan studi kasusnya, lalu langsung masuk ke demo.

Alasan memilih studi kasus ini: dekat dengan keseharian mahasiswa, mudah
dinilai benar-salahnya, dan kelemahannya bisa didemonstrasikan dengan jelas.

Ingatkan peserta bahwa mereka tidak harus memakai ide yang sama — ini hanya
contoh alur kerjanya.
-->

---
layout: default
---

# Demo A — Ide menjadi spesifikasi

<div class="abs-step-head">
<span class="abs-pill">Demo · Langkah 1–2</span>
<span class="abs-eyebrow">Tanpa AI</span>
</div>

<div class="grid grid-cols-2 gap-8">

<div>

<h3>Yang saya lakukan di layar</h3>

<ul class="abs-check mt-3">
<li>Menuliskan satu kalimat masalah — tanpa kata "dan"</li>
<li>Menyempitkan pengguna menjadi satu kelompok spesifik</li>
<li>Mengisi enam baris spesifikasi</li>
<li>Menentukan kriteria sukses yang bisa diukur</li>
</ul>

<div class="abs-callout mt-4">

<strong>Perhatikan:</strong> saya belum membuka AI sama sekali di tahap ini.

</div>

</div>

<div>

<h3>Hasil spesifikasinya</h3>

<PromptBox label="Spesifikasi — enam baris">

**Masalah:** Mahasiswa tidak tahu bagian mana dari proposalnya yang lemah sebelum diserahkan.

**Pengguna:** Mahasiswa tingkat akhir yang sedang menyusun proposal skripsi.

**Masukan:** Potongan teks draft proposal (1-3 halaman).

**Keluaran:** Daftar kelemahan + saran perbaikan, dikelompokkan per bagian proposal.

**Batasan:** Berdasarkan kaidah proposal ilmiah umum. Tidak menilai isi substansi penelitian. Maksimal 5 temuan. Bahasa Indonesia.

**Kriteria sukses:** 4 dari 5 draft uji mendapat temuan yang menurut saya relevan.

</PromptBox>

</div>

</div>

<!--
SKRIP DEMO A (4 menit)

1. Buka catatan kosong (Notes / Notion / teks editor). JANGAN buka ChatGPT dulu.
2. Ketik di layar: "Mahasiswa tidak tahu bagian mana dari proposalnya yang
   lemah sebelum diserahkan." Tunjukkan bahwa tidak ada kata "dan".
3. Tanyakan ke peserta: "Penggunanya siapa?" — ambil satu jawaban, sempitkan.
4. Isi enam baris spesifikasi sambil menjelaskan alasan tiap baris.
5. Berhenti di baris "Batasan". Jelaskan kenapa "tidak menilai substansi
   penelitian" penting: membatasi tanggung jawab AI agar tidak overclaim.
6. Baris terakhir: kriteria sukses harus terukur. Tunjukkan bahwa
   "4 dari 5" jauh lebih berguna daripada "hasilnya bagus".

Poin yang harus diucapkan: "Ini 6 menit kerja tanpa AI yang menentukan
kualitas seluruh sisa sesi."
-->

---
layout: default
class: abs-dense
---

# Demo B — Instruksi dan kritik diri

<div class="abs-step-head">
<span class="abs-pill">Demo · Langkah 3</span>
<span class="abs-eyebrow">Iterasi pertama</span>
</div>

<div class="grid grid-cols-2 gap-6 abs-card-row">

<div>

<PromptBox label="Versi 1" tone="bad">

Kamu adalah reviewer proposal skripsi. Periksa proposal berikut dan berikan masukan yang membangun untuk perbaikan.

</PromptBox>

<p class="abs-small abs-muted mt-2">Hasilnya: masukan terlalu umum, panjang, dan tidak terstruktur. Sulit ditindaklanjuti.</p>

<div class="abs-prompt mt-4">
<div class="abs-prompt-label">Kritik diri — prompt yang saya ketik</div>
<div class="abs-prompt-body">
Sebelum menjawab, sebutkan <strong>3 kelemahan dari instruksi di atas</strong>. Lalu tulis ulang instruksinya menjadi lebih baik, dan jelaskan tiap perbaikan dalam satu baris.
</div>
</div>

</div>

<div>

<PromptBox label="Versi 2" tone="good">

**Peran:** Kamu dosen pembimbing yang teliti dan konstruktif.

**Tugas:** Periksa draft proposal yang saya berikan. Temukan kelemahan pada struktur, kejelasan argumen, dan konsistensi penulisan.

**Batasan:**
- Maksimal 5 temuan, diurutkan dari yang paling penting.
- Setiap temuan: kutip bagian yang bermasalah, jelaskan masalahnya dalam 1 kalimat, beri 1 saran perbaikan.
- Jangan menilai kebenaran substansi penelitian.
- Jika bagian tertentu sudah baik, tidak perlu dibahas.

**Format:**
Nomor. [Bagian] Kutipan -> Masalah -> Saran

**Contoh:**
1. [Latar Belakang] "Banyak penelitian telah..." -> Terlalu umum, tidak ada data -> Sebutkan 1 data spesifik beserta sumbernya.

</PromptBox>

</div>

</div>

<!--
SKRIP DEMO B (5 menit)

1. Tunjukkan instruksi versi 1. Kirim, lalu tampilkan hasilnya ke layar.
   Diam sebentar, biarkan peserta melihat bahwa hasilnya "terlihat oke
   tapi tidak berguna".
2. Baca satu temuan dari hasil itu dengan lantang. Tanyakan: "Ini bisa
   langsung kamu pakai untuk merevisi?" — jawabannya tidak.
3. Baru setelah itu ketik prompt kritik diri. Ini momen terpenting di demo:
   AI dipakai untuk mengkritik instruksi, bukan hanya menjalankannya.
4. Bandingkan hasil kritik dengan versi 2 yang sudah saya siapkan. Jelaskan
   bahwa versi 2 biasanya muncul dari 2-3 putaran, bukan sekali jadi.
5. Kirim versi 2, tampilkan hasilnya berdampingan dengan versi 1.

Poin yang harus diucapkan: "Saya tidak menulis ulang dari nol. Saya
memperbaiki tiga hal: peran yang lebih spesifik, batasan jumlah temuan,
dan format keluaran yang bisa ditindaklanjuti."
-->

---
layout: default
class: abs-dense
---

# Demo C — Menambahkan knowledge

<div class="abs-step-head">
<span class="abs-pill">Demo · Langkah 4</span>
<span class="abs-eyebrow">Memberi AI konteks</span>
</div>

<div class="grid grid-cols-2 gap-8">

<div>

<h3>Yang saya unggah</h3>

<ul class="abs-list mt-3">
<li>Panduan penulisan proposal dari kampus (PDF, 24 halaman)</li>
<li>Dua contoh proposal yang pernah mendapat nilai baik</li>
<li>Daftar kesalahan yang paling sering muncul dari dosen</li>
</ul>

<div class="abs-callout mt-4">

<strong>Kenapa tiga dokumen ini?</strong> Karena ketiganya menjawab pertanyaan yang sama: "menurut standar kampus ini, proposal yang baik itu seperti apa?"

</div>

<h3 class="mt-5">Satu baris tambahan di instruksi</h3>

<PromptBox label="Tambahan pada bagian Batasan">

- Gunakan HANYA panduan penulisan dan contoh proposal yang saya unggah sebagai acuan penilaian.
- Jika ada aturan kampus yang tidak tercantum di dokumen, katakan tidak tahu, jangan menebak.

</PromptBox>

</div>

<div>

<h3>Perbedaan yang saya amati</h3>

<div class="grid gap-3 mt-3">

<div class="abs-card">
<h3 class="abs-small flex items-center gap-1" style="color:var(--abs-danger)"><span class="i-carbon-close-outline" />Sebelum ada knowledge</h3>
<p class="abs-small">Saran bersifat umum: "perkuat latar belakang", "perbaiki metodologi". Tidak menyebut aturan kampus sama sekali.</p>
</div>

<div class="abs-card abs-card-accent">
<h3 class="abs-small flex items-center gap-1" style="color:var(--abs-ok)"><span class="i-carbon-checkmark" />Sesudah ada knowledge</h3>
<p class="abs-small">Saran menyebut acuan konkret: format sitasi, urutan bab, dan batas jumlah halaman sesuai panduan kampus.</p>
</div>

</div>

<div class="abs-callout-warn abs-callout mt-5">

<strong>Ini yang paling sering bikin peserta kecewa:</strong> mereka mengunggah dokumen tapi lupa menambahkan baris "gunakan HANYA dokumen ini". Tanpa baris itu, AI tetap menjawab dari pengetahuannya sendiri.

</div>

</div>

</div>

<!--
SKRIP DEMO C (4 menit)

1. Unggah ketiga dokumen ke kolom Knowledge — lakukan perlahan agar terlihat.
2. Sebelum menambahkan baris instruksi, kirim satu pertanyaan uji.
   Tunjukkan bahwa jawabannya masih generik.
3. Baru tambahkan baris "gunakan HANYA dokumen ini". Kirim pertanyaan yang
   sama. Tunjukkan perbedaannya di layar — ini momen "aha" yang penting.
4. Tunjuk satu saran spesifik yang menyebut aturan kampus, dan bandingkan
   dengan jawaban sebelumnya.

Poin yang harus diucapkan: "Dokumen yang diunggah tidak berguna sampai saya
memberi tahu AI untuk memakainya. Dua hal ini harus berpasangan."
-->

---
layout: default
class: abs-dense
---

# Demo D — Menguji dan memperbaiki

<div class="abs-step-head">
<span class="abs-pill">Demo · Langkah 5</span>
<span class="abs-eyebrow">Bagian terpenting</span>
</div>

<div class="grid grid-cols-2 gap-6">

<div>

<h3>Tiga kasus uji saya</h3>

<div class="abs-card mt-2">
<p><strong>Kasus 1 — Normal</strong></p>
<p class="abs-small">Draft proposal dengan latar belakang yang terlalu umum. <span class="abs-pill abs-pill-ok"><span class="i-carbon-checkmark" />Lulus</span></p>
</div>

<div class="abs-card mt-2">
<p><strong>Kasus 2 — Di luar cakupan</strong></p>
<p class="abs-small">Pertanyaan tentang statistik penelitian, bukan tentang penulisan. <span class="abs-pill abs-pill-warn"><span class="i-carbon-warning-alt" />Melenceng</span></p>
</div>

<div class="abs-card mt-2">
<p><strong>Kasus 3 — Jebakan</strong></p>
<p class="abs-small">Draft dengan metodologi yang lemah tapi penulisan rapi. <span class="abs-pill abs-pill-danger"><span class="i-carbon-close-outline" />Gagal mendeteksi</span></p>
</div>

</div>

<div>

<h3>Perbaikan yang saya lakukan</h3>

<div class="abs-prompt mt-2">
<div class="abs-prompt-label is-good">Perbaikan 1 — batas cakupan</div>
<div class="abs-prompt-body">
Jika permintaan <strong>di luar topik penulisan proposal</strong>, tolak dengan sopan: kamu hanya menilai aspek penulisan, bukan metodologi atau statistik.
</div>
</div>

<div class="abs-prompt mt-2">
<div class="abs-prompt-label is-good">Perbaikan 2 — paksa periksa struktur</div>
<div class="abs-prompt-body">
Sebelum memberi temuan, periksa <strong>kelengkapan bagian wajib</strong> proposal satu per satu. Sebutkan bagian mana yang <strong>ada</strong> dan mana yang <strong>tidak ada</strong>.
</div>
</div>

<div class="abs-callout-ok abs-callout mt-2">

Hasilnya: kasus 2 ditolak dengan tepat, dan kasus 3 menghasilkan temuan "metodologi tidak dijelaskan".

</div>

</div>

</div>

<!--
SKRIP DEMO D (5 menit)

1. Tampilkan ketiga kasus uji di layar (sudah disiapkan sebelumnya sebagai
   dokumen terpisah — jangan mengetik panjang saat demo).
2. Jalankan kasus 1. Lulus. Jangan berhenti lama.
3. Jalankan kasus 2. Tunjukkan jawabannya melenceng ke statistik.
   Tanyakan ke peserta: "Ini salah di mana?" — ambil satu jawaban.
4. Jalankan kasus 3. Ini yang paling penting: tunjukkan bahwa AI melewatkan
   metodologi yang lemah. Diam sebentar. Biarkan peserta melihat sendiri
   kelemahannya.
5. Ketik dua perbaikan. Jalankan ulang kasus 2 dan 3. Tunjukkan hasilnya.

Poin yang harus diucapkan: "Saya menemukan dua cacat bukan karena saya
pintar, tapi karena saya sengaja membuat kasus uji yang mencoba mematahkan
asisten saya. Ini yang membedakan prototype mainan dan prototype yang layak."
-->

---
layout: default
class: abs-dense
---

# Rekap demo — dan langkah berikutnya

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3>Yang baru saja terjadi</h3>

<div class="abs-flow" style="flex-direction:column;gap:0.45rem">
<div class="abs-flow-item" style="text-align:left;padding:0.6rem">1. Ide disempitkan jadi satu kalimat</div>
<div class="abs-flow-item" style="text-align:left;padding:0.6rem">2. Spesifikasi enam baris tanpa AI</div>
<div class="abs-flow-item" style="text-align:left;padding:0.6rem">3. Instruksi versi 1, dikritik, jadi versi 2</div>
<div class="abs-flow-item" style="text-align:left;padding:0.6rem">4. Knowledge + baris "gunakan HANYA dokumen ini"</div>
<div class="abs-flow-item" style="text-align:left;padding:0.6rem">5. Tiga kasus uji, dua cacat ditemukan, diperbaiki</div>
</div>

<div class="abs-callout mt-4">

<strong>Total waktu:</strong> sekitar 20 menit untuk satu asisten yang benar-benar berfungsi.

</div>

</div>

<div>

<h3>Kalau ingin jadi aplikasi utuh</h3>

<p class="abs-small abs-muted">Asisten yang baru kita buat hidup di dalam layar chat. Kalau ingin bentuknya aplikasi sendiri — halaman web dengan antarmuka dan tombol — di situlah kategori tool kedua masuk.</p>

<div class="abs-card abs-card-accent mt-3">

<p><strong>AI Coding Agent</strong> — ZCode, Gemini CLI, Antigravity</p>

<ul class="abs-small mt-2">
<li>Kamu menjelaskan aplikasi yang diinginkan dalam bahasa biasa</li>
<li>Agent membuat berkas, menulis kode, dan menjalankannya</li>
<li>Kamu menguji hasilnya di browser dan memberi koreksi</li>
<li>Keterampilan yang dipakai <strong>sama persis</strong> dengan hari ini</li>
</ul>

</div>

<div class="abs-callout mt-3">

<strong>Ini bukan materi hari ini.</strong> Saya tunjukkan supaya kamu tahu ke mana arah lanjutannya setelah menguasai dasar.

</div>

</div>

</div>

<!--
Catatan: 2 menit. Ini slide jembatan. Pesannya: yang berubah hanya wadahnya,
bukan cara berpikirnya.

Kalau ada peserta yang antusias dan bertanya lebih jauh soal AI coding agent,
jawab singkat lalu arahkan ke sesi lanjutan — jangan menyimpang dari agenda.
-->

---
layout: section
class: abs-dark
---

<div class="abs-eyebrow">Bagian 5 dari 5</div>

# Persiapan Praktek

Sekarang bagianmu.

<!--
Pembatas bagian. 13 menit. Di sini nada bicara berubah dari "mengajar"
menjadi "mempersiapkan" — peserta harus merasa siap, bukan gugup.
-->

---
layout: default
---

# Roadmap bertingkat

<div class="mt-6">

<div class="grid grid-cols-4 gap-3">

<div class="abs-card abs-card-accent">
<div class="abs-pill">Hari ini</div>
<h3 class="mt-2">Asisten</h3>
<p>Satu tugas spesifik, satu pengguna, di dalam layar chat.</p>
</div>

<div class="abs-card">
<div class="abs-pill">1-2 minggu lagi</div>
<h3 class="mt-2">Integrasi</h3>
<p>Terhubung ke alat lain: email, spreadsheet, atau formulir.</p>
</div>

<div class="abs-card">
<div class="abs-pill">1-2 bulan lagi</div>
<h3 class="mt-2">Aplikasi</h3>
<p>Antarmuka sendiri dengan bantuan AI coding agent.</p>
</div>

<div class="abs-card">
<div class="abs-pill">Lebih jauh</div>
<h3 class="mt-2">Produk</h3>
<p>Dipakai orang lain, dengan pengujian dan tanggung jawab penuh.</p>
</div>

</div>

</div>

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="abs-callout">

<strong>Tiap tingkat menambah tanggung jawab, bukan hanya fitur.</strong> Di tingkat aplikasi, kamu bertanggung jawab atas antarmuka dan data pengguna.

</div>

<div class="abs-callout">

<strong>Lompat tingkat adalah kesalahan umum.</strong> Banyak yang ingin langsung ke "produk" lalu berhenti di tengah karena terlalu besar. Selesaikan tingkat pertama dulu sampai benar-benar dipakai.

</div>

</div>

<!--
Catatan: 3 menit. Tunjukkan bahwa langkah pertama sengaja dibuat kecil.
Target hari ini hanya kotak pertama — dan itu sudah cukup.

Kalau ada yang bertanya "berapa lama sampai bisa bikin produk?" —
jawab jujur: tergantung seberapa cepat kamu belajar menilai hasil dan
seberapa keras kamu menguji.
-->

---
layout: default
---

# Etika dan tanggung jawab

<div class="grid grid-cols-3 gap-4 mt-6 abs-card-row">

<Card icon="i-carbon-search" title="Verifikasi">
<p>Kamu bertanggung jawab atas apa yang kamu serahkan, walaupun AI yang menulisnya.</p>
<p class="mt-2 abs-small">Perlakukan keluaran AI sebagai draft yang belum diperiksa.</p>
</Card>

<Card icon="i-carbon-text-link" title="Atribusi">
<p>Sebutkan penggunaan AI sesuai kebijakan yang berlaku di kampusmu.</p>
<p class="mt-2 abs-small">Kalau aturannya belum jelas, tanyakan — jangan diasumsikan.</p>
</Card>

<Card icon="i-carbon-view" title="Transparansi">
<p>Kalau kamu membangun asisten untuk orang lain, beri tahu bahwa itu asisten AI.</p>
<p class="mt-2 abs-small">Jangan biarkan pengguna mengira mereka bicara dengan manusia.</p>
</Card>

</div>

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="abs-callout-warn abs-callout">
<strong>Yang tidak boleh didelegasikan:</strong> keputusan yang berdampak pada orang lain. AI boleh menyiapkan bahan, tapi keputusannya tetap milikmu.
</div>

<div class="abs-callout-ok abs-callout">
<strong>Kebiasaan yang baik sejak awal:</strong> simpan catatan tentang instruksi yang kamu pakai dan alasan perubahannya. Ini berguna saat kamu perlu menjelaskan prosesmu.
</div>

</div>

<!--
Catatan: 3 menit. Nada bicara: serius tapi tidak menakut-nakuti.

Contoh konkret untuk audiens mahasiswa: menyerahkan tugas yang ditulis AI
tanpa dibaca itu masalah akademik; memakai AI untuk memahami konsep lalu
menulis sendiri itu wajar. Bedanya ada di proses berpikir, bukan di alatnya.
-->

---
layout: default
---

# Checklist persiapan praktek

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

<h3>Siapkan sebelum sesi</h3>

<ul class="abs-check mt-3">
<li><strong>Akun aktif</strong> di salah satu: ChatGPT, Claude, atau Gemini — pastikan sudah bisa login</li>
<li><strong>Satu ide</strong> yang lolos kriteria Langkah 1: satu kalimat, tanpa koma</li>
<li><strong>2-3 dokumen sumber</strong> berformat PDF atau teks, relevan dengan idemu</li>
<li><strong>Catatan spesifikasi</strong> enam baris, di kertas atau aplikasi catatan</li>
<li><strong>Laptop</strong> beserta charger dan koneksi internet</li>
</ul>

</div>

<div>

<h3>Yang akan kita lakukan bersama</h3>

<div class="abs-flow" style="flex-direction:column;gap:0.5rem">
<div class="abs-flow-item is-active" style="text-align:left;padding:0.65rem">Tulis instruksi versi 1</div>
<div class="abs-flow-item is-active" style="text-align:left;padding:0.65rem">Uji dengan 5 kasus</div>
<div class="abs-flow-item is-active" style="text-align:left;padding:0.65rem">Perbaiki minimal 2 kali</div>
<div class="abs-flow-item is-active" style="text-align:left;padding:0.65rem">Tunjukkan hasil ke peserta lain</div>
</div>

<div class="abs-callout mt-4">

<strong>Kalau belum punya ide, jangan khawatir.</strong> Slide berikutnya berisi daftar ide yang bisa langsung kamu pakai.

</div>

</div>

</div>

<!--
Catatan: 3 menit. Bacakan poin "Siapkan sebelum sesi" satu per satu — ini yang
paling sering menyebabkan peserta tertinggal di sesi praktek.

Ingatkan soal dokumen sumber: format hasil pindai (scan) sering tidak terbaca
dengan baik. Sarankan PDF dengan teks asli.

Kalau ada peserta yang belum siap, minta mereka berpasangan dengan yang sudah
siap untuk sesi pertama.
-->

---
layout: default
class: abs-dense
---

# Cheat sheet: 10 pola prompt

<div class="abs-small abs-muted mb-2">Slide ini sengaja padat — foto layar ini sebelum lanjut.</div>

<div class="grid grid-cols-2 gap-x-8 gap-y-2">

<div>

<table>
<tbody>
<tr><td style="width:34%"><strong>Batasi sumber</strong></td><td>"Gunakan HANYA dokumen yang saya unggah. Kalau tidak ada di sana, katakan tidak tahu."</td></tr>
<tr><td><strong>Batasi panjang</strong></td><td>"Maksimal 120 kata" / "Maksimal 5 poin"</td></tr>
<tr><td><strong>Tentukan format</strong></td><td>"Format: Masalah -> Saran -> Contoh"</td></tr>
<tr><td><strong>Minta alasan</strong></td><td>"Jelaskan alasan tiap saran dalam satu baris."</td></tr>
<tr><td><strong>Kritik diri</strong></td><td>"Sebutkan 3 kelemahan dari jawabanmu sendiri, lalu perbaiki."</td></tr>
</tbody>
</table>

</div>

<div>

<table>
<tbody>
<tr><td style="width:34%"><strong>Minta bertanya</strong></td><td>"Sebelum menjawab, ajukan 3 pertanyaan yang membuat jawabanmu lebih tepat."</td></tr>
<tr><td><strong>Beri contoh</strong></td><td>"Ikuti gaya contoh ini: ..."</td></tr>
<tr><td><strong>Akui ketidaktahuan</strong></td><td>"Tandai bagian yang kamu tidak yakin dengan tanda [?]."</td></tr>
<tr><td><strong>Ubah peran</strong></td><td>"Sekarang berperan sebagai dosen yang kritis terhadap jawaban tadi."</td></tr>
<tr><td><strong>Iterasi sempit</strong></td><td>"Perbaiki hanya bagian X, jangan ubah bagian lain."</td></tr>
</tbody>
</table>

</div>

</div>

<div class="abs-callout mt-5">

Lima pola pertama menyelesaikan sebagian besar masalah. Kalau hasilnya kurang tepat, cek dulu apakah kamu sudah memakai salah satunya.

</div>

<!--
Catatan: 3 menit. Minta peserta benar-benar memfoto slide ini. Beri waktu
10 detik untuk memfoto, jangan bicara saat mereka memfoto.

Setelah selesai memfoto, baca cepat tiga pola yang paling sering dipakai:
"Batasi sumber", "Kritik diri", dan "Akui ketidaktahuan".
-->

---
layout: default
---

# Ide praktek untuk pemula

<div class="abs-small abs-muted mb-2">Pilih satu. Kalau idemu sendiri sudah ada, pakai idemu.</div>

<div class="grid grid-cols-2 gap-x-8 gap-y-1 abs-small">

<div>

<ul class="abs-list">
<li><strong>Asisten modul kuliah</strong> — menjawab pertanyaan dari materi yang kamu unggah</li>
<li><strong>Reviewer tulisan</strong> — memeriksa struktur dan tata bahasa draft esai</li>
<li><strong>Penyusun ringkasan</strong> — merangkum PDF panjang jadi poin penting</li>
<li><strong>Pembuat soal latihan</strong> — menyusun soal dari materi beserta pembahasan</li>
<li><strong>Penerjemah istilah</strong> — menjelaskan istilah teknis dengan bahasa sederhana</li>
</ul>

</div>

<div>

<ul class="abs-list">
<li><strong>Pembantu organisasi</strong> — menjawab pertanyaan berulang soal program kerja</li>
<li><strong>Perencana belajar</strong> — menyusun jadwal dari daftar materi dan tenggat</li>
<li><strong>Pemeriksa format</strong> — memeriksa kesesuaian format sitasi dan struktur</li>
<li><strong>Pemandu wawancara</strong> — melatih menjawab pertanyaan wawancara kerja</li>
<li><strong>Penjelas kode</strong> — menjelaskan potongan kode baris per baris</li>
</ul>

</div>

</div>

<div class="grid grid-cols-2 gap-8 mt-5">

<div class="abs-callout">
<strong>Pilih yang paling kamu butuhkan minggu ini.</strong> Asisten yang kamu pakai sendiri akan kamu perbaiki lebih serius daripada asisten latihan.
</div>

<div class="abs-callout-warn abs-callout">
<strong>Hindari ide yang butuh data orang lain</strong> di sesi pertama. Mulai dari data dan dokumenmu sendiri — lebih aman dan lebih cepat.
</div>

</div>

<!--
Catatan: 2 menit. Baca cepat saja, jangan satu per satu. Tujuannya memberi
pilihan bagi yang belum punya ide.

Kalau ada peserta yang tetap bingung, arahkan ke ide pertama
("Asisten modul kuliah") — itu yang paling mudah dan paling cepat berhasil.
-->

---
layout: cover
class: abs-cover
---

# Sekarang bagianmu

<div class="abs-cover-rule" style="margin:1.5rem auto" />

<p class="abs-lead">
Kamu sudah punya kerangka, alat, dan daftar ide.<br>
Siapkan satu ide dan dua dokumen — sisanya kita kerjakan bersama.
</p>

<div class="mt-10 abs-muted abs-small">

**Sumber belajar:**
[Panduan prompt](https://platform.openai.com/docs/guides/prompt-engineering) ·
[Dokumentasi Claude](https://docs.claude.com) ·
[Panduan Gemini](https://ai.google.dev/gemini-api/docs/prompting-strategies)

</div>

<!--
Catatan penutup (1 menit). Tutup dengan tenang, jangan buru-buru.

Kalimat penutup yang disarankan: "Yang membedakan orang yang berhasil di sesi
praktek bukan yang paling paham teknologi, tapi yang idenya paling jelas.
Sampai jumpa di sesi praktek."

Buka sesi tanya jawab. Kalau ada pertanyaan yang terlalu teknis, catat dan
jawab setelah sesi selesai agar tidak menggeser agenda.
-->
