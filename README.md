# Aplikasi Peminjaman Ruangan Laboratorium

Room and laboratory booking system built on **CodeIgniter** (PHP), with an admin panel
for managing rooms and reservations.

**PHP · CodeIgniter 3 · MySQL**

---

## Setup

1. Sesuaikan URL pada `application/config/config.php` — set `base_url` to your install path.
2. Buat database baru bernama `siplab` dan import file `siplab.sql`.
3. Sesuaikan kredensial database di `application/config/database.php`.
4. Login sebagai admin:

   ```
   user: admin
   pass: admin
   ```

---

## Running locally

Requires PHP 7.4+ and MySQL, plus Apache with `.htaccess` support (`mod_rewrite`
enabled) — or point the web root at this folder.

```bash
php -S localhost:8000
```

> ⚠️ The default password `admin` is for local setup only. Change it before deploying
> anywhere reachable from the internet, and update `config.php` so `base_url` and
> sessions match your host.
