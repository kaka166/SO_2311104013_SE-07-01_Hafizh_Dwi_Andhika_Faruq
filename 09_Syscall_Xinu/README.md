# <h1 align="center">Laporan Praktikum Modul 9 <br> Syscall </h1>

<p align="center">Hafizh Dwi Andhika Faruq - 2311104013</p>

## Dasar Teori

Xinu adalah sistem operasi eksperimental yang dibuat untuk tujuan pendidikan dan penelitian. Xinu dirancang sederhana agar memudahkan pembelajaran konsep dasar sistem operasi seperti manajemen proses, memori, dan penjadwalan CPU.

## Guided

1. [50 Poin] Buat syscall baru seperti yang ditunjukkan pada modul syscall poin 9.5!
   (sertakan Screenshot kode dan hasil run)
   ![Logo](Jawaban1.png) <br>
2. [25 Poin] Perbaiki syscall chprio (xinu/system/chprio.c) dengan memperhatikan validasi
   input <br>
   ● Pastikan id adalah angka dari 0 – NPROC (ukuran maks banyaknya proses)<br>
   ● Pastikan prioritas adalah bilangan yang positif<br>
   Compile dan jalankan Xinu dengan syscall yang telah diperbaiki<br>
   ● make clean <br>
   ● make <br>
   ![Logo](Jawaban2.png) <br>
3. Lakukan hal-hal berikut ini <br>
   ● Edit xsh_uptime.c <br>
   Tambahkan kode berikut <br>
   ![Logo](SS1.jpg) <br>
   ● Compile source code tersebut dengan perintah <br>
   ● make clean <br>
   ● make <br>
   ● Jalankan perintah ps <br>
   ● xsh $ps <br>
   ● perhatikan prioritas proses dengan id = 5 <br>
   ● Jalankan uptime <br>
   ● xsh $uptime <br>
   ● Perhatikan hasil perintah tersebut <br>
   ● Jalankan ps <br>
   ● xsh $ps <br>
   ● perhatikan prioritas proses dengan id = 5 seharusnya sudah berubah <br>

   [25 Poin] Testing chprio syscall yang telah diubah <br>
   ● Testing prioritas tidak boleh &lt; 0: Ubah “chprio(5,33)” menjadi “chprio(5,-3)” <br>
   pada xsh_uptime.c <br>
   ● Testing id adalah valid: Ubah “chprio(5,33)” menjadi “chprio(3000,3)” <br>
   ● Hasil dua testing di atas adalah prioritas tidak berubah karena salah argument <br>
   (dibuktikan dengan menggunakan perintah ps) <br>
   ![Logo](Jawaban3.png) <br>

## Referensi

1. https://en.wikipedia.org/wiki/Xinu
