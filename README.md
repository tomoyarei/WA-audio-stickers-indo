<p align="center"><img src="extension/icons/icono-128.png" width="96" alt=""></p>

<h1 align="center">Stiker dengan Suara</h1>

<p align="center">Ubah video, gambar, atau GIF menjadi <b>stiker bersuara</b> dan kirim lewat <b>WhatsApp Web</b>.<br>Semuanya diproses di browser Anda: tidak ada yang diunggah ke server mana pun selain WhatsApp.</p>

<p align="center"><a href="https://github.com/tomoyarei/WA-audio-stickers-indo/releases/download/v0.7.2/stickers-con-sonido-0.7.2-id.zip"><img src="docs/img/boton-descargar.png" width="352" alt="Unduh gratis (ZIP untuk Chrome, Edge, atau Brave)"></a></p>

<p align="center"><a href="#instalasi"><img src="docs/img/boton-guia.png" width="282" alt="Panduan instalasi"></a> <a href="https://ko-fi.com/shirtep"><img src="docs/img/boton-apoyar.png" width="282" alt="Dukung di Ko-fi"></a></p>

<p align="center"><sub>Gratis dan nirlaba. Donasi bersifat sukarela.</sub></p>

> Ini terjemahan bahasa Indonesia tidak resmi dari [Shirtep/WA-audio-stickers](https://github.com/Shirtep/WA-audio-stickers).

> **Peringatan:** proyek pribadi, **tidak resmi**, tidak berhubungan dengan WhatsApp maupun Meta. Ekstensi ini memakai fungsi internal WhatsApp Web yang bisa berubah kapan saja, dan mengaktifkan di browser Anda fitur stiker bersuara yang sedang diuji coba WhatsApp. Gunakan dengan risiko Anda sendiri.

## Instalasi

Tidak perlu menjalankan program apa pun: cukup muat folder ekstensi ke browser (Chrome, Edge, atau Brave versi desktop).

1. Unduh [**ZIP versi terbaru**](https://github.com/tomoyarei/WA-audio-stickers-indo/releases/download/v0.7.2/stickers-con-sonido-0.7.2-id.zip) (juga tersedia di halaman [rilis](https://github.com/tomoyarei/WA-audio-stickers-indo/releases/latest)).
2. Ekstrak ke tempat yang akan tetap di sana, misalnya `Documents`. Anda akan mendapatkan folder `stickers-con-sonido-id`.
   **Jangan menghapus atau memindahkannya setelah itu:** browser memuat ekstensi langsung dari folder tersebut.
3. Buka halaman ekstensi: ketik `chrome://extensions` di address bar (di Edge, `edge://extensions`).
4. Aktifkan **Mode developer** (kanan atas):

   <img width="188" height="37" alt="stiker1" src="https://github.com/user-attachments/assets/6dd5e1de-5ec2-4c30-b074-bc63a98b16eb" />


5. Klik **Muat yang belum dipaketkan** (*Load unpacked*; di beberapa versi namanya berbeda):

<img width="465" height="58" alt="stiker2" src="https://github.com/user-attachments/assets/d6a11f44-1134-45aa-b63e-c5b705622e06" />

6. Pilih folder `stickers-con-sonido-id` dari langkah 2, lalu klik **Pilih Folder**. Ekstensi akan muncul:

<img width="488" height="247" alt="stiker3" src="https://github.com/user-attachments/assets/c280537a-17e9-4c62-a0ba-6080db5eb544" />

7. Klik ikon puzzle di toolbar browser lalu **sematkan** (pin) **Stiker dengan Suara**, agar ikon ungunya mudah dijangkau.

Tangkapan layar diambil dari Brave. Di Chrome dan Edge tampilannya sama, hanya warnanya berbeda.

**Memperbarui:** unduh ZIP versi baru dan ganti isi folder `stickers-con-sonido-id` dengan yang baru. Lalu klik tombol muat ulang (↻) pada ekstensi di halaman ekstensi. Pengaturan Anda tetap tersimpan.

**Menghapus:** klik **Hapus** (*Remove*) di halaman ekstensi, lalu hapus foldernya.

## Cara pakai

1. Buka [web.whatsapp.com](https://web.whatsapp.com) dan masuk ke chat tempat Anda ingin mengirim stiker.
2. Klik ikon ungu ekstensi. Panelnya punya tiga tab, masing-masing dengan formulirnya sendiri:
   - **Video:** video dengan suaranya sendiri (langkah-langkahnya di bawah).
   - **Gambar + audio:** gambar diam dengan suara pilihan Anda (MP3, M4A, OGG, WAV, atau suara dari sebuah video). Audio dipotong dengan gagang di atas bentuk gelombangnya, dan durasi stiker sama dengan durasi potongan itu.
   - **Video atau GIF + audio:** animasi (video tanpa suaranya, atau GIF) dengan audio lain. Jika durasinya berbeda, secara default masing-masing berjalan sesuai durasinya sendiri: saat stiker disentuh, keduanya dimulai bersamaan dan berakhir sendiri-sendiri. Anda juga bisa mengulang animasi, atau mendiamkan frame terakhirnya sampai audio selesai. Mengubah potongan audio tidak mengharuskan opsi dihitung ulang.

   Pada tab **Video** ada empat langkah:
   1. **Video:** pilih video yang bersuara.
   2. **Potongan:** seret gagang hijau untuk menandai awal dan akhir. Video menampilkan frame yang tepat, dan tombol **−/+** menggeser satu frame.
   3. **Format:** klik **Hitung opsi**. Muncul tabel resolusi × fps beserta perkiraan ukuran tiap kombinasi:
      - hijau: muat;
      - kuning: muat dengan menurunkan kualitas;
      - ✕: tidak muat;
      - ★: yang direkomendasikan.
   4. **Buat dan kirim:** secara opsional tulis **paket** dan **pembuat** (WhatsApp menampilkannya di bawah stiker), buat stiker, periksa pratinjau, lalu kirim.
3. Dari ponsel, Anda bisa menandainya sebagai favorit agar bisa dipakai lagi.

## Batasan

| | Batas | Alasan |
|---|---|---|
| Ukuran stiker | **1 MB** | Server WhatsApp menolak file yang lebih besar (error 413). |
| Ukuran audio | 1 MB (≈ 10 menit) | Batas WhatsApp Web untuk audio stiker. |
| Resolusi | 64 sampai 512 px | WhatsApp memakai 512 px. Lebih besar tidak tampak lebih baik dan ukurannya lebih berat. |
| Kelancaran | hingga 30 fps | WhatsApp hanya mensyaratkan setiap frame berdurasi minimal 8 ms. |

Makin panjang potongannya, makin rendah resolusi atau fps yang muat dalam 1 MB: tabel pada langkah 3 menunjukkan apa yang muat sebelum Anda membuat apa pun.

Penerima stiker membutuhkan versi WhatsApp yang sudah bisa memutar stiker bersuara. Jika belum, yang terlihat hanyalah stiker biasa tanpa suara.

## Privasi

- Konversi video terjadi di browser Anda.
- Ekstensi menyimpan **log diagnostik** hanya di browser Anda, dengan nomor telepon disamarkan dan tanpa kunci. Anda bisa melihat, mengunduh, atau menghapusnya lewat *Alat uji* di panel, atau dengan klik kanan pada ikon → *Opsi*.

## Persyaratan

- Chrome, Edge, atau Brave versi desktop yang sudah diperbarui (memakai WebCodecs untuk mengenkode audio).
- Akun WhatsApp yang terbuka di WhatsApp Web.

## Untuk pengembang

- [`docs/como-funciona.md`](docs/como-funciona.md): cara stiker bersuara dirakit (protobuf, format audio, batasan) dan cara kerja ekstensi.
- [`dev/`](dev/): halaman untuk menguji konversi tanpa WhatsApp dan video kalibrasi sinkronisasi.

## Lisensi

Bebas dan gratis dipakai, **tanpa tujuan komersial**: Anda boleh menggunakan, mempelajari, mengubah, dan membagikannya, tetapi tidak boleh menjualnya atau memakainya untuk mencari untung. Teks lengkap ada di [`LICENSE.md`](LICENSE.md) ([PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0)). Disediakan apa adanya, tanpa jaminan.
