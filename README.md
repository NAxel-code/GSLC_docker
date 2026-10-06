# GSLC_docker

Tugas GSLC sesi 4 — contoh sederhana PHP "Hello World" yang dijalankan dengan Docker Compose.

## Struktur

- `docker-compose.yml` — konfigurasi service `web` menggunakan image `php:8.2-apache`.
- `src/index.php` — halaman PHP sederhana yang menampilkan `Hello, World!`.

## Cara Menjalankan

```bash
docker compose up -d
```

Buka browser ke [http://localhost:8080](http://localhost:8080).

## Menghentikan

```bash
docker compose down
```
