# Kenneth — Visual Stories Photography Portfolio

Website portfolio fotografi pemula menggunakan HTML, CSS, dan JavaScript murni.

## Struktur folder

```text
kenneth-photography-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Cara menjalankan di VS Code

1. Ekstrak file ZIP.
2. Buka VS Code.
3. Pilih **File → Open Folder**, lalu pilih folder `kenneth-photography-portfolio`.
4. Buka `index.html`.
5. Untuk cara termudah, pasang ekstensi **Live Server** dari Extensions di VS Code.
6. Klik kanan `index.html` → **Open with Live Server**.
7. Website akan terbuka di browser.

Alternatif: buka `index.html` langsung dengan browser. Live Server memudahkan proses pengembangan dan refresh.

## Cara mengganti nama dan kontak

- Nama website: ubah teks `KENNETH` dan `Kenneth` di `index.html`.
- Email: cari `hello@example.com` di `index.html`, lalu ganti dengan email kamu.
- Deskripsi: edit bagian `hero-description` dan bagian About.

## Cara mengganti foto dengan foto sendiri

1. Buat folder baru bernama `images` di dalam folder project.
2. Salin foto kamu ke folder `images`, misalnya `foto-pesawat.jpg`.
3. Di `index.html`, cari tag gambar yang ingin diganti.
4. Ganti URL `src` dengan `images/foto-pesawat.jpg`.
5. Untuk foto yang bisa diperbesar, ganti juga URL pada atribut `data-full` dengan `images/foto-pesawat.jpg`.

Contoh:

```html
<img src="images/foto-pesawat.jpg" alt="Pesawat di bandara">
```

Pada tombol foto, pastikan `data-full` juga menunjuk ke file yang sama:

```html
<button
  class="image-button"
  data-full="images/foto-pesawat.jpg"
  data-title="Pesawat di Bandara"
  data-category-label="AVIATION">
```

## Materi coding yang dipelajari

- **HTML:** struktur halaman, teks, gambar, tautan, dan tombol.
- **CSS:** warna, layout, grid, animasi, dan tampilan responsif.
- **JavaScript:** filter galeri, lightbox foto, menu HP, dan tahun otomatis.

## Catatan

Foto contoh memakai URL Unsplash, sehingga perlu koneksi internet untuk menampilkannya. Gunakan foto milik sendiri atau gambar yang kamu punya izin untuk pakai sebelum mempublikasikan portfolio.
