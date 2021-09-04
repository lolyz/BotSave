# Mantapjozz Saver Group

<a href="https://heroku.com/deploy?template=https://github.com/softmilkpc/MantapjozzSaverGroup">
   <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
 </a>
 <br>
# Tutorial
<code>ADMIN             :</code>{
            "description": "isikan id admin ex. 1121192",
<code>BOTUSERNAME       :</code> masukkan username bot tanpa "@", ex. mantapjozzgroupbot
<code>CAPTIONLINK       : isikan caption yang akan di isi pada file / video
<code>CHANNELJOIN       : Masukkan ID channel atau grup untuk identifikasi BOT bisa membaca pengguna yang masuk/forcesub
<code>DB_URL            : Dapatkan url basis data mongodb dari https://www.mongodb.com/cloud/atlas with database name = MantapFileMediaDB and collection name = Mantapjozzsaver
<code>DOMAIN            : Masukkan nama aplikasi Anda sesuai nama app heroku saja ex. mantapjozzgroup
<code>LINKCHANNEL       : Link channel grup masukkan disini dan ikuti format penulisan ex. Gabung-https://t.me/mantapvids
<code>LOG_CHANNEL       : Buat saluran pribadi dan masukkan id saluran untuk memantau file dan mendapatkan data pengguna dan file alias channel DB
<code>MESSAGEWELCOMEBOT : Masukkan pesan untuk pengguna yang belum bergabung channel
<code>TOKEN             : Token bot disediakan oleh  @botfather
<code>WELCOMEJOINBOT    : Masukkan pesan untuk pengguna setelah bergabung

</a>
<br>
Ganti tautan dengan template github Anda.
</br>

<br>
Detail yang diperlukan.

<code>TOKEN</code> - Dapatkan Token Bot dari Bot father.

<code>DOMAIN</code> - Sama dengan nama aplikasi yang Anda masukkan di Heroku.

<code>ADMIN</code> - ID Akun Anda (jika Anda tidak dapat menemukannya menggunakan bot seperti @getmyid_bot).

<code>BOTUSERNAME</code> - Nama pengguna bot Anda tanpa '@'.

<code>DB_URL</code> - Buat akun di https://www.mongodb.com/cloud/atlas , nama database - Mantapjozz ,nama collection - MantapjozzBackup.Klik Connect dan pilih 'Hubungkan aplikasi Anda'.copy tautan dan ganti "< password >" dengan kata sandi pengguna yang memiliki akses ke DB dan ganti "myFirstDatabase" untuk "MantapjozzDB". Kalau mau ubah sesuai keinginan nama databasenya ada di folder config.

<code>LOG_CHANNEL</code> - buat saluran pribadi dan dapatkan ID saluran (jika Anda tidak dapat meneruskan ID saluran apa pun dari saluran ke @getidsbot itu mungkin terlihat seperti -1001234567890).
<hr>

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


<b>Jika Anda ingin mendukung saya, ikuti saya di GitHub sebagai dukungan.</b>

//Update

HISTORY 6
1. Kirim pesan ke pengguna melalui BOT.

HISTORY 5
1. Kirim pesan ke pengguna melalui grup.

HISTORY 4
1. BOT mendukung kick, ban, unban dan ada pesan pribadi.
2. BOT mendukung pin dan unpin.

HISTORY 3
1. Perbaikan penulisan file_name.
2. Perbaikan pencarian media.

HISTORY 2
1. Function teks disederhanakan.
2. Mendeteksi jika belum ada nama akun akan dikosongkan.
3. Admin bisa menggunakan BOT tanpa masuk channel/grup.
4. Ada log channel untuk mengetahui siapa yang ngirim dan apa deskripsi filenya.

HISTORY 1
1. Ada join channel/grup terlebih dahulu saat start, pastikan id channel/grup di ganti pada index.js dan bot harus jadi admin di grup/channel.
2. Terdapat penambahan untuk menghilangkan null supaya tidak terlihat saat tampil.
3. Ada get ID untuk cek ID akun Anda.
4. Ada pesan bot belum dimasukkan ke channel/grup tujuan.


