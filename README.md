# LaTeX Template Laporan TA Bentuk 2 - Capstone

Template LaTeX laporan Tugas Akhir (TA) untuk bentuk Capstone. Template ini sudah disiapkan sebagai struktur proyek langsung, bukan sebagai ZIP di dalam ZIP. Seluruh gambar, konfigurasi, dan bab dapat digunakan segera setelah dipindahkan ke editor LaTeX atau Overleaf.

## Struktur proyek

- `thesis.tex` - file utama yang harus dijadikan dokumen utama.
- `config/` - konfigurasi gaya dan informasi laporan.
- `chapters/` - isi bab, abstrak, lembar pengesahan, lampiran, dan bagian laporan.
- `figure/` - gambar, logo, grafik, dan aset ilustrasi.

## Cara menggunakan template ini di Overleaf

### Metode 1: Impor langsung dari GitHub

1. Masuk ke [Overleaf](https://www.overleaf.com).
2. Pilih **New Project**.
3. Pilih **Import from GitHub**.
4. Hubungkan akun GitHub Anda jika diminta, lalu pilih repository ini.
5. Tunggu proses impor selesai.
6. Buka `thesis.tex` dan pilih **Recompile**.

Gunakan metode ini agar pembaruan repository dapat ditarik kembali ke Overleaf melalui sinkronisasi GitHub.

### Metode 2: Unggah sebagai proyek Overleaf

1. Pada halaman GitHub repository ini, pilih tombol **Code**.
2. Pilih **Download ZIP**.
3. Ekstrak ZIP hasil unduhan GitHub sehingga isi repositori tersedia seperti `thesis.tex`, `config/`, `chapters/`, dan `figure/`.
4. Masuk ke Overleaf, lalu pilih **New Project**.
5. Pilih **Upload Project**.
6. Buat ZIP baru dari isi yang diekstrak. Pastikan `thesis.tex` berada langsung di dalam ZIP, bukan berada di dalam folder lain.
7. Unggah ZIP tersebut ke Overleaf.

Contoh struktur yang benar pada hasil ZIP Overleaf:

```text
thesis.tex
config/
chapters/
figure/
README.md
```

Setelah proyek terbuka di Overleaf:

1. Buka `thesis.tex`.
2. Pilih **Menu** di kiri atas.
3. Pastikan **Main document** adalah `thesis.tex`.
4. Pilih **Recompile** untuk membangun dokumen PDF.

## Penyesuaian awal

1. Perbarui identitas dan data laporan pada `config/informations.tex`.
2. Perbarui konten sampul pada `chapters/cover.tex`.
3. Isi atau edit isi bab pada folder `chapters/`.
4. Tambahkan gambar baru ke folder `figure/` dan panggil gambar tersebut dari file LaTeX.

## Compile menggunakan editor lokal

Template dapat dikompilasi dengan TeX Live, MiKTeX, atau TeXstudio. Gunakan `thesis.tex` sebagai file utama, lalu jalankan kompilasi `pdfLaTeX` atau `XeLaTeX` sesuai konfigurasi editor.
