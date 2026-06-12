# Flappy Cat — Sky Adventure

Flappy Cat adalah game arcade berbasis browser yang dibuat dalam satu file HTML. Pemain mengendalikan Miko, seekor kucing terbang, untuk melewati rintangan, menghadapi tantangan yang terus berubah, dan mencapai pertarungan boss terakhir melawan Dog Si Nakal.

## Mainkan Sekarang

[Klik di sini untuk memainkan Flappy Cat](https://cat-flappy.netlify.app/)

## Tentang Game

Game ini terinspirasi dari mekanisme permainan arcade sederhana dengan kontrol satu tombol, tetapi dikembangkan dengan tema kucing, tampilan modern, tantangan bertingkat, pergantian tema, pilihan warna karakter, efek suara, serta boss battle.

Semua sistem utama berjalan langsung di browser tanpa instalasi tambahan dan tanpa backend.

## Fitur Utama

- Game berjalan langsung melalui browser.
- Dibuat dalam satu file HTML.
- Responsif untuk desktop, laptop, tablet, dan smartphone.
- Mendukung kontrol keyboard dan layar sentuh.
- Pilihan warna karakter Miko sebelum bermain.
- Tantangan baru setiap 5 skor.
- Pergantian tema setiap 30 skor.
- Variasi tantangan seperti speed rush, celah sempit, menara bergerak, gravitasi berat, gravitasi ringan, angin silang, menara lebar, dan celah berdenyut.
- Boss battle melawan Dog Si Nakal pada skor 1.000.000.000.
- Miko dapat melempar tulang ikan saat pertarungan boss.
- Dog Si Nakal memiliki HP dan beberapa pola serangan.
- Sistem suara dapat dinyalakan atau dimatikan.
- Fitur pause dan resume.
- Skor tertinggi dimulai dari nol pada setiap kunjungan baru.
- Tidak menggunakan database.
- Tidak menggunakan framework eksternal.
- Dapat dimainkan secara lokal dan offline.

## Kontrol

| Perangkat | Kontrol |
|---|---|
| Desktop atau Laptop | Tekan Space untuk terbang |
| Desktop atau Laptop | Tekan P untuk pause atau resume |
| Smartphone atau Tablet | Tap layar untuk terbang |
| Boss Battle | Tap atau tekan Space untuk terbang dan melempar tulang ikan |

## Cara Menjalankan di Komputer

1. Download atau clone repository ini.
2. Buka folder project.
3. Klik dua kali file `index.html`.
4. Game akan langsung terbuka di browser.

## Cara Clone Repository

```bash
git clone https://github.com/USERNAME/NAMA-REPOSITORY.git
cd NAMA-REPOSITORY
```

Setelah itu, buka file `index.html` menggunakan browser.

## Struktur Project

```text
flappy-cat/
├── index.html
└── README.md
```

## Teknologi

- HTML5
- CSS3
- JavaScript
- Canvas API
- Web Audio API
- Local Storage untuk preferensi suara dan warna karakter

## Cara Upload ke GitHub

1. Buat repository baru di GitHub.
2. Beri nama repository, misalnya `flappy-cat-sky-adventure`.
3. Upload file `index.html` dan `README.md`.
4. Simpan perubahan dengan commit.
5. Buka menu Settings pada repository.
6. Pilih Pages.
7. Pada bagian Build and deployment, pilih Deploy from a branch.
8. Pilih branch `main` dan folder `/root`.
9. Klik Save.
10. Tunggu hingga GitHub Pages memberikan link publik.

## Demo

Demo aktif:

https://cat-flappy.netlify.app/

## Catatan

GitHub README tidak dapat menjalankan game HTML langsung di dalam halaman README. Karena itu, tombol Mainkan Sekarang akan membuka versi game yang sudah dipublikasikan melalui Netlify.

## Developer

Dikembangkan oleh Aidil Farhan Rares.

## Lisensi

Project ini dibuat untuk pembelajaran, portofolio, dan pengembangan pribadi.
