# BUKU MODUL PELATIHAN
> Program **FOLUR UNDP** — WebGIS Interaktif + Modul Pembelajaran

Website pelatihan penguatan kapasitas **Perencanaan Zonasi Spasial** untuk level Kabupaten. Menampilkan 30+ layer indikator spasial hasil agregasi AHP (Analytical Hierarchy Process), dengan AI assistant **Ka Zoni** untuk analisis spasial.

**Production**: [pelatihan-zonasi.diffa.net](https://pelatihan-zonasi.diffa.net)
## Perencanaan Zonasi Spasial Kabupaten Luwu
### Program FOLUR (Food Systems, Land Use, and Restoration)

**Kabupaten Luwu, Sulawesi Selatan**

---

## Kata Pengantar

Buku modul ini disusun sebagai bahan pegangan peserta **Pelatihan Perencanaan Zonasi Spasial Kabupaten Luwu**. Pelatihan terdiri dari **6 modul** (masing-masing ± 15 menit) yang membawa peserta dari konsep dasar zonasi, metodologi analisis, hingga penerapan dalam perizinan dan pemantauan.

Setiap modul diakhiri dengan **kuis** untuk menguji pemahaman. Kunci jawaban tersedia pada lampiran di bagian akhir buku ini — kerjakan kuis terlebih dahulu sebelum melihat kunci.

Pelatihan ini didukung **platform web interaktif** yang memuat:

| Halaman | Fungsi |
|---|---|
| Beranda | Ringkasan program dan navigasi |
| Modul Pelatihan (`modul.html`) | Materi digital + kuis daring (akses tiap modul menggunakan **PIN** yang dibagikan fasilitator) |
| Peta Interaktif (`map.html`) | WebGIS 29 layer indikator: toggle layer, digitasi poligon/garis/titik, buffer, clip & hitung luas, analisis lokasi, unduh GeoJSON, serta asisten AI **Ka Zoni** |
| Hasil Agregat (`mce-hasil.html`) | Detail bobot AHP para pakar dan perbandingan antar tipologi |

---

## Daftar Isi

1. **Modul 1 — Konsep Dasar Perencanaan Zonasi Spasial & FOLUR**
2. **Modul 2 — Metodologi Analisis Spasial (MCE-GIS)**
3. **Modul 3 — Lima Kriteria & 16 Indikator AHP**
4. **Modul 4 — Membaca & Menggunakan Peta Zonasi**
5. **Modul 5 — Penerapan Zonasi dalam Peraturan & Perizinan**
6. **Modul 6 — Pemantauan & Evaluasi Zonasi**
- Lampiran A — Struktur 29 Indikator Peta (X1–X6)
- Lampiran B — Klasifikasi 5 Kelas Zonasi
- Lampiran C — Kunci Jawaban Kuis

---

# MODUL 1 — Konsep Dasar Perencanaan Zonasi Spasial & FOLUR

> **Durasi:** 15 menit · **Ringkasan:** Fondasi: apa itu zonasi spasial, mengapa penting, dan bagaimana FOLUR menjadi kerangkanya.

## 1.1 Apa itu zonasi spasial?

Zonasi spasial adalah pembagian suatu wilayah menjadi **zona-zona dengan arahan pemanfaatan yang berbeda**, berdasarkan karakteristik fisik, lingkungan, sosial, dan ekonomi yang melekat pada ruang tersebut. Tujuannya memastikan setiap petak lahan digunakan sesuai daya dukung dan kerentanannya — bukan sekadar berdasarkan permintaan sesaat.

Di Kabupaten Luwu, zonasi disusun untuk menjawab satu pertanyaan praktis: *"Di mana sebaiknya kegiatan pertanian, restorasi, atau perlindungan dilakukan, dan dengan syarat apa?"* Jawabannya tidak ditebak, melainkan dihitung dari data spasial yang dapat ditelusuri.

## 1.2 Mengapa zonasi penting bagi pemerintah daerah

Zonasi yang baik menjadi dasar bagi:

- **Perizinan berusaha (KKPR)** — menilai apakah lokasi yang diajukan sesuai peruntukan;
- **Revisi RTRW** — memberi basis teknis untuk penetapan pola ruang;
- **Perlindungan lahan pangan (LP2B)** — menjaga sawah produktif dari alih fungsi;
- **Mitigasi bencana** — mengarahkan pembangunan menjauh dari kawasan rawan.

> 💡 Tanpa zonasi berbasis data, keputusan ruang cenderung reaktif dan sulit dipertanggungjawabkan. Zonasi mengubahnya menjadi proses yang transparan dan dapat diaudit.

## 1.3 Kerangka FOLUR

**FOLUR** (Food Systems, Land Use, and Restoration — Sistem Pangan, Tata Guna Lahan, dan Restorasi) adalah pendekatan yang menyeimbangkan tiga kepentingan yang sering bertabrakan: **produksi pangan**, **kelestarian lingkungan**, dan **pemulihan lahan terdegradasi**.

Dalam konteks Luwu, FOLUR memfokuskan zonasi pada lima komoditas prioritas — **kakao, padi sawah, jagung, sagu, dan cengkeh** — sambil memastikan pengembangannya tidak mengorbankan kawasan bernilai konservasi tinggi maupun memperparah risiko bencana.

## 1.4 Dasar hukum dan kebijakan

Zonasi spasial berpijak pada sejumlah landasan, antara lain:

- Undang-Undang Penataan Ruang dan turunannya (RTRW, RDTR, KKPR);
- Ketentuan Daya Dukung & Daya Tampung Lingkungan Hidup (DDDTLH);
- Pedoman kesesuaian lahan pertanian (mis. Permentan terkait);
- Kerangka kerentanan iklim (IPCC AR5) dan kebijakan kebencanaan (BNPB/InaRISK).

Modul-modul berikutnya menerjemahkan landasan ini menjadi langkah analisis dan pembacaan peta yang konkret.

## ✏️ Kuis Modul 1

**1. Apa tujuan utama zonasi spasial?**
- A. Membagi wilayah secara administratif
- B. Mengarahkan pemanfaatan ruang sesuai daya dukung dan kerentanannya
- C. Menentukan batas desa
- D. Menghitung jumlah penduduk

**2. Lima komoditas prioritas FOLUR di Luwu adalah?**
- A. Kakao, padi sawah, jagung, sagu, cengkeh
- B. Padi, jagung, kedelai, tebu, kopi
- C. Sawit, karet, kakao, lada, vanili
- D. Sagu, sukun, pisang, kelapa, nilam

**3. Apa singkatan dari FOLUR?**
- A. Food, Land Use, and Restoration
- B. Forest, Ocean, Land, and Urban Resilience
- C. Food and Land Utilization Reform
- D. Future of Land Use and Restoration

**4. Berapa kelas zonasi yang digunakan dalam pelatihan ini?**
- A. 3 kelas
- B. 5 kelas
- C. 7 kelas
- D. 10 kelas

---

# MODUL 2 — Metodologi Analisis Spasial (MCE-GIS)

> **Durasi:** 15 menit · **Ringkasan:** Bagaimana banyak indikator digabung menjadi satu peta zonasi melalui evaluasi multi-kriteria.

## 2.1 Gambaran umum alur analisis

Inti penyusunan zonasi Luwu adalah **MCE-GIS** (Multi-Criteria Evaluation berbasis SIG): metode yang menggabungkan banyak lapisan indikator — masing-masing dengan bobot kepentingannya — menjadi satu peta keputusan.

Alurnya secara ringkas:

1. **Identifikasi indikator** — memilih variabel yang relevan (lereng, curah hujan, ketersediaan air, dll.);
2. **Standardisasi** — menyeragamkan setiap indikator ke skala kelas yang sebanding (1–5);
3. **Pembobotan** — menetapkan bobot tiap indikator berdasarkan kepentingan relatifnya;
4. **Agregasi** — menjumlahkan nilai berbobot menjadi indeks gabungan per lokasi;
5. **Klasifikasi** — membagi indeks menjadi 5 kelas zonasi.

## 2.2 Standardisasi: dari beragam satuan ke kelas 1–5

Indikator datang dalam satuan berbeda — derajat kemiringan, milimeter hujan, jumlah jiwa. Agar bisa dijumlahkan, semuanya diterjemahkan ke **kelas numerik 1–5** yang sebanding.

Contoh untuk **kemiringan lereng**:

| Kelas | Lereng | Kategori |
|---|---|---|
| 1 | 0–2% | Datar |
| 2 | 2–5% | Landai |
| 3 | 5–15% | Bergelombang |
| 4 | 15–40% | Curam |
| 5 | >40% | Sangat Curam |

*Inilah atribut `kelas_numeric` dan `kategori` yang akan Anda temui saat mengklik fitur pada peta interaktif.*

## 2.3 Pembobotan AHP dan agregasi

Tidak semua kriteria sama pentingnya. **Bobot** ditetapkan melalui **AHP (Analytical Hierarchy Process)** — metode perbandingan berpasangan yang melibatkan para pakar dari 4 tipologi: Akademisi, Pemerintah, Praktisi, dan Tokoh Masyarakat.

Hasil agregasi menggunakan **geometric mean (AIJ)** dengan Consistency Ratio **CR = 0,019** (sangat konsisten, di bawah ambang 0,10). Urutan bobot konstruk dari yang terpenting:

| Konstruk | Bobot | Peringkat |
|---|---|---|
| **K1** Kesesuaian Lahan | 0,271 | 🥇 1 |
| **K2** Daya Dukung Lingkungan | 0,222 | 🥈 2 |
| **K4** Nilai Konservasi | 0,195 | 🥉 3 |
| **K5** Faktor Sosial-Ekonomi | 0,157 | 4 |
| **K3** Risiko Iklim & Bencana | 0,156 | 5 |

Nilai akhir tiap lokasi dihitung sebagai **jumlah berbobot**:

```
Indeks = Σ ( kelas_indikator_i × bobot_global_i )
```

Total bobot global = **1,000**. Perbedaan persepsi antar tipologi (Akademisi vs Pemerintah vs Praktisi vs Masyarakat) ditampilkan di halaman **Hasil Agregat** untuk triangulasi.

> ℹ️ AHP dipilih karena kemampuannya mengurai masalah multi-kriteria yang kompleks menjadi perbandingan berpasangan yang lebih sederhana dan terukur.

## 2.4 Hukum minimum (limiting factor)

Khusus untuk penilaian **kesesuaian lahan**, berlaku **hukum minimum**: kelas kesesuaian sebuah satuan lahan ditentukan oleh *faktor pembatas terberat*, bukan rata-rata.

Analoginya seperti rantai — kekuatannya ditentukan mata rantai terlemah. Lahan dengan tanah subur namun lereng sangat curam tetap dinilai rendah, karena lereng menjadi pembatas dominan.

## 2.5 Anatomi penilaian zonasi (AHP)

Hasil akhir zonasi disusun dari **5 kriteria AHP** yang membawahi **16 indikator**:

| Kriteria | Bobot | Indikator |
|---|---|---|
| K1 · Kesesuaian Lahan | 0,271 | 3 indikator: Kakao, Padi, Lainnya |
| K2 · Daya Dukung Lingkungan | 0,222 | 3 indikator: DD Lahan, DD Air, Jasa Ekosistem |
| K4 · Nilai Konservasi | 0,195 | 3 indikator: Fungsi Hidrologi, Area Preservasi, Kawasan ABKT |
| K5 · Faktor Sosial-Ekonomi | 0,157 | 4 indikator: Infrastruktur, Diversifikasi, Ekonomi, Permukiman |
| K3 · Risiko Iklim & Bencana | 0,156 | 3 indikator: Banjir/Longsor, Kekeringan, Hidrometeorologi |

**CR (Consistency Ratio) = 0,019 — sangat konsisten.** K1 mendominasi dengan 27,1%, diikuti K2 22,2%.

## ✏️ Kuis Modul 2

**1. Mengapa setiap indikator distandardisasi ke kelas 1–5?**
- A. Agar terlihat rapi
- B. Agar indikator dengan satuan berbeda dapat dijumlahkan secara sebanding
- C. Untuk mengurangi jumlah data
- D. Karena diwajibkan undang-undang

**2. Menurut hukum minimum, kelas kesesuaian lahan ditentukan oleh?**
- A. Rata-rata semua faktor
- B. Faktor dengan nilai tertinggi
- C. Faktor pembatas terberat
- D. Luas lahan

**3. Berapa Consistency Ratio (CR) hasil AHP para pakar?**
- A. 0,105 — tidak konsisten
- B. 0,019 — sangat konsisten
- C. 0,500 — cukup konsisten
- D. 1,000 — sempurna

**4. Kriteria mana yang memiliki bobot tertinggi dalam AHP?**
- A. K3 Risiko Iklim & Bencana
- B. K2 Daya Dukung Lingkungan
- C. K1 Kesesuaian Lahan
- D. K5 Faktor Sosial-Ekonomi

---

# MODUL 3 — Lima Kriteria & 16 Indikator AHP

> **Durasi:** 15 menit · **Ringkasan:** Mengenal 5 kriteria K1–K5 dan 16 indikator beserta bobot hasil agregasi para pakar.

## 3.1 Struktur penilaian AHP

Seluruh penilaian zonasi Luwu dibangun dari **16 indikator** yang dikelompokkan menjadi **5 kriteria AHP** (K1–K5). Tiap kriteria mewakili satu dimensi penilaian dengan bobot hasil agregasi geometric mean dari para pakar (4 tipologi).

| Kriteria | Bobot Konstruk | Indikator | Bobot Global |
|---|---|---|---|
| **K1** Kesesuaian Lahan | 0,271 | Kesesuaian Kakao | 0,115 |
| | | Kesesuaian Padi | 0,099 |
| | | Kesesuaian Lainnya (Jagung, Sagu, Cengkeh) | 0,057 |
| **K2** Daya Dukung Lingkungan | 0,222 | Daya Dukung Lahan | 0,091 |
| | | Daya Dukung Air | 0,085 |
| | | Kinerja Jasa Ekosistem | 0,045 |
| **K3** Risiko Iklim & Bencana | 0,156 | Risiko Banjir/Longsor | 0,055 |
| | | Risiko Kekeringan | 0,051 |
| | | Risiko Hidrometeorologi | 0,050 |
| **K4** Nilai Konservasi | 0,195 | Fungsi Hidrologi | 0,106 |
| | | Area Preservasi | 0,057 |
| | | Kawasan ABKT | 0,032 |
| **K5** Faktor Sosial-Ekonomi | 0,157 | Infrastruktur | 0,066 |
| | | Diversifikasi Komoditas | 0,036 |
| | | Aktivitas Ekonomi | 0,036 |
| | | Permukiman | 0,019 |

## 3.2 Membaca bobot dan prioritas

Bobot global menunjukkan **seberapa kuat sebuah indikator menggeser hasil zonasi**. Beberapa yang menonjol:

- 🥇 **Kesesuaian Kakao (K1 — 0,115)**: bobot tertinggi — menegaskan posisi kakao sebagai komoditas prioritas utama FOLUR;
- 🥈 **Fungsi Hidrologi (K4 — 0,106)**: konservasi air sangat menentukan — daerah resapan dan DAS diberi bobot besar;
- 🥉 **Kesesuaian Padi (K1 — 0,099)**: padi sebagai komoditas pangan pokok mendapat prioritas tinggi kedua.

Di tingkat kriteria, **K1 Kesesuaian Lahan (0,271)** paling dominan, diikuti K2 Daya Dukung Lingkungan (0,222) dan K4 Nilai Konservasi (0,195).

> ℹ️ Bobot dihitung melalui AHP dengan perbandingan berpasangan (pairwise) skala Saaty 1–9. Agregasi menggunakan geometric mean — lebih robust terhadap outlier dibanding arithmetic mean.

## 3.3 Perbandingan persepsi antar tipologi

Salah satu kekuatan AHP adalah kemampuannya mengungkap **perbedaan persepsi** antar kelompok pemangku kepentingan. Para pakar terbagi dalam 4 tipologi:

| Tipologi | Jumlah | K1 | K2 | K3 | K4 | K5 |
|---|---|---|---|---|---|---|
| AKADEMISI | 4 | 0,269 | 0,229 | 0,150 | 0,189 | 0,163 |
| PEMERINTAH | 5 | 0,260 | 0,225 | 0,157 | 0,196 | 0,161 |
| PRAKTISI | 3 | 0,275 | 0,239 | 0,149 | 0,194 | 0,143 |
| MASYARAKAT | 3 | 0,278 | 0,196 | 0,171 | 0,196 | 0,159 |

Menarik: **Masyarakat** memberi bobot tertinggi pada K3 (Risiko Bencana: 0,171) — lebih tinggi dari kelompok lain. Ini mencerminkan pengalaman langsung menghadapi bencana di lapangan. Sementara **Praktisi** paling menekankan K1 (Kesesuaian Lahan: 0,275).

## ✏️ Kuis Modul 3

**1. Berapa total indikator dalam model AHP zonasi Luwu?**
- A. 29 indikator
- B. 16 indikator
- C. 5 indikator
- D. 10 indikator

**2. Indikator dengan bobot global tertinggi adalah?**
- A. Daya Dukung Air
- B. Kesesuaian Kakao
- C. Fungsi Hidrologi
- D. Infrastruktur

**3. Tipologi mana yang memberi bobot tertinggi pada Risiko Bencana (K3)?**
- A. Akademisi
- B. Pemerintah
- C. Praktisi
- D. Masyarakat

**4. Mengapa agregasi AHP menggunakan geometric mean?**
- A. Karena lebih cepat dihitung
- B. Karena lebih robust terhadap outlier
- C. Karena diwajibkan undang-undang
- D. Karena menghasilkan angka bulat

---

# MODUL 4 — Membaca & Menggunakan Peta Zonasi

> **Durasi:** 15 menit · **Ringkasan:** Praktik: simbologi, legenda, klasifikasi 5 kelas, dan interpretasi zona pada peta interaktif.

## 4.1 Anatomi peta zonasi

Peta zonasi terdiri dari beberapa komponen yang perlu dibaca bersama: **layer indikator**, **legenda** (skema warna tiap kelas), **peta dasar**, dan **info atribut** yang muncul saat sebuah fitur diklik.

Setiap poligon pada peta membawa atribut seperti `kategori`, `kelas_numeric`, `bobot`, dan `luas` (dalam hektar). Inilah data yang menjelaskan "mengapa" sebuah lokasi masuk kelas tertentu.

## 4.2 Klasifikasi lima kelas

Hasil akhir zonasi dibagi menjadi **5 kelas**, dari nilai gabungan terendah hingga tertinggi (lihat Lampiran B untuk tabel lengkap beserta warna).

**Perhatian:** makna "tinggi" bergantung pada konteks layer. Pada layer kesesuaian, kelas 5 berarti paling sesuai; pada layer kerentanan/rawan bencana, nilai tinggi justru menandakan risiko yang perlu diwaspadai. Selalu baca judul layer dan legendanya.

## 4.3 Langkah praktik membaca peta

1. **Aktifkan layer** yang ingin ditelaah dari panel Layer;
2. **Baca legenda** di bawah nama layer untuk memahami arti tiap warna;
3. **Klik sebuah fitur** untuk melihat kelas dan nilainya;
4. **Bandingkan beberapa layer** — misalnya kesesuaian kakao vs rawan bencana — untuk menilai trade-off;
5. **Catat zona prioritas** berdasarkan tujuan: budidaya, penyangga, atau perlindungan.

Praktik lanjutan di peta interaktif:

- **Digitasi & Clip** — gambar poligon (atau garis/titik dengan buffer, atau upload GeoJSON) lalu jalankan *Clip & Hitung Luas* untuk memperoleh luas per kelas di dalam area tersebut;
- **Analisis Lokasi** — klik satu titik untuk melihat kelas setiap layer aktif pada titik itu;
- **Ka Zoni** — asisten AI yang otomatis menganalisis hasil clip dan siap menjawab pertanyaan lanjutan.

> ⚠️ Selisih luas antara total klasifikasi 5 kelas dan total bab zonasi dapat terjadi karena adanya sub-zona (sempadan, cagar budaya) yang tumpang tindih secara spasial dengan zona penyangga. Ini bukan kesalahan perhitungan.

## 4.4 Desa prioritas intervensi

Fokus intervensi FOLUR diarahkan pada **12 desa prioritas**. Saat membaca peta, perhatikan bagaimana kelas zonasi pada desa-desa ini menentukan jenis kegiatan yang dianjurkan — apakah pengembangan komoditas, restorasi, atau pembatasan karena risiko.

Dua kecamatan dengan perhatian khusus pada kawasan rawan bencana (KRB) adalah **Walenrang Barat** dan **Latimojong**, dengan luas gabungan sekitar **26.470 ha**.

## ✏️ Kuis Modul 4

**1. Saat mengklik fitur peta, atribut mana yang menjelaskan kelas suatu lokasi?**
- A. Hanya nama desa
- B. `kelas_numeric` dan `kategori`
- C. Koordinat saja
- D. Tanggal pembuatan

**2. Selisih luas antara klasifikasi 5 kelas dan total zonasi terutama disebabkan oleh?**
- A. Kesalahan input data
- B. Sub-zona yang tumpang tindih dengan zona penyangga
- C. Perbedaan proyeksi peta
- D. Pembulatan luas

**3. Berapa kelas zonasi yang digunakan dalam peta interaktif?**
- A. 3 kelas
- B. 5 kelas
- C. 7 kelas
- D. 10 kelas

**4. Apa yang dimaksud dengan 'trade-off' saat membaca beberapa layer sekaligus?**
- A. Menghapus layer yang tidak penting
- B. Menimbang keuntungan dan risiko antar indikator di lokasi yang sama
- C. Memperbesar peta
- D. Membandingkan warna layer

---

# MODUL 5 — Penerapan Zonasi dalam Peraturan & Perizinan

> **Durasi:** 15 menit · **Ringkasan:** Menerjemahkan zona menjadi ketentuan kegiatan, dan kaitannya dengan KKPR serta revisi RTRW.

## 5.1 Dari peta ke aturan

Peta zonasi hanya bermakna jika diterjemahkan menjadi **ketentuan yang mengikat**. Setiap zona memerlukan rumusan: kegiatan apa yang **diperbolehkan**, **diperbolehkan bersyarat/terbatas**, dan **dilarang**.

| Arahan zona | Contoh ketentuan kegiatan |
|---|---|
| Zona budidaya prioritas | Pengembangan komoditas FOLUR diperbolehkan dengan praktik berkelanjutan |
| Zona penyangga | Kegiatan terbatas; wajib kajian dampak lingkungan |
| Zona perlindungan | Pembangunan dilarang; diarahkan untuk konservasi/restorasi |
| Sempadan / cagar budaya | Mengikuti ketentuan khusus yang berlaku |

## 5.2 Kaitan dengan KKPR

**KKPR** (Kesesuaian Kegiatan Pemanfaatan Ruang) adalah gerbang perizinan berusaha. Zonasi memberi dasar teknis untuk menilai permohonan: jika lokasi yang diajukan berada pada zona yang tidak sesuai peruntukan, permohonan dapat ditolak atau diberi syarat.

Alur sederhananya:

```
Permohonan → cek lokasi terhadap peta zonasi → tentukan kesesuaian
           → terbitkan rekomendasi (sesuai / bersyarat / tidak sesuai)
```

## 5.3 Mendukung revisi RTRW

Hasil zonasi menjadi masukan teknis bagi **revisi RTRW**, khususnya dalam penetapan pola ruang. Karena disusun dari data yang dapat ditelusuri, zonasi memperkuat argumentasi penetapan kawasan lindung, kawasan budidaya, dan lahan pangan berkelanjutan (**LP2B** — Lahan Pertanian Pangan Berkelanjutan).

> ⚖️ Catatan: angka luas zona yang rinci hanya dirujuk dari bagian penetapan resmi (Bab 5 laporan), sementara bagian lain berfungsi sebagai pratinjau spasial. Konsistensi rujukan ini penting saat dokumen masuk proses legal.

## ✏️ Kuis Modul 5

**1. Apa fungsi KKPR dalam kaitannya dengan zonasi?**
- A. Menghitung pajak lahan
- B. Menilai kesesuaian lokasi kegiatan terhadap peruntukan ruang
- C. Menetapkan harga tanah
- D. Membuat peta dasar

**2. Tiga kategori ketentuan kegiatan dalam zonasi adalah?**
- A. Murah, sedang, mahal
- B. Diperbolehkan, terbatas/bersyarat, dilarang
- C. Pagi, siang, malam
- D. Desa, kecamatan, kabupaten

**3. Apa hubungan zonasi dengan revisi RTRW?**
- A. Tidak ada hubungan
- B. Zonasi menjadi masukan teknis penetapan pola ruang
- C. Zonasi menggantikan RTRW
- D. RTRW membatalkan zonasi

**4. Apa kepanjangan LP2B dalam konteks penataan ruang?**
- A. Laporan Pembangunan 2 Bulan
- B. Lahan Pertanian Pangan Berkelanjutan
- C. Lembaga Penilaian 2 Bidang
- D. Lingkup Perencanaan 2 Barat

---

# MODUL 6 — Pemantauan & Evaluasi Zonasi

> **Durasi:** 15 menit · **Ringkasan:** Konsep alat bantu keputusan, indikator kepatuhan, dan pemutakhiran data berbasis InaRISK/BPBD.

## 6.1 Mengapa pemantauan diperlukan

Zonasi bukan dokumen sekali jadi. Kondisi lapangan berubah — tutupan lahan bergeser, infrastruktur bertambah, risiko bencana berevolusi. **Pemantauan dan evaluasi (M&E)** menjaga agar zonasi tetap relevan dan ditaati.

## 6.2 Konsep alat bantu pengambilan keputusan

Alat bantu (decision support tool) yang dirancang berfungsi memantau:

- **Kepatuhan zonasi** — apakah pemanfaatan ruang sesuai arahan zona;
- **Perubahan tutupan/penggunaan lahan** dari waktu ke waktu;
- **Perkembangan risiko bencana** dengan merujuk data **InaRISK/BPBD**.

Secara konseptual, alat ini menyajikan indikator kunci dalam bentuk ringkas (dashboard) sehingga pengambil keputusan dapat menindaklanjuti penyimpangan secara cepat.

## 6.3 Pemutakhiran data dan siklus evaluasi

Indikator kebencanaan kini merujuk pada **peta rawan bencana BPBD/InaRISK**, bukan sekadar frekuensi kejadian. Layer ini perlu diperbarui berkala agar penilaian tetap mencerminkan kondisi terkini.

Siklus evaluasi yang sehat:

```
Kumpulkan data terbaru → bandingkan dengan zonasi → identifikasi penyimpangan
                       → rekomendasi tindak lanjut → perbarui zonasi bila perlu
```

> 🔁 Luwu tergolong risiko tinggi untuk banjir, banjir bandang, cuaca ekstrem, dan tanah longsor. Karena itu, pemutakhiran layer kebencanaan menjadi bagian rutin yang tidak bisa diabaikan.

## ✏️ Kuis Modul 6

**1. Indikator kebencanaan kini dirujuk dari sumber mana?**
- A. Frekuensi kejadian saja
- B. BPBD dan InaRISK
- C. Perkiraan warga
- D. Data curah hujan tahunan

**2. Mengapa zonasi perlu dipantau dan dievaluasi berkala?**
- A. Agar dokumen terlihat baru
- B. Karena kondisi lapangan dan risiko berubah dari waktu ke waktu
- C. Untuk menambah jumlah halaman laporan
- D. Karena diminta vendor

**3. Apa yang dimaksud dengan siklus M&E zonasi?**
- A. Menggambar ulang peta setiap minggu
- B. Kumpulkan data → bandingkan → identifikasi penyimpangan → rekomendasi → perbarui
- C. Menghapus data lama
- D. Mengganti semua indikator

**4. Jenis bencana apa yang tergolong risiko tinggi di Kabupaten Luwu?**
- A. Tsunami dan gempa bumi
- B. Banjir, banjir bandang, cuaca ekstrem, dan tanah longsor
- C. Kebakaran hutan saja
- D. Kekeringan saja

---

# LAMPIRAN A — Struktur 29 Indikator Peta (X1–X6)

Peta interaktif menyajikan **29 layer indikator** dalam 6 kelompok. Angka dalam kurung adalah bobot kelompok; kolom bobot adalah bobot global tiap indikator.

### X1 · Kerentanan Fisik (0,136)

| Kode | Indikator | Bobot |
|---|---|---|
| X1.1 | Kemiringan Lereng | 0,001 |
| X1.2 | Curah Hujan | 0,037 |
| X1.3 | Rawan Bencana | 0,051 |
| X1.4 | Kenaikan Muka Laut | 0,052 |

### X2 · Kerentanan Sosial-Ekonomi (0,080)

| Kode | Indikator | Bobot |
|---|---|---|
| X2.1 | Kepadatan Penduduk | 0,011 |
| X2.2 | Penduduk Miskin | 0,005 |
| X2.3 | Rasio Ketergantungan | 0,027 |
| X2.4 | Akses Kesehatan | 0,034 |
| X2.5 | Diversifikasi Mata Pencaharian | 0,008 |

### X3 · Daya Dukung Lingkungan Hidup (0,258)

| Kode | Indikator | Bobot |
|---|---|---|
| X3.1 | Tutupan Vegetasi | 0,080 |
| X3.2 | Ketersediaan Air | 0,103 |
| X3.3 | Daya Tampung Lahan | 0,022 |
| X3.4 | Ruang Terbuka Hijau | 0,017 |
| X3.5 | Kualitas Air Sungai | 0,074 |

### X4 · Kesesuaian Lahan (0,138)

| Kode | Indikator | Bobot |
|---|---|---|
| X4.1 | Kemampuan Lahan | 0,020 |
| X4.2 | Penggunaan Lahan Eksisting | 0,005 |
| X4.3 | Kedalaman Tanah | 0,039 |
| X4.4 | Infrastruktur & Aksesibilitas | 0,083 |
| X4.5 | Jarak Pusat Kegiatan | 0,005 |

### X5 · Kapasitas Adaptasi (0,167)

| Kode | Indikator | Bobot |
|---|---|---|
| X5.1 | Tingkat Pendidikan | 0,028 |
| X5.2 | Akses Informasi Spasial | 0,027 |
| X5.3 | Kelembagaan Lokal | 0,076 |
| X5.4 | Kapasitas Fiskal | 0,002 |
| X5.5 | Infrastruktur Mitigasi | 0,065 |

### X6 · Kesesuaian Komoditas FOLUR (0,120)

| Kode | Indikator | Bobot |
|---|---|---|
| X6.1 | Kesesuaian Lahan Kakao | 0,031 |
| X6.2 | Kesesuaian Lahan Padi | 0,008 |
| X6.3 | Soil Fertility Index | 0,025 |
| X6.4 | Status Daya Dukung Lahan | 0,047 |
| X6.5 | Status Daya Dukung Air | 0,011 |
| X6.6 | Status NKT/SKT | 0,008 |

---

# LAMPIRAN B — Klasifikasi 5 Kelas Zonasi

| Kelas | Nama | Warna | Deskripsi |
|---|---|---|---|
| 1 | Sangat Rendah | 🟥 `#d73027` | Zona dengan nilai gabungan terendah — prioritas perlindungan / pembatasan pemanfaatan |
| 2 | Rendah | 🟧 `#fc8d59` | Pemanfaatan terbatas dengan syarat ketat |
| 3 | Sedang | 🟨 `#fee08b` | Zona penyangga / transisi, perlu kajian tambahan |
| 4 | Tinggi | 🟩 `#91cf60` | Sesuai untuk pengembangan terkendali |
| 5 | Sangat Tinggi | 🟩 `#1a9850` | Paling sesuai untuk intervensi / budidaya prioritas |

---

# LAMPIRAN C — Kunci Jawaban Kuis

> Kerjakan seluruh kuis terlebih dahulu sebelum membuka halaman ini.

| Modul | No. 1 | No. 2 | No. 3 | No. 4 |
|---|---|---|---|---|
| Modul 1 | B | A | A | B |
| Modul 2 | B | C | B | C |
| Modul 3 | B | B | D | B |
| Modul 4 | B | B | B | B |
| Modul 5 | B | B | B | B |
| Modul 6 | B | B | B | B |

---

*Dokumen ini merupakan bahan pegangan peserta Pelatihan Perencanaan Zonasi Spasial Kabupaten Luwu — Program FOLUR. Materi digital, kuis daring, peta interaktif, dan sertifikat tersedia di platform pelatihan.*
