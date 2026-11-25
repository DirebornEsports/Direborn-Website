# Direborn Website

Redesign direborn.team — gaya **Signal / Mono Brutalist**.

Halaman utama adalah gateway "pilih sisi":

- **Side A — Direborn** (merah): tim, roster, reel, matches, partners → `#direborn`
- **Side B — Dire Battle** (hijau): Uprising 1, registrasi + countdown, Dire Battle Pro Circuit, hasil Dire Battle Cup, daftar turnamen, about → `#direbattle`

Satu file statis (`index.html`): HTML + CSS + JS vanilla, font dari Google Fonts. Tidak perlu build — bisa langsung di-host di Vercel, Cloudflare Pages, atau GitHub Pages.

## Masih placeholder

- [ ] Logo resmi (sekarang kotak merah + teks)
- [ ] Foto 5 pemain (sekarang siluet; kartu punya fitur preview foto lokal untuk cek layout)
- [ ] Video reel Direborn & Dire Battle (tombol Play masih ke Instagram)
- [ ] Jadwal & hasil match Direborn (masih empty state)
- [ ] Link registrasi & schedule masih mengarah ke direborn.team lama

## Catatan data

- Countdown registrasi Uprising 1 berakhir **16 Nov 2026 23:59 WIB** (sudah lewat → otomatis tampil "Registration closed"). Update tanggal di `const close=` dan teks event bila ada event berikutnya.
- Data Grand Final & earlier series ada di array `GAMES` dan `SERIES` di bagian `<script>`.
