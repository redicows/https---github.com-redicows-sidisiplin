<h1 align="center">Selamat datang di Sistem Informasi Akademik Sekolah! 👋</h1>

## Apa itu Sistem Informasi Akademik Sekolah?

Web Sistem Informasi Akademik Sekolah yang dibuat oleh <a href="https://github.com/adhiariyadi"> Adhi Ariyadi </a>. **Sistem Informasi Akademik Sekolah adalah Website untuk para siswa dapat melihat jadwal pelajaran, dan nilai rapot dan para guru dapat menambahkan nilai siswa dengan muda melalui website.**

## Fitur apa saja yang tersedia di Sistem Informasi Akademik Sekolah?

- Autentikasi Admin
- User & CRUD
- Jadwal & CRUD
- Kelas & CRUD
- Mata Pelajaran & CRUD
- Guru & CRUD
- Siswa & CRUD
- Rapot
- Dan lain-lain

## Release Date

**Release date : 28 Apr 2024**

> Sistem Informasi Akademik Sekolah merupakan project open source yang dibuat oleh Adhi Ariyadi. Kalian dapat download/fork/clone. Cukup beri stars di project ini agar memberiku semangat. Terima kasih!

---

## Default Account for testing

**Admin Default Account**

- email: admin@gmail.com
- Password: 12345678

---

## Install

1. **Clone Repository**

```bash

cd Sistem-Informasi-Akademik-Sekolah-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```


## Contributing

