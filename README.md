Berikut adalah versi dokumentasi yang diubah dengan bahasa yang berbeda:

---

Alat Enkripsi dan Steganografi

Repositori ini menyediakan berbagai alat untuk enkripsi dan steganografi menggunakan Python dengan antarmuka grafis (GUI). Ada tiga alat utama yang dapat digunakan dalam proyek ini:

1. Caesar Cipher: Alat untuk enkripsi dan dekripsi menggunakan metode Caesar Cipher.
2.DES Encryption/Decryption*: Alat untuk enkripsi dan dekripsi dengan algoritma DES (Data Encryption Standard).
3. Steganografi: Alat untuk menyembunyikan dan mengungkapkan pesan dalam gambar menggunakan teknik steganografi berbasis LSB (Least Significant Bit).

Fitur Utama

 Caesar Cipher:
- Menyediakan kemampuan untuk mengenkripsi dan mendekripsi pesan dengan menggunakan algoritma Caesar Cipher.
- Pengguna dapat mengatur nilai pergeseran (shift) antara 1 hingga 25.

 DES Encryption/Decryption:
- Mendukung enkripsi dan dekripsi pesan menggunakan algoritma DES.
- Enkripsi dilakukan menggunakan kunci yang terdiri dari 8 karakter.

 Steganografi:
- Menyembunyikan pesan dalam gambar berformat PNG dan JPG.
- Menampilkan pesan yang disembunyikan dalam gambar yang telah dipilih.

 Panduan Instalasi

 Persyaratan Sistem
Pastikan Python versi 3.x (misalnya 3.10.11) sudah terinstal di sistem Anda. Selain itu, beberapa pustaka tambahan diperlukan agar alat-alat ini dapat berfungsi dengan baik, yaitu:

- tkinter: Untuk membuat antarmuka grafis pengguna (GUI).
- pycryptodome: Untuk enkripsi menggunakan algoritma DES.
- stegano: Untuk menyembunyikan dan menampilkan pesan dalam gambar.

 Instalasi Dependensi
1. Pertama, clone repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com/username/encryption-and-steganography-tools.git
   cd encryption-and-steganography-tools
   ```

2. Instal semua dependensi yang diperlukan dengan menggunakan pip:
   ```bash
   pip install -r requirements.txt
   ```

Jika tidak ada file `requirements.txt`, Anda dapat menginstal pustaka yang dibutuhkan secara manual:
   ```bash
   pip install tkinter pycryptodome stegano
   ```

 Cara Menggunakan

 Caesar Cipher
1. Jalankan script `caesarGui.py`.
2. Masukkan pesan yang ingin dienkripsi.
3. Tentukan nilai pergeseran (shift) antara 1 hingga 25.
4. Program akan menampilkan hasil enkripsi dan dekripsi pesan yang telah dimasukkan.

 DES Encryption/Decryption
1. Jalankan script `desGui.py`.
2. Pilih tab Enkripsi untuk mengenkripsi teks dan tab Dekripsi untuk mendekripsi teks.
3. Masukkan teks yang ingin dienkripsi dan key 8 karakter untuk proses enkripsi.
4. Program akan menampilkan hasil enkripsi dan dekripsi berdasarkan input yang Anda berikan.

 Steganografi
1. Jalankan script `steganoGui.py`.
2. Masukkan pesan yang ingin Anda sembunyikan dalam gambar.
3. Pilih gambar (format PNG atau JPG) yang akan digunakan untuk menyembunyikan pesan.
4. Tentukan lokasi untuk menyimpan gambar yang telah disisipi pesan.
5. Untuk melihat pesan yang disembunyikan, pilih tab Tampilkan Pesan dan pilih gambar yang berisi pesan tersembunyi.



