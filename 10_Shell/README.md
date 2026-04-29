# <h1 align="center">Laporan Praktikum Modul 10 <br> Shell </h1>

<p align="center">Hafizh Dwi Andhika Faruq - 2311104013</p>

## Dasar Teori

Xinu adalah sistem operasi eksperimental yang dibuat untuk tujuan pendidikan dan penelitian. Xinu dirancang sederhana agar memudahkan pembelajaran konsep dasar sistem operasi seperti manajemen proses, memori, dan penjadwalan CPU.

## Guided

1. [40 Poin] Akan dimodifikasi shell dengan modifikasi syscall bernama chname yang
   berfungsi untuk mengubah nama suatu proses. Lihat kembali modul sebelumnya cara
   membuat syscall.
   Perhatikan sekarang syscall chname mempunyai 3 parameter yaitu pid, character dan
   panjang character. Character untuk menyimpan nama dan panjang character untuk
   panjang nama. <br>
   a. Pada prototypes.h chname diubah menjadi: <br>
   ![Logo](1_A.png) <br>
   b. Pada chname.c fungsi diubah dari: <br>
   ![Logo](1_B-1.png) <br>
   Menjadi <br>
   ![Logo](1_B-2.png) <br>
   Modifikasi kode pada chname.c sehingga nama proses bisa diubah bila syscall tersebut
   dipanggil.
2. [40 Poin] Buatlah perintah baru bernama namecmd sesuai dengan langkah-langkah pada
   no.5 pada modul shell!
   Berikut adalah kode dalam perintah baru namecmd: <br>
   ![Logo](2.png) <br>
3. [20 Poin] Test hasilnya: <br>
   a. Masuk ke terminal xinu <br>
   b. Jalankan perintah ps <br>
   c. Jalankan perintah namecmd <br>
   d. Jalankan perintah ps <br>
   e. Lihat nama proses telah berubah <br>

   Jawaban: <br>
   Proses dengan PID 2 (netin) diubah menjadi hello <br>
   ![Logo](Jawaban.png) <br>

## Referensi

1. https://en.wikipedia.org/wiki/Xinu
