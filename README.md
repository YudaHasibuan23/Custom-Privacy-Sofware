<!-- LOGO PROYEK -->
<h1 align="center">
  <br>
  <a href="http:/whoamiproject.tech"><img src="https://user-images.githubusercontent.com/59175356/160829133-b140e801-8e1e-4255-9277-7ab05ae3640d.pg" alt="Whoami" width="200"></a>
</h1>

<h4 align="center"> <a href="http:/whoamiproject.tech" target="_blank">Whoami</a> <h2 align="center"> 

<!-- TENTANG PROYEK -->
<h2 align="center">Tentang Proyek</h2>

Dalam definisi paling sederhana dan terpendek, Whoami adalah alat privasi/anonimitas yang ramah pengguna dengan kemudahan penggunaan dan antarmuka sederhana. Whoami menggunakan lebih dari 9 modul berbeda untuk memastikan tingkat anonimitas setinggi mungkin juga memecahkan kemungkinan masalah tanpa mengganggu Anda dengan modul Pemecah Bug, yang sedang dalam pengembangan. Anda dapat menemukan deskripsi modul di bawah dan informasi lebih rinci di situs web. </a> dan lebih banyak informasi.

<!-- MODUL -->
<h2 align="center">Modul</h2>

<h4 align="center">Lihat bagian dokumentasi di situs web untuk informasi terperinci tentang modul</h4>
<table align="center">
    <thead>
    <tr>
      <th align="center"><img width="225" height="0"> <p>Nama Modul</p></th>
      <th align="center"><img width="225" height="0"> <p>Deskripsi</p></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Anti mitm</td>
       <td>Secara otomatis melarang penyerang saat Anda mengalami serangan Man In The Middle</td>
    </tr>
    <tr>
      <td>Log killer</td> 
       <td>Menghancurkan file log dalam sistem dengan metode overwrite</td>
    </tr>
    <tr>
      <td>IP changer</td>
       <td>Menyembunyikan alamat IP asli Anda dengan mengalihkan semua lalu lintas jaringan ke tor transparent proxy</td>
    </tr>
    <tr>
      <td>Dns change</td>
       <td>Mengganti server DNS default yang disediakan oleh ISP Anda dengan server berbasis privasi</td>
    </tr>
    <tr>
      <td>Mac changer</td>
       <td>Mengganti setiap antarmuka jaringan dalam sistem dengan alamat mac palsu</td>
    </tr>
        </tr>
    <tr>
      <td>Anti cold boot</td>
      <td>Menghindari dump RAM dengan menghapus jejak dalam sistem</td>
    </tr>
        </tr>
    <tr>
      <td>Timezone changer</td>
       <td>Mengatur waktu dalam UTC untuk menghindari kebocoran lokasi dari jam sistem</td>
    </tr>
        </tr>
    <tr>
      <td>Hostname changer</td>
       <td>Mengganti nama host dengan nama acak untuk menyembunyikannya</td>
    </tr>
        </tr>
    <tr>
      <td>Browser anonymization</td>
       <td>Mengonfigurasi browser agar berfokus pada privasi</td>
    </tr>
  </tbody>
</table>

<!-- MEMULAI -->
<h2 align="center">Memulai</h2>

Jika Anda tidak memperbarui sistem Anda secara teratur atau belum menginstal paket-paket ini di sistem Anda, Anda tidak akan dapat menggunakan alat ini. Jadi mari kita lihat apa yang kita butuhkan sebelum instalasi dan bagaimana kita bisa mengunduhnya.

* Anda dapat mengunduh semua dependensi dengan perintah berikut atau memeriksa apakah mereka sudah terbaru.

  ```sh
  sudo apt update && sudo apt install tar tor curl python3 python3-scapy network-manager
