<h1>Pertal Berita Laravel</h1>
<p>Website ini dibangun menggunakan Laravel versi 10 dengan integrasi template AdminLTE 3 untuk dashboard admin dan Bootstrap 5 untuk antarmuka pengguna.</p>

<p><strong>Laravel 10:</strong> Framework PHP yang andal dan modern untuk membangun aplikasi web.</p>

<p><strong>AdminLTE 3:</strong> Template dashboard admin responsif yang menyediakan berbagai komponen UI siap pakai.</p>

<p><strong>Bootstrap 5:</strong> Framework CSS yang populer untuk pengembangan frontend yang cepat dan responsif.</p>

<p>Dengan kombinasi ini, Portal Berita Laravel menawarkan antarmuka pengguna yang intuitif dan mudah digunakan baik untuk admin maupun pengunjung.</p>

<h2>Dokumentasi Website</h2>

![Screenshot (246)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/1a6aeb5d-0a10-4145-b654-efe7fc6b0ed7) 

![Screenshot (256)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/2b10e2fa-4a30-4092-9788-d47e80742781) 

![Screenshot (247)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/14844715-609e-425b-9c24-252f5b7738ec) 

![Screenshot (248)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/bf716d75-90af-40b1-820c-b16e259d6e13) 

![Screenshot (249)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/d86c424e-54cd-48aa-9f87-cd69e6a34a62) 

![Screenshot (250)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/d17ec79d-210a-4a7d-99ed-88e1c2b7ffff) 

![Screenshot (251)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/df419adb-22fa-400c-8624-b0bafb3589ff) 

![Screenshot (252)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/856577a5-1fd0-4b57-8672-51b6983afc3d) 

![Screenshot (253)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/fc051ca1-afde-4a30-b8f2-8516a7d27333) 

![Screenshot (254)](https://github.com/Dhilannavi/UAS-WebLanjut/assets/124485266/a2fb5297-cc32-4830-b973-866246e059ed)



<h2>Fitur</h2>
<ul>
    <li>Laravel Breeze (Blade)</li>
    <li>Spatie Permission v6 dengan dukungan multi role</li>
    <li>Data wilayah Indonesia dari Laravolt mencakup: Provinsi, Kota, Kecamatan, Desa</li>
    <li>Dashboard Admin: CRUD untuk Post, Kategori, Tag, Pengguna, Navigasi, Permission, Role</li>
    <li>Dashboard Penulis: CRUD untuk Post, Edit Profil</li>
</ul>

<h3>Layout</h3>
Frontend: Bootstrap 5, Backend: AdminLTE 3

<h3>Paket</h3>
<ul>
    <li>Yajra Datatable</li>
    <li>SweetAlert</li>
    <li>Select2</li>
    <li>Bootstrap Datepicker</li>
    <li>Fontawesome 6</li>
</ul>

<p>Untuk melihat semua paket yang digunakan dalam repository ini, Anda dapat memeriksa plugin di folder <code>public > assets</code> dan file <code>composer.json</code>. Namun, tidak semua plugin dan paket sudah diterapkan, jadi Anda bisa melihat yang sebenarnya digunakan di <code>layouts > app.blade.php</code> dan <code>script.blade.php</code>.</p>



<h2>Cara Instalasi</h2>
<ol>
    <li>Pastikan Anda terhubung ke internet dan memiliki PHP 8.1 terinstal pada sistem Anda.</li>
    <li>Buka terminal atau command prompt (cmd) di direktori proyek ini, lalu jalankan perintah berikut:
        <ol>
            <li>Instal atau perbarui dependensi dengan Composer:
                <pre><code>composer install</code></pre>
                atau jika sudah pernah diinstal sebelumnya:
                <pre><code>composer update</code></pre>
            </li>
            <li>Salin file konfigurasi contoh dan sesuaikan:
                <pre><code>cp .env.example .env</code></pre>
            </li>
            <li>Jalankan migrasi database untuk membuat tabel yang diperlukan:
                <pre><code>php artisan migrate</code></pre>
            </li>
            <li>Seed database dengan data awal:
                <pre><code>php artisan db:seed</code></pre>
            </li>
        </ol>
    </li>
</ol>

<p>Dengan langkah-langkah di atas, proyek Anda seharusnya siap untuk dijalankan. Pastikan untuk memeriksa konfigurasi lainnya sesuai kebutuhan Anda.</p>


<h2>Menggunakan PHP Versi Lain</h2>
<p>Jika Anda menggunakan versi PHP selain 8.1, seperti 8.3, pastikan semua ekstensi yang dibutuhkan terpasang dan kompatibel dengan proyek Anda. Sebagai contoh, untuk PHP 8.3, Anda mungkin perlu mengatasi beberapa masalah kompatibilitas dan ketergantungan paket:</p>

<ol>
    <li><strong>Install atau Enable Ekstensi GD untuk PHP</strong>
        <ul>
            <li><strong>Windows:</strong>
                <ol>
                    <li>Buka file <code>php.ini</code> (misalnya di <code>C:\php-8.3.3\php.ini</code>).</li>
                    <li>Cari baris <code>;extension=gd</code>.</li>
                    <li>Hapus tanda titik koma (<code>;</code>) di awal baris tersebut untuk mengaktifkannya.</li>
                    <li>Simpan file <code>php.ini</code>.</li>
                    <li>Restart web server Anda.</li>
                </ol>
            </li>
            <li><strong>Linux:</strong>
                <ul>
                    <li><strong>Ubuntu/Debian:</strong>
                        <pre><code>sudo apt-get update
sudo apt-get install php-gd
sudo service apache2 restart</code></pre>
                    </li>
                    <li><strong>CentOS/RHEL:</strong>
                        <pre><code>sudo yum install php-gd
sudo systemctl restart httpd</code></pre>
                    </li>
                </ul>
            </li>
        </ul>
    </li>
    <li><strong>Verifikasi Ekstensi GD</strong>
        <p>Pastikan ekstensi GD aktif dengan menjalankan:</p>
        <pre><code>php -m | grep gd</code></pre>
        <p>Harus muncul output <code>gd</code> jika ekstensi sudah aktif.</p>
    </li>
    <li><strong>Perbarui <code>composer.json</code> Dependencies</strong>
        <p>Sesuaikan <code>composer.json</code> untuk mendukung versi PHP Anda:</p>
        <pre><code>{
    "require": {
        "phpoffice/phpspreadsheet": "^1.29",
        "maatwebsite/excel": "^3.1"
    }
}</code></pre>
    </li>
    <li><strong>Update Composer</strong>
        <p>Jalankan perintah berikut untuk memperbarui dependencies:</p>
        <pre><code>composer update --with-all-dependencies</code></pre>
        <p>Jika masih ada masalah dengan ekstensi GD, Anda bisa melewatinya sementara dengan:</p>
        <pre><code>composer install --ignore-platform-req=ext-gd</code></pre>
        <p>Namun, lebih baik jika Anda memastikan ekstensi GD terinstal dengan benar.</p>
    </li>
</ol>

<h2>Mengatasi Masalah Dependency</h2>
<p>Jika Anda menghadapi masalah ketergantungan, seperti versi PHP yang tidak kompatibel dengan paket tertentu, pastikan Anda menggunakan versi paket yang mendukung versi PHP Anda. Misalnya, <code>maatwebsite/excel</code> versi terbaru mungkin diperlukan untuk mendukung PHP 8.3.</p>
<p>Dengan langkah-langkah ini, Anda seharusnya dapat menginstal dan menjalankan proyek Anda tanpa masalah.</p>


<h2>Kredensial Login Pengguna</h2>
<ul>
    <li>Admin: email dan password; dhilannafi@gmail.com , admin123</li>
    <li>Author: email dan password; robertbaratheon@gmail.com , a1b2c3d4</li>
</ul>

