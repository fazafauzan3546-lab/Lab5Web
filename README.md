# Praktikum Web - JavaScript Dasar

## Tujuan
- Memahami dasar-dasar sintaks JavaScript dan cara mengintegrasikannya dengan HTML.
- Menggunakan *pop-up dialog* bawaan browser (`prompt()` dan `alert()`) untuk interaksi pengguna.
- Memahami dan menerapkan struktur logika percabangan (`if-else`, `switch-case`).
- Melakukan manipulasi DOM (*Document Object Model*) untuk mengubah konten teks dan gaya (*style*) CSS secara dinamis.
- Mengambil nilai input dari form HTML, memproses perhitungan logika matematika, dan menampilkannya kembali pada antarmuka web.

## Langkah Kerja
1. **Membuat Struktur HTML:** Menulis kerangka halaman menggunakan HTML (`index.html`) yang mencakup elemen teks, tombol, checkbox menu makanan, dan form nilai.
2. **Menghubungkan JavaScript:** Menghubungkan file HTML dengan script eksternal atau menuliskannya di dalam tag `<script>`.
3. **Menulis Logika Pemrograman:** Menggunakan JavaScript untuk memproses input dari pengguna (seperti perhitungan ganjil/genap dan kalkulasi nilai mahasiswa).
4. **Manipulasi DOM:** Menggunakan fungsi seperti `document.getElementById` untuk merubah warna latar belakang, membaca nilai form, dan menampilkan output teks.
5. **Pengujian:** Menguji fungsionalitas dengan berbagai input pada browser untuk memastikan semua logika berjalan tanpa *error*.

## Cara Menjalankan
1. Buka folder proyek ini di komputer Anda.
2. Buka file `index.html` dengan cara klik dua kali (otomatis terbuka di browser default) atau *drag and drop* ke *browser* (Chrome, Firefox, Edge, dll).
3. Untuk melihat perubahan secara langsung (*real-time*) saat coding, Anda bisa menggunakan ekstensi **Live Server** di VS Code.
4. Uji coba fungsionalitas tombol, masukkan nilai pada form, dan amati perubahan di layar.

---

## Hasil Latihan

### 1. Pengenalan JavaScript (Ubah Teks dengan DOM)
Latihan ini memanipulasi elemen HTML untuk menampilkan teks "Hello World" saat halaman dimuat.
<br>
![Hello World](Screenshot%20(85).png)

### 2. Interaksi Pengguna (Prompt dan Validasi)
Penggunaan dialog `prompt()` untuk meminta masukan secara langsung dari pengguna.
- **Meminta Input Nama:**
  <br>
  ![Prompt Nama](Screenshot%20(86).png)
- **Meminta Input Nilai (0-100):**
  <br>
  ![Prompt Nilai](Screenshot%20(87).png)
- **Penggunaan Switch Case (Input angka 1-5):**
  <br>
  ![Prompt Angka](Screenshot%20(88).png)

### 3. Manipulasi Antarmuka dan Pemilihan Menu
Menampilkan tombol-tombol interaktif untuk memeriksa bilangan ganjil/genap, daftar menu makanan dengan checkbox, serta merubah warna latar belakang secara dinamis.
- **Tampilan Awal dan Menu Makanan:**
  <br>
  ![Tampilan UI Awal](Screenshot%20(89).png)
- **Perubahan Latar Belakang Hijau:**
  <br>
  ![Latar Hijau](Screenshot%20(90).png)
- **Perubahan Latar Belakang Kuning:**
  <br>
  ![Latar Kuning](Screenshot%20(91).png)

### 4. Aplikasi Perhitungan Nilai Akhir (Kalkulator Nilai)
Aplikasi mini berupa form yang mengambil nilai **Tugas (30%)**, **UTS (30%)**, dan **UAS (40%)**. Program kemudian menghitung Nilai Akhir, menentukan Predikat (A/B/C/D/E), dan menampilkan Status Kelulusan secara langsung di halaman HTML.
<br>
![Kalkulator Nilai Mahasiswa](Screenshot%20(92).png)

<img width="1366" height="768" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/7497bfb9-c037-4b15-97e4-cf2b236617af" />
<img width="1366" height="768" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/605f3d2f-5adb-4ba9-8b32-3f636d213dd7" />
<img width="1366" height="768" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/fc167e9a-0ff7-4ca8-bfa3-25885bddd553" />
<img width="1366" height="768" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/fb1fe089-6dda-4374-bb7a-f9c6d895c94a" />
<img width="1366" height="768" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/84aa46bd-d62f-416f-b222-0186710f4a1a" />
<img width="1366" height="768" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/7c5e108e-577e-4eb4-81c2-7990f0a80b4b" />
<img width="1366" height="768" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/c42a6e21-6963-46e1-8061-ab81faafffd2" />
<img width="1366" height="768" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/8b20baf7-88ce-4225-afc8-3cb4e3bad75c" />
