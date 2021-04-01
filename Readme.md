# Daftar Bank Indonesia

Daftar bank indonesia yang diambil dari jaringanprima.co.id menggunakan pyinstantcrawl

## Penggunaan

Bila anda ingin melakukan update data, pastikan anda telah menginstall `pyinstantcrawl`

```
pip install pyinstantcrawl
```

setelah itu, issue command berikut

```
pyinstantcrawl https://www.jaringanprima.co.id/kode_bank/get_bank?format=json scraper.json > bank-list.json
```
