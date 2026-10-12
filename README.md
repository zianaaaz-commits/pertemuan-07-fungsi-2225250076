# Pertemuan 07 Fungsi Python

**Nama:** Ziana Alfia Zahra 
**NIM:** 2225250076  
**Kelas:** 3A

## Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan

Jalankan program praktik melalui terminal VS Code dengan perintah:

```bash
python3 praktik/utilitas_matematika.py
```

Pada Windows, perintah dapat menggunakan `python` jika `python3` tidak tersedia.

## Struktur Fungsi

| Nama Fungsi | Parameter | Nilai Return |
|---|---|---|
| `luas_persegi_panjang(p, l)` | `p`, `l` | Hasil perkalian panjang dan lebar |
| `luas_segitiga(a, t)` | `a`, `t` | Hasil perhitungan luas segitiga |
| `jumlah_n(n)` | `n` | Jumlah bilangan dari 1 sampai n |
| `faktorial(n)` | `n` | Hasil faktorial bilangan n |
| `tampilkan_menu()` | Tidak ada | Tidak mengembalikan nilai; menampilkan menu |

## Hasil Pengujian

| Fungsi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---:|---:|---|
| Luas persegi panjang | `p=8, l=5` | 40 | 40 | Berhasil |
| Luas segitiga | `a=10, t=6` | 30.0 | 30.0 | Berhasil |
| Jumlah 1 sampai n | `n=10` | 55 | 55 | Berhasil |
| Faktorial | `n=5` | 120 | 120 | Berhasil |
| Faktorial | `n=0` | 1 | 1 | Berhasil |

## Refleksi

Program menjadi lebih sederhana setelah perhitungan dipisahkan menjadi beberapa fungsi. Setiap fungsi memiliki tugas masing-masing sehingga rumus dapat digunakan kembali dengan input yang berbeda. Penggunaan parameter memudahkan pemberian input, sedangkan `return` memungkinkan hasil perhitungan digunakan kembali dalam program utama.