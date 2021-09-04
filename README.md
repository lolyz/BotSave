# Mantapjozz Saver Group

<a href="https://heroku.com/deploy?template=https://github.com/softmilkpc/MantapjozzSaverGroup">
   <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
 </a>
 <br>
<h1><b>Tutorial</b></h1> </br>
<code>ADMIN             :</code> isikan id admin ex. 1121192 </br>
<code>BOTUSERNAME       :</code> masukkan username bot tanpa "@", ex. mantapjozzgroupbot </br>
<code>CAPTIONLINK       :</code> isikan caption yang akan di isi pada file / video </br>
<code>CHANNELJOIN       :</code> Masukkan ID channel atau grup untuk identifikasi BOT bisa membaca pengguna yang masuk/forcesub </br>
<code>DB_URL            :</code> Dapatkan url basis data mongodb dari https://www.mongodb.com/cloud/atlas with database name = MantapFileMediaDB and collection name = Mantapjozzsaver. Klik Connect dan pilih 'Hubungkan aplikasi Anda'.copy tautan dan ganti "< password >" dengan kata sandi pengguna yang memiliki akses ke DB dan ganti "myFirstDatabase" untuk "MantapFileMediaDB". Kalau mau ubah sesuai keinginan nama databasenya ada di folder config. </br>
<code>DOMAIN            :</code> Masukkan nama aplikasi Anda sesuai nama app heroku saja ex. mantapjozzgroup </br>
<code>LINKCHANNEL       :</code> Link channel grup masukkan disini dan ikuti format penulisan ex. Gabung-https://t.me/mantapvids </br>
<code>LOG_CHANNEL       :</code> Buat saluran pribadi dan masukkan id saluran untuk memantau file dan mendapatkan data pengguna dan file alias channel DB </br>
<code>MESSAGEWELCOMEBOT :</code> Masukkan pesan untuk pengguna yang belum bergabung channel </br>
<code>TOKEN             :</code> Token bot disediakan oleh  @botfather </br>
<code>WELCOMEJOINBOT    :</code> Masukkan pesan untuk pengguna setelah bergabung </br>

<h1>Berikut adalah beberapa perintah dan penggunaan admin.</h1>


    Bagaimana pengguna melarang, unban dan kick dari BOT dan Grup.

<code>/ban</code> userID caption jika ada.
<code>/banchat</code> userID (pribadi). 

<code>/unban</code> userID.
<code>/unbanchat</code> userID (pribadi).

<code>/kick</code> userID.

(Dapatkan UserID dari saluran log).


    Bagaimana cara menggunakan pin dan unpin di grup.

<code>/pin</code> reply ke pesan yang mau di pin.

<code>/unpin</code> reply ke pesan yang mau di unpin.


    Bagaimana cara kirim pesan ke pengguna dari grup.

<code>/send</code> userID pesan. kirim ke pengguna melalui grup.


    Bagaimana cara kirim pesan ke pengguna dari BOT.

<code>/sendchat</code> userID pesan. kirim ke pengguna melalui BOT.
 

<h2>Cara Menghapus File Dari Bot.</h2>


Anda dapat menghapus file 3 cara.

  ⚫ Hapus file individual dengan file_id.

  ⚫ Hapus semua file Kirim oleh pengguna.

  ⚫ Hapus semua file Kirim ke BOT.


    Hapus file individual dengan file_id.

<code>/rem</code> file_id.

(Ini akan menghapus file satu per satu saat Anda memberikan file_id, dapatkan file_id dari saluran log).


    Hapus semua file Kirim oleh pengguna.

<code>/remall</code> userID.

(Anda dapat menghapus semua file dikirim oleh pengguna tertentu jika pengguna mengirim konten atau spam yang kasar, dapatkan userid dari saluran log).


    Hapus semua file Kirim ke B0T.

<code>/clear</code>

(Ini akan menghapus semua file yang dikirim ke BOT secara permanen).

<h2>Kirim pesan ke pengguna</h2>

<code>/broadcast</code> Pesan Anda akan dikirim ke pengguna.

(Anda dapat menyiarkan pesan teks ke pengguna Anda, pesan akan dikirim dari pengguna terakhir bergabung untuk pertama-tama bergabung dengan pengguna untuk mengurangi spam. Cobalah untuk tidak mengirim terlalu banyak pesan sekaligus jika Anda memiliki sejumlah besar pengguna).


<h2>Cara Mengetahui Total Pengguna BOT.</h2>

<code>/stats</code>

(Anda akan mendapatkan total pengguna memulai BOT Anda, data waktu nyata akan diperbarui setelah siaran yang berhasil).

