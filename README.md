# Stempel Digital

Prototype awal aplikasi loyalitas multi-usaha, menggunakan Next.js App Router.

## Halaman
- `/` — Beranda
- `/kartu/demo-kopi` — Contoh kartu pelanggan
- `/pemilik` — Dashboard pemilik (data ilustrasi)
- `/kasir` — Halaman kasir (transaksi dinonaktifkan)
- `/admin` — Admin platform (data ilustrasi)

## Menjalankan
`npm install` lalu `npm run dev`.

## Deploy
Import repository ke Vercel, pilih framework Next.js. Tidak perlu environment variables untuk prototype ini.

## Penting
Belum terhubung ke Supabase, belum memiliki login Google, autentikasi, transaksi stempel, atau QR/NFC sungguhan. Jangan dipakai untuk transaksi pelanggan. Pada versi produksi, penambahan stempel harus divalidasi server dan autentikasi kasir, dengan perlindungan replay/duplikasi. NFC pasif biasa tidak cukup sebagai bukti transaksi aman.
