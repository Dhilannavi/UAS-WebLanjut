<h1>laravel-berita</h1>
laravel-berita menggunakan framework laravael v10 dengan integrasi template AdminLTE 3 dan Bootstrap 5. 

![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/3bda3d0b-4220-4b8a-8265-210b685a6611)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/a34a22e0-d4c8-4b26-bc13-92f9022b9fe0)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/b81e959e-359b-4594-b0da-7695f7cfedda)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/ae8f8903-31ad-4714-9b71-4c7b45fee3c3)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/f5e8ed7e-2c82-47b8-9438-e8a3df3ecb64)
![Image](https://github.com/Dina067/UAS_WebLanjut/assets/124496007/acdc3894-f88d-4b3e-868b-e344c9de7a50)


<h2>Fitur</h2>
<ul>
    <li>Laravel Breeze (Blade)</li>
    <li>Spatie Permission v6 dengan multi role</li>
    <li>Wilayah Indonesia dari Laravolt meliputi: Province, City, District, Village</li>
    <li>Dashboard Admin: CRUD Post, Category, Tag, User, Navigation, Permission, Role</li>
    <li>Dashboard Author: CRUD Post, Edit Profile</li>
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

Atau Anda dapat melihat semua paket yang saya gunakan dalam repo ini dari plugin di folder public > assets folder and composer.json file. Namun plugin dan paketnya belum semuanya terpakai, jadi Anda bisa melihat yang sebenarnya dari layouts > app.blade.php and script.blade.php.

<h2>Cara Instalasi</h2>
<ul>
    <li>Pastikan Anda terhubung ke internet dan menginstal PHP 8.1.</li>
    <li>Buka terminal / cmd / powershell Anda untuk proyek ini dan jalankan perintah ini:
        <ul>
            <li>composer install / composer update</li>
            <li>cp .env.example .env</li>
            <li>php artisan migrate</li>
            <li>php artisan db:seed</li>
        </ul>
    </li>
    <li>Siapkan Kredensial Email SMTP (opsional)
        <ul>
            <li>MAIL_MAILER=</li>
            <li>MAIL_HOST=</li>
            <li>MAIL_PORT=</li>
            <li>MAIL_USERNAME=</li>
            <li>MAIL_PASSWORD=</li>
            <li>MAIL_ENCRYPTION=</li>
            <li>MAIL_FROM_ADDRESS=""</li>
        </ul>
    </li>
</ul>

<h2>Kredensial Login Pengguna</h2>
<ul>
    <li>Admin: email dan password; dinahariyanti48@gmail.com , bismillah1</li>
    <li>Author: email dan password; alexandra22@gmail.com , alexa123</li>
</ul>

Apakah anda memiliki saran lain untuk repo ini? Mari kembangkan repo ini menjadi lebih baik

