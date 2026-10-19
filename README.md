# test-app

Kalkulator kurs dolar sederhana: konversi USD ↔ Rupiah (IDR) dengan kurs terbaru.

## Cara pakai

Buka `index.html` di browser. Tidak perlu instalasi atau build.

- Ketik jumlah, hasil konversi langsung muncul.
- Tombol ⇅ menukar arah (USD → IDR atau IDR → USD).
- Tombol "Perbarui kurs" mengambil kurs terbaru (paling cepat tiap 5 menit).

## Sumber kurs

Kurs diambil dari [open.er-api.com](https://www.exchangerate-api.com) (ExchangeRate-API, akses terbuka tanpa kunci). Jika gagal, aplikasi mencoba [frankfurter.dev](https://frankfurter.dev). Hasil disimpan sementara di browser selama 1 jam karena kurs hanya diperbarui sekali sehari dan API membatasi jumlah permintaan.

Kurs yang ditampilkan adalah kurs tengah sebagai perkiraan, bukan kurs jual/beli bank.
