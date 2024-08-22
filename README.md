# Tolls DG DeAth LINUX

<b>Termux tidak mendukung penggunaan paket dari Debian, Ubuntu, dan repositori distribusi Linux lainnya. Oleh karena itu, jangan mencoba memasukkan paket-paket ini ke dalam daftar sumber Anda atau menginstal file .deb secara manual. Lihat Perbedaan dari Linux untuk mengetahui alasannya.

# Pembatasan tambahan 😫:

-Saat ini, hanya satu arsitektur yang didukung. Anda tidak dapat menginstal paket 64 dan 32 bit secara bersamaan.
-Penggunaan apt di bawah root dibatasi untuk mencegah kekacauan kepemilikan dan label SELinux pada partisi Android/data.
-Penurunan versi tidak didukung. Untuk mendapatkan kembali ruang disk, kami tidak menyimpan riwayat versi paket.</b>

<b>Kami sangat menyarankan untuk menggunakan pkgutilitas alih-alih aptsecara langsung. Utilitas adalah pembungkus yang melakukan sejumlah tugas:

Menyediakan pintasan perintah. Gunakan "pkg in" sebagai ganti "pkg install" atau "apt install".
Secara otomatis menjalankan "apt update" sebelum menginstal paket jika perlu.
Melakukan penyeimbangan beban repositori sisi klien dengan secara otomatis mengganti mirror secara berkala. Hal ini penting untuk mencegah kami mencapai batas kuota pada hosting.</br>

# Menginstal paket baru 😯:

<b>
pkg instal nama-paket
Sangat disarankan untuk meng-upgrade paket yang sudah ada sebelum menginstal paket yang baru. Anda dapat menginstal pembaruan dengan menjalankan perintah ini:

peningkatan paket
Selain itu, kami sarankan untuk memeriksa pembaruan setidaknya seminggu sekali. Jika tidak, ada risiko tertentu bahwa selama instalasi atau pemutakhiran paket, Anda akan mengalami masalah.

Menghapus paket yang terinstal:

pkg hapus instalan nama-paket
Ini akan menghapus paket tetapi berkas konfigurasi yang dimodifikasi akan tetap utuh. Jika Anda ingin menghapusnya, gunakan apt purgesaja.</b>

# Lihat di bawah untuk perintah tambahan yang didukung 😊:

<b>
Memerintah	Keterangan
pkg autoclean	Hapus file .deb yang kedaluwarsa dari cache.
pkg clean	Hapus semua file .deb dari cache.
pkg files "package"	Daftar berkas yang diinstal berdasarkan paket yang ditentukan.
pkg list-all	Daftar semua paket yang tersedia.
pkg list-installed	Daftar paket yang saat ini terinstal.
pkg reinstall "package"	Instal ulang paket yang ditentukan.
pkg search "query"	Cari paket berdasarkan kueri.
pkg show "package"	Menampilkan informasi tentang paket tertentu.</b>

# Repositori Termux 🫠:
<b>Repositori Termux utama dapat diakses melalui https://packages.termux.org/apt/termux-main/

Kami memiliki beberapa repositori opsional yang menyediakan konten pada topik tertentu dan dapat diaktifkan dengan menginstal paket dengan nama berakhiran -repo.

Daftar repositori opsional saat ini:

Gudang	Perintah untuk berlangganan repositori
paket permainan	pkg install game-repo
paket sains	pkg install science-repo
paket-root-termux	pkg install root-repo
Paket x11 (hanya Android 7+)	pkg install x11-repo
Paket untuk repositori resmi kami dibuat dari skrip yang terdapat di github.com/termux/ dan dikelola serta ditandatangani oleh anggota tim pengembang Termux . Kunci publik untuk memverifikasi tanda tangan disediakan dalam paket termux-keyring. Untuk informasi lebih lanjut tentang cara repositori ditandatangani, lihat termux-keyring .

Mirror repositori apt Termux tersedia. Lihat informasi terkini tentangnya di Github .</b>

# Comunity 🥶:

<b>
Selain repositori resmi, ada repositori yang dihosting oleh anggota komunitas. Anda juga dipersilakan untuk menghosting repositori Termux Anda sendiri.

Anda dapat membuat repositori sendiri dengan menggunakan termux-apt-repo dari baris perintah dan Github Pages sebagai hosting. Perlu diketahui bahwa Github memiliki batasan ketat sebesar 100 MB per file dan jika repositori Anda melebihi ukuran total 1 GB, Anda mungkin menerima email sopan dari GitHub Support yang meminta Anda mengurangi ukuran repositori. Jadi, jika Anda memiliki paket yang sangat besar, Anda mungkin ingin menggunakan hosting yang berbeda. Pilih hosting menurut jenis file, misalnya, video dapat dihosting di https://YouTube.com atau yang serupa.
</b>

Anda dapat memilih cermin dengan menggunakan utilitas termux-change-repo.

Developer👨‍💻: https://github.com/DwiDevelopes <br>

Website🌎: https://linkr.bio/BangRoy.go.id <br>

Tiktok 🤩: https://www.Tiktok.com/@Royhtml <br>

Whatsapp 🫡: https://wa.me/+6289652969323 <br>

Telegram 😏: https://t.me/@BangRoy78 <br>

<br>
<p align="center">
  <img alt="Smiley face" src="https://i.ytimg.com/vi/cCaHytnFlNk/maxresdefault.jpg">
</p>
<br>

## One command Information detail📥:

visit : https://linkr.bio/BangRoy.go.id

<br>

## Install DG DeAth📲:

```pkg install```
<br></br>
```apt update```
<br>
<br></br>
```apt update -y```
<br></br>
```termux-setup-storage```
<br></br>
```pkg install wget```
<br><br>
wget -O install-nethunter-termux dwidevelopes.github.io/linux/
chmod +x install-nethunter-termux
./install-nethunter-termux


