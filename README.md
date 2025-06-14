# WatchCoin Site

Template sederhana untuk menampilkan berita dari NewsAPI dengan desain mirip WatchCoin.

## Cara Pakai

1. Signup ke [newsapi.org](https://newsapi.org/) dan dapatkan **API Key**.
2. Ganti `YOUR_API_KEY_HERE` di `index.html` dengan API Key-mu.
3. Buat repo GitHub bernama `watchcoin-site` (atau apa pun).
4. Upload kedua file (`index.html` & `README.md`).
5. Aktifkan **GitHub Pages**: Settings → Pages → pilih branch `main`.
6. Akses melalui `https://username.github.io/watchcoin-site/`.

---

## Kustomisasi

- **Jumlah artikel**: ubah `pageSize` di URL `fetch()`.
- **Negara**: ganti `country=us` ke kode lain (`id` untuk Indonesia, dsb).
- **Gaya**: ubah CSS sesuai selera.
- **Menggunakan API lain**: fetch endpoint lain dan sesuaikan parsing di JavaScript.
