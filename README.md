# BinaryLens Data Recovery

**BinaryLens Data Recovery** adalah aplikasi desktop untuk memulihkan file yang hilang atau terhapus dari media penyimpanan seperti hard disk, flashdisk, dan drive eksternal. Aplikasi ini memindai sektor-sektor disk secara langsung (low-level) untuk menemukan file berdasarkan signature/header, kemudian mengembalikannya ke folder yang ditentukan pengguna. Aplikasi ini cocok untuk pengguna rumahan maupun profesional IT yang membutuhkan alat pemulihan data cepat dan ringan.

---

## Fitur Utama

- **Pemindaian Disk Cepat** – Memindai drive (FAT/NTFS) sektor per sektor dengan algoritma optimasi.
- **Dukungan Berbagai Kategori File** – Pilih berdasarkan tipe: Gambar, Musik, Video, Dokumen, atau Semua File.
- **Live Progress & Estimasi Waktu** – Tampilkan progres pemindaian, kecepatan baca (MB/s), dan perkiraan waktu selesai.
- **Pemulihan File Terpilih** – Centang file yang ingin dipulihkan, tentukan folder tujuan, dan proses di background.
- **Pencarian Real-time** – Filter file yang ditemukan berdasarkan nama atau ekstensi.
- **Simpan & Muat Hasil Scan** – Ekspor daftar file ke file log (format CSV) dan impor kembali untuk analisis nanti.
- **Seleksi Cerdas** – Pilih semua, hapus pilihan, atau pilih berdasarkan kelompok ekstensi (Gambar, Musik, dll.) melalui menu konteks.

---

## Tangkapan Layar

<div align="center">
  <img src="./assets/BinaryLens Data Recovery.png" alt="BinaryLens Data Recovery" width="600" height="500">
</div>

---

## Persyaratan Sistem

- **Sistem Operasi:** Windows 7/8/10/11 (32-bit atau 64-bit)
- **Processor:** Intel/AMD 1 GHz atau lebih
- **RAM:** Minimal 512 MB (disarankan 2 GB)
- **Penyimpanan:** 50 MB ruang kosong untuk aplikasi, plus ruang untuk hasil pemulihan
- **Hak Akses:** Administrator (diperlukan untuk membaca sektor disk mentah)

---

## Cara Instalasi / Menjalankan

1. **Unduh** file rilis terbaru dari [halaman Releases](https://github.com/MichaelJorky/BinaryLens-Data-Recovery/releases).
2. **Ekstrak** arsip ZIP ke folder pilihan Anda.
3. Jalankan `BinaryLens.Recovery.exe` sebagai **Administrator** (klik kanan → *Run as administrator*).
4. Jika muncul peringatan dari Windows Defender, pilih **Run anyway** (aplikasi ini aman).

> **Catatan:** Tidak diperlukan instalasi tambahan; aplikasi bersifat *portable*.

---

## Cara Penggunaan

### 1. Memilih Drive dan Kategori
- Pilih drive yang akan dipindai (misal `C:`, `D:`, `F:`) dari combobox **Drive**.
- Pilih kategori file dari combobox **Kategori** (misal *Gambar*, *Musik*, atau *Semua File*).

### 2. Memulai Pemindaian
- Klik tombol **Mulai Scan**.
- Proses pemindaian akan berjalan di latar belakang. Anda dapat melihat progres, kecepatan, dan jumlah file ditemukan.
- Tekan **Stop** kapan saja untuk menghentikan pemindaian.

### 3. Memilih File yang Akan Dipulihkan
- Setelah pemindaian selesai, file-file yang ditemukan akan ditampilkan dalam daftar.
- Centang file yang ingin dipulihkan. Gunakan tombol **Pilih Semua**, **Hapus Pilihan**, atau menu konteks (klik kanan) untuk memilih berdasarkan tipe.
- Gunakan kotak **Pencarian** untuk memfilter file berdasarkan nama atau ekstensi.

### 4. Memulihkan File
- Klik tombol **Pulihkan** (atau *Restore*).
- Pilih folder tujuan penyimpanan (pastikan folder tersebut bukan drive yang sama dengan sumber untuk menghindari penimpaan data).
- Proses pemulihan akan berjalan di latar belakang. Setelah selesai, folder tujuan akan terbuka secara otomatis.

### 5. Menyimpan/Memuat Hasil Scan
- Klik **Simpan Hasil** untuk menyimpan daftar file ke file `.log` (format CSV).
- Klik **Muat Hasil** untuk memuat kembali file log yang pernah disimpan.

---

## Kontribusi

Kontribusi sangat diterima! Jika Anda ingin melaporkan bug, mengusulkan fitur baru, atau meningkatkan kode, silakan:

1. **Fork** repositori ini.
2. Buat branch baru (`git checkout -b fitur-keren`).
3. Lakukan perubahan dan commit (`git commit -am 'Menambahkan fitur X'`).
4. Push ke branch (`git push origin fitur-keren`).
5. Buat **Pull Request**.

---

## Lisensi

Proyek ini dilisensikan di bawah **MIT License** – silakan lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

---

## Dukungan & Kontak

- **Repositori GitHub:** [https://github.com/MichaelJorky/BinaryLens-Data-Recovery](https://github.com/MichaelJorky/BinaryLens-Data-Recovery)
- **Dukungan (Saweria):** [https://saweria.co/teknoxpert](https://saweria.co/teknoxpert)
- **Channel YouTube:** [TeknoXpert](https://www.youtube.com/channel/UCubtSerA3uEv9IGVWOlgkcQ?sub_confirmation=1)
- **Laporkan Masalah:** [GitHub Issues](https://github.com/MichaelJorky/BinaryLens-Data-Recovery/issues)

---

## Peringatan Penting

- Gunakan aplikasi ini hanya pada drive yang **bukan drive sistem** (kecuali Anda tahu persis risiko yang mungkin terjadi).
- Selalu **cadangkan data penting** sebelum melakukan pemulihan ke drive yang sama.
- Penulis tidak bertanggung jawab atas kerusakan data akibat penggunaan yang tidak tepat.

**BinaryLens Data Recovery** dikembangkan dengan ❤️ oleh **TeknoXpert** untuk membantu masyarakat memulihkan data berharga mereka.
