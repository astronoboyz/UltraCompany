# Cloudly Static Website

Website statis untuk layanan rental cloud dengan beberapa halaman:

- `index.html` sebagai beranda utama.
- `about.html` untuk profil perusahaan.
- `services.html` untuk daftar layanan.
- `contact.html` untuk kontak.

## Tech stack

- HTML statis
- Tailwind CSS via CDN
- Nginx (Docker)

## Menjalankan

1. Buka `index.html` di browser, atau
2. Jalankan via Docker:

	```bash
	docker compose up -d --build
	```

	Akses di http://localhost

## Catatan deploy

- Semua aset menggunakan path relatif.
- Tidak ada proses build.
- Cocok untuk hosting statis atau container di VPS.
