# Novz Schematic

Website schematic Minecraft (farm dan base) 100% gratis. Request schematic lewat ticket Discord: https://dc.gg/novzschematic

## Struktur

```
index.html          halaman website
assets/images/      screenshot tiap schematic
assets/video/       video background (novz-bg.mp4)
schematics/         file .litematic yang bisa didownload
```

## Pasang di GitHub Pages

1. Buat repository baru di GitHub, misalnya `novz-schematic`.
2. Ekstrak zip ini, lalu upload isi folder `novz-schematic` ke repository (Add file, Upload files).
3. Buka Settings, Pages. Pada Source pilih "Deploy from a branch", branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1 sampai 2 menit. Website bisa dibuka di `https://USERNAME.github.io/novz-schematic/`.

## Menambah schematic baru

1. Taruh file `.litematic` di folder `schematics/` dan screenshot di `assets/images/`.
2. Di `index.html`, salin salah satu blok `<article class="farm">...</article>`.
3. Ganti judul, deskripsi, nama pembuat, path gambar, dan path file download.
