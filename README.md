# Website Ditto – Konsultan Hyundai Semarang

Website statis menggunakan HTML, CSS, dan JavaScript biasa. Tidak membutuhkan Emergent, framework, database, atau proses build.

## File
- `index.html` — konten halaman
- `style.css` — desain responsif
- `script.js` — menu mobile dan tahun footer

## Cara melihat di laptop
Klik dua kali `index.html`, lalu buka dengan Chrome.

## Deploy gratis ke Cloudflare Pages
1. Buat akun GitHub dan buat repository baru, misalnya `ditto-hyundai-website`.
2. Upload tiga file (`index.html`, `style.css`, `script.js`) ke root repository.
3. Buat akun Cloudflare, buka Workers & Pages → Create → Pages → Connect to Git.
4. Pilih repository tadi. Framework preset: None. Build command: kosongkan. Build output directory: `/` atau root directory sesuai instruksi dashboard Cloudflare.
5. Deploy. Cloudflare akan memberi alamat `*.pages.dev`.
6. Setelah domain `dealerhyundaisemarang.com` dimiliki dan DNS dikelola di Cloudflare, tambahkan domain itu dari Custom domains pada project Pages dan ikuti instruksi DNS.

## Catatan sebelum publikasi
- Pastikan domain sudah dibeli atas nama/akun sendiri.
- Periksa kembali nomor WhatsApp pada link `wa.me` di `index.html`.
- Perbarui foto, harga, promo, spesifikasi, dan ketersediaan berdasarkan informasi resmi terbaru sebelum dipublikasikan.
- Website ini adalah website konsultasi personal dan bukan situs resmi Hyundai Motor Indonesia.
