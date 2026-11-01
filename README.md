# Katalog Karya (Latihan P10)

Kode latihan debugging Tugas P10 Praktikum Pemrograman Visual (TB033109). Bug yang diperbaiki: G1 (path logo), G2 (class row pada #galeri), G3 (selektor filter), G4 (jumlah hasil saringan), G6 (pencarian huruf besar-kecil). G5 dikerjakan tapi tidak sempat saya masukkan ke git.

## Cara menjalankan
Buka `index.html` (Live Server). Butuh internet untuk CDN Bootstrap 5.3.3.

## Catatan Riwayat Git
G1 sampai G4 saya perbaiki dan commit langsung di branch utama sebelum saya memakai cabang `fix/katalog`, sehingga commit pertama sudah berisi perbaikan (G1), bukan kode asli LAMPIRAN. Folder `assets/` dan path logo dibereskan dalam commit perbaikan G1, bukan commit `chore:` terpisah. G6 dikerjakan di cabang `fix/katalog` lalu digabung ke branch utama dengan `git merge --no-ff`, bersama commit dokumentasi.

## Catatan Penggunaan AI
- Langkah debugging dan perintah Git dibantu Claude (Anthropic).
- Analisis penyebab dan DEBUG_LOG.md ditulis sendiri.