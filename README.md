# ZEN TOOLS — Premium Utility Suite

Website statis bertema hitam–emas, responsif untuk Android, tanpa backend dan tanpa biaya hosting wajib.

## Fitur
- Password Generator (opsi panjang dan jenis karakter; dibuat di browser)
- QR Code Maker (perlu internet untuk memuat QRCode.js dari CDN)
- Text Counter (karakter, karakter tanpa spasi, kata, kalimat, estimasi baca)
- Bio Maker
- Text Case Converter
- JSON Formatter / Validator / Minifier
- URL Encoder / Decoder
- Quick Notes (localStorage browser)
- Pencarian dan filter kategori, navigasi mobile, toast notifikasi

## Jalankan di Android
1. Simpan folder project dan buka `index.html` di browser atau gunakan editor HTML lokal.
2. Semua tools selain QR maker berjalan tanpa backend. QR maker memerlukan internet.
3. Catatan hanya tersimpan di browser/perangkat yang sama; data bisa hilang jika data situs/browser dihapus.

## Deploy gratis ke Vercel
1. Upload `index.html`, `style.css`, `app.js`, `vercel.json`, dan `README.md` ke repository GitHub.
2. Di Vercel pilih **Add New → Project**, import repository tersebut.
3. Framework preset: **Other**. Build command dan output directory dapat dikosongkan; ini website statis.
4. Klik **Deploy**.

Tidak ada login, database, API rahasia, backend, sinkronisasi cloud, atau kredensial yang disertakan. Google Fonts dan QRCode.js adalah dependensi CDN eksternal.
