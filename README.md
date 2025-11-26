# Tugas Akhir: Peramalan Curah Hujan dengan Pembobotan Deret Waktu Berbasis Spatio Temporal

## Deskripsi
Dokumen LaTeX untuk proposal tugas akhir dengan judul "Peramalan Curah Hujan dengan Pembobotan Deret Waktu Berbasis Spatio Temporal" pada Program Studi Sarjana Sains Data, Universitas Telkom Surabaya.

## Struktur Project
```
├── main.tex                    # File utama dokumen
├── preamble.tex               # Konfigurasi package dan style
├── components/                # Komponen halaman awal
│   ├── Cover.tex             # Halaman cover
│   ├── Lembar-Persetujuan.tex # Lembar persetujuan
│   └── Lembar-Orisinalitas.tex # Lembar pernyataan orisinalitas
├── chapters/                  # Bab-bab dokumen (kosong)
├── sections/                  # Bagian-bagian dokumen (kosong)
├── appendices/               # Lampiran (kosong)
├── tables/                   # Tabel (kosong)
├── images/                   # Gambar dan logo
│   ├── Tel-U-Logo.png       # Logo Universitas Telkom
│   └── calis.jpg            # Foto mahasiswa
└── .gitignore               # File yang diabaikan Git
```

## Fitur
- ✅ **Tanggal Dinamis** - Otomatis update sesuai tanggal kompilasi
- ✅ **Format Indonesia** - Menggunakan bahasa Indonesia dengan babel
- ✅ **Layout Responsif** - Margin dan spacing yang sesuai standar
- ✅ **Font Modern** - Menggunakan titlesec untuk formatting yang konsisten
- ✅ **Hyperlink** - Bookmark dan navigasi PDF yang interaktif

## Requirements
### LaTeX Packages
- `babel` (indonesian)
- `titlesec`
- `geometry`
- `graphicx`
- `hyperref`
- `fancyhdr`
- Dan lainnya (lihat `preamble.tex`)

### Software
- **MiKTeX** atau **TeX Live**
- **LaTeX Editor** (TeXstudio, Overleaf, VS Code dengan LaTeX Workshop)

## Cara Kompilasi
1. Pastikan semua package LaTeX terinstall
2. Compile file `main.tex`:
   ```bash
   pdflatex main.tex
   ```
   Atau gunakan editor LaTeX favorit Anda

## Konfigurasi
Edit data di `preamble.tex` bagian "DATA MAHASISWA DAN DOKUMEN":
- Nama mahasiswa
- NIM
- Data pembimbing
- Judul tugas akhir
- Dan informasi lainnya

## Output
File PDF akan dihasilkan dengan nama `main.pdf` berisi:
- Halaman cover
- Lembar persetujuan
- Lembar pernyataan orisinalitas

## Kontributor
**Calista Ghea Ardhani** - 1206220010  
Program Studi Sarjana Sains Data  
Universitas Telkom Surabaya

## Lisensi
Dokumen ini dibuat untuk keperluan akademik Universitas Telkom.