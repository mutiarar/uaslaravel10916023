<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


Sesuai dengan penjelasan yang ada pada modul, dimulai dengan penginstalan laravel yang dapat dilalu dengan dua cara yaitu melalui composser dan copy fresh laravel. Setelah penginstalan dilakukan integrasi dengan template admin.lte 2.3.11 agar ada tampilan yang dibagi menjadi tiga yaitu header,index, dan footer. Setelah itu mulai membuat controller menggunakan artisan melalui command prompt.

Setelah itu dilakukan pembuatan tabel melalui artisan juga, namun sebelumnya harus disetting agar terhubung dengan database yang sudah kita buat. Setelah disetting pembuatan tabel bisa dilakukan,untuk pembuatan struktur tabel dilakukan dengan cara mengedit struktur pada file php tabel yang kita buat lalu melakukan migration, otomatis struktur yang diedit sudah berubah di database juga.Setelah pembuatan struktur tabel,lalu dilakukan seeder yaitu mengisi struktur yang sudah ada melalui artisan yang otomatis akan terhubung juga. Setelah controller dan tabel dibuat dilakukan pembuatan create, update dan delete data. Data yang dibuat ada 2, yaitu data kelas dan siwa.

Setelah create, update dan delete dibuat lalu buat tampilan dan data untuk login, untuk pembuatan hampir sama dengan pembuatan data kelas dan siswa. Jika sudah selesai dibuat lalu hubungkan login agar langsung diarahkan ke halaman login.
