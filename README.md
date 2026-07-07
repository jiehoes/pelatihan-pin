# Pelatihan Perencanaan Zonasi Spasial

> Program **FOLUR UNDP** — WebGIS Interaktif + Modul Pembelajaran

Website pelatihan penguatan kapasitas **Perencanaan Zonasi Spasial** untuk level Kabupaten. Menampilkan 30+ layer indikator spasial hasil agregasi AHP (Analytical Hierarchy Process), dengan AI assistant **Ka Zoni** untuk analisis spasial.

## Halaman

| Halaman | Deskripsi |
|---|---|
| `/` (`index.html`) [pelatihan-zonasi.diffa.net](https://pelatihan-zonasi.diffa.net) | Beranda — pengantar pelatihan, alur belajar, sasaran peserta |
| `/modul` (`modul.html`) [pelatihan-zonasi.diffa.net/modul](https://pelatihan-zonasi.diffa.net/modul) | Pusat pembelajaran — 6 modul, kuis interaktif, progres tracking |
| `/map` (`map.html`) [pelatihan-zonasi.diffa.net/map](https://pelatihan-zonasi.diffa.net/map) | **WebGIS interaktif** — MapLibre GL JS, clip & hitung luas, Ka Zoni AI |

> **Sumber Layer Peta Interaktif:** Menggunakan Indikator MCE-SEM/PLS-GIS (Metode evaluasi penapisan jumlah indikator) karena peta berbasis vector yang relatif bermanfaat untuk kegiatan simulasi dibandingkan dengan indikator MCE-AHP-GIS yang berbasiskan index (raster/vector).

## Fitur Peta Interaktif (`/map`)

- **30+ layer GeoJSON tematik** — 6 kelompok indikator (X1–X6) dengan bobot AHP
- **Clip & Hitung Luas** — gambar poligon / upload GeoJSON, hitung luas per kelas
- **Analisis Lokasi** — klik titik, dapatkan kelas dari semua layer aktif
- **Digitasi & Upload** — poligon, garis (ukur panjang), titik + buffer
- **Ka Zoni AI Assistant** — chat dengan Llama 3.2 3B, analisis otomatis hasil clip
- **4 Basemap** — OSM Streets, Satellite (ESRI), Carto Light, Dark Mode
- **Download GeoJSON** — ekspor layer aktif (disabled)
- **Upload Zip Shapefile** — panel layers paling bawah

## Modul Pelatihan

1. **Konsep Dasar Perencanaan Zonasi Spasial** — Fondasi: definisi, urgensi, dasar hukum
2. **Metodologi Analisis Spasial (MCE-GIS)** — Standardisasi, pembobotan, agregasi
3. **Enam Kelompok Indikator Spasial (X1–X6)** — 30 indikator, bobot, kerangka IPCC AR5
4. **Membaca & Menggunakan Peta Zonasi** — Simbologi, legenda, klasifikasi 5 kelas
5. **Penerapan Zonasi dalam Peraturan & Perizinan** — KKPR, revisi RTRW
6. **Pemantauan & Evaluasi Zonasi** — M&E, InaRISK/BPBD, siklus pemutakhiran

## Tech Stack

| Layer | Teknologi |
|-------|-----------|
| **Frontend** | HTML5, Tailwind CSS (CDN), MapLibre GL JS 3.6, Turf.js 6, Vanilla JS |
| **Backend** | Cloudflare Worker (`src/index.js`) |
| **Database** | Cloudflare D1 (`ahp-zonasi-db`) — 3 tabel (pakar, bobot, pairwise) |
| **Storage** | Cloudflare R2 (`zonasi-geojson`) — file GeoJSON |
| **AI** | Cloudflare Workers AI — Llama 3.2 3B (Ka Zoni) |
| **Deploy** | `wrangler deploy` — static assets + API dalam satu worker |

## Data Simulasi

File ZIP shapefile untuk latihan upload dan clip pada peta interaktif. Peserta bisa mendownload lalu meng-upload ke peta melalui tombol **Upload** di panel digitasi.

| File | Deskripsi | Download |
|------|-----------|----------|
| `Batas_Kab.zip` | Batas administrasi Kabupaten | [⬇ Download](https://github.com/jiehoes/pelatihan-pin/raw/main/download/Batas_Kab.zip) |
| `das_suso_suli.zip` | DAS Suso Suli | [⬇ Download](https://github.com/jiehoes/pelatihan-pin/raw/main/download/das_suso_suli.zip) |
| `rbi10k_kabluwu_desa.zip` | RBI 10K Kabupaten Luwu — batas desa | [⬇ Download](https://github.com/jiehoes/pelatihan-pin/raw/main/download/rbi10k_kabluwu_desa.zip) |

## PIN Kuis

| Modul | PIN |
|---|---|
| Modul 1 — Konsep Dasar Perencanaan Zonasi Spasial | **4827** |
| Modul 2 — Metodologi Analisis Spasial (MCE-GIS) | **7391** |
| Modul 3 — Enam Kelompok Indikator Spasial | **1563** |
| Modul 4 — Membaca & Menggunakan Peta Zonasi | **9045** |
| Modul 5 — Penerapan Zonasi dalam Peraturan & Perizinan | **6182** |
| Modul 6 — Pemantauan & Evaluasi Zonasi | **2750** |

### Reset Progres

| Fungsi | PIN |
|---|---|
| Reset Progres Belajar | **1234** |
