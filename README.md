# KetikBareng

Latihan mengetik sambil menonton YouTube. Subtitle atau lirik tersinkron dengan video, dan baris bebas dipilih.

## Jalankan di komputer sendiri
    npx vercel dev
Buka http://localhost:3000

## Pasang gratis di internet
1. Buat akun gratis di vercel.com (atau netlify.com / cloudflare.com).
2. Dari folder ini jalankan `npx vercel --prod`, atau unggah ke GitHub lalu impor ke Vercel.

## Catatan
- `api/transcript.js` mengambil subtitle YouTube tanpa API key. YouTube kadang memblokir alamat IP server cloud. Jika gagal di internet tetapi berhasil di komputer sendiri, itu penyebabnya. Tempel transkrip manual sebagai cadangan.
- `api/lyrics.js` memakai lrclib.net (gratis). Waktu lirik mengikuti versi studio, jadi di video klip mungkin perlu "Geser waktu".
