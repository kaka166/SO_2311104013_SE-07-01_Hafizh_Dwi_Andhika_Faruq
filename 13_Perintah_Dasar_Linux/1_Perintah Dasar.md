# <h1 align="center">Laporan Praktikum Modul 13 <br> Perintah Dasar Linux</h1>

<p align="center">Hafizh Dwi Andhika Faruq - 2311104013</p>

## Dasar Teori

Windows dan Linux merupakan sistem operasi yang berfungsi mengatur perangkat keras dan perangkat lunak pada komputer agar dapat digunakan oleh pengguna. Windows dikembangkan oleh Microsoft dengan antarmuka yang mudah digunakan dan kompatibel dengan banyak aplikasi umum. Sementara itu, Linux adalah sistem operasi open-source yang dikembangkan dari kernel Linux dan memiliki berbagai distro seperti Ubuntu, Debian, dan Fedora, dengan keunggulan pada stabilitas, keamanan, serta fleksibilitas penggunaannya.

## Guided

1.  a. Jalankan dan screenshot terminal Anda!<br>
    ![Logo](1.a.png) <br>
    b. Jelaskan arti dari command prompt milik Anda! <br>
    - xinu = username pengguna <br>
    - xinu-develop-end = hostname/ nama komputer <br>
    - ~ = direktori home user <br>
    - $ = menandakan pengguna biasa (bukan root) <br>
2.  a. Jalankan dan screenshot perintah berikut ini: ls <br>
    ![Logo](2.a.png) <br>
    b. Apakah option dan parameter dari perintah di atas? <br>
    Tidak ada option ataupun parameter di perintah atas. <br>
    c. Apa fungsi dari perintah tersebut? <br>
    Perintah tersebut berfungsi untuk menampilkan daftar file dan folder pada direktori saat ini. <br>
    d. Jalankan perintah berikut ini: ls -al / <br>
    ![Logo](2.d.png) <br>
    e. Apakah option dan parameter dari perintah di atas? <br>
    - Option: -a = menampilkan file tersembunyi, dan -l = menampilkan detail file. <br>
    - Parameter: / yang artinya direktori root <br>

    f. Apa fungsi dari perintah tersebut? <br>
    Menampilkan seluruh file dan folder pada direktori root secara detail termasuk dengan file tersembunyi. <br>
    g. Jelaskan mengapa perintah pada a dan e mempunyai hasil yang berbeda! <br>
    Karena ls hanya menampilkan isi direktori secara biasa dan ls -al / menampilkan isi direktori root secara lengkap dan detail termasuk dengan file tersembunyi <br>

3.  a. Jalankan dan screenshot perintah: pwd <br>
    ![Logo](3.a.png) <br>
    b. Apakah option dan parameter dari perintah tersebut?
    - Option: tidak ada
    - Parameter: tidak ada

    c. Apa fungsi perintah tersebut? <br>
    Menampilkan lokasi direktori kerja saat ini <br>

4.  a. Jalankan dan screenshot perintah: cd / <br>
    ![Logo](4.a.png)
    b. Apakah option dan parameter dari perintah tersebut? <br>
    - Option: tidak ada
    - Parameter: / = direktori root

    c. Apa yang dilakukan perintah tersebut? <br>
    Berpindah ke direktori root Linux.

5.  a. Lakukan dan screenshot perintah cd / kemudian lakukan perintah cd ~. Jelaskan
    hasil dari keduanya!
    ![Logo](5.a.png) <br>
    Penjelasan: cd / berfungsi untuk berpindah ke direktori root dan cd ~ berfungsi untuk berpindah ke home directory user. <br>
    b. Lakukan perintah cd /proc/self. Buatlah perintah menggunakan cd .. agar dapat
    berpindah ke direktori / (root). Berapa kali perintah cd .. harus dieksekusi?
    Screenshot hasilnya! <br>
    ![Logo](5.b.png) <br>
    Penjelasan: untuk kembali ke root / dari /proc/self dibutuhkan 2 kali perintah cd .. untuk dieksekusi. <br>

6.  a. Copylah file dari /proc/cpuinfo ke folder home Anda (/home/user/) menggunakan
    command pada terminal. Ganti user dengan username anda. <br>
    ![Logo](6.a.png) <br>
    b. Tunjukkan menggunakan perintah bahwa file tersebut benar-benar telah dicopy ke
    folder home Anda. <br>
    ![Logo](6.b.png) <br>
    c. Copy file dari /proc/uptime ke folder home Anda. <br>
    ![Logo](6.c.png) <br>
    d. Tunjukkan menggunakan perintah bahwa file tersebut benar-benar telah dicopy ke
    folder home Anda. <br>
    ![Logo](6.d.png) <br>
    e. Hapuslah file uptime di folder home Anda. <br>
    ![Logo](6.e.png) <br>
    f. Tunjukkan menggunakan perintah bahwa file tersebut benar-benar telah dihapus ke
    folder home Anda. <br>
    ![Logo](6.f.png) <br>
    g. Rename file cpuinfo di folder home Anda menjadi infocpu <br>
    ![Logo](6.g.png) <br>

7.  a. Buatlah folder baru dengan nama “nim_anda”. <br>
    ![Logo](7.a.png) <br>
    b. Buatlah di dalam folder “nim_anda”, folder baru dengan nama “nama_anda”. <br>
    ![Logo](7.b.png) <br>

8.  a. Bukalah fungsi manual untuk perintah “ls” <br>
    ![Logo](8.a.png) <br>
    b. Apa fungsi perintah “ls”? <br>
    Menampilkan isi direktori. <br>
    c. Siapakah pencipta perintah “ls”? <br>
    Richard M. Stallman dan David MacKenzie. <br>
    d. Apakah arti dari -h dari manual ls? <br>
    Menampilkan ukuran file dalam format mudah dibaca manusia (KB, MB, GB). <br>
    e. Option apa yang harus digunakan agar dapat melihat direktori secara rekursif? <br>
    -R <br>
    f. Bukalah fungsi manual untuk perintah “cp” <br>
    ![Logo](8.f.png) <br>
    g. Apa fungsi perintah “cp” <br>
    Menyalin file atau folder. <br>
    h. Siapakah pencipta perintah “cp”? <br>
    Torbjorn Granlund, David MacKenzie, dan Jim Meyering. <br>
    i. Apakah arti -v dalam perintah “cp? <br>
    Verbose yang mana menampilkan proses penyalinan file. <br>
    j. Jika ingin interaktif, option apa yang harus digunakan? <br>
    -i <br>

9.  a. Lakukan perintah ini cat /etc/passwd dan screenshot hasil perintah tersebut! <br>
    ![Logo](9.a.png) <br>
    b. Apa fungsi perintah cat? <br>
    Untuk menampilkan isi file. <br>
    c. Lakukan perintah cat /etc/passwd | grep daemon dan screenshot hasil perintah
    tersebut! <br>
    ![Logo](9.c.png) <br>
    d. Lakukan perintah cat /etc/passwd | grep root dan screenshot hasil perintah tersebut! <br>
    ![Logo](9.d.png) <br>
    e. Lakukan perintah cat /etc/passwd | grep nobody dan screenshot hasil perintah <br>
    tersebut! <br>
    ![Logo](9.e.png) <br>
    f. Apakah fungsi perintah “ | grep daemon”? <br>
    - | = pipe, untuk mengirim output ke perintah berikutnya.
    - grep daemon untuk mencari kata "daemon"

10. a. Lakukan perintah dan jelaskan hasilnya <br>
    cd / <br>
    ls -al > /home/user/result.txt <br>
    Ganti user dengan username ubuntu anda. <br>
    ![Logo](10.a.png) <br>
    b. Dimana file result.txt berada? <br>
    File ada di /home/xinu/result.txt <br>
    c. Lakukan perintah dan jelaskan hasilnya
    cd /etc <br>
    ls -al > /home/user/result.txt <br>
    Ganti user dengan username ubuntu anda. <br>
    ![Logo](10.c.png) <br>
    d. Apakah fungsi dari perintah >? <br>
    Menyimpan output ke file dan menyimpan isi file sebelumnya. <br>
    e. Lakukan perintah dan jelaskan hasilnya cd / <br>
    ls -al >> /home/user/result1.txt <br>
    Ganti user dengan username ubuntu anda. <br>
    ![Logo](10.e.png) <br>
    f. Lakukan perintah dan jelaskan hasilnya <br>
    cd /etc <br>
    ls -al >> /home/user/result1.txt <br>
    Ganti user dengan username ubuntu anda. <br>
    ![Logo](10.f.png) <br>
    g. Apakah perbedaan perintah > dan >>? <br>
    - ">" = overwrite/ menimpa isi file <br>
    - ">>" = append/ menambahkan isi file <br>

## Referensi

1. https://id.wikipedia.org/wiki/Linux
2. https://en.wikipedia.org/wiki/Microsoft_Windows
3. https://en.wikipedia.org/wiki/Operating_system
