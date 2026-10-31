# Pertemuan 12 - File I/O dan Error Handling

## Isi proyek
- `latihan/`: enam latihan membaca, menulis, append, dan menangani error.
- `tugas/rekap_nilai_file.py`: program Tugas 5 untuk merekap nilai.
- `data/nilai.txt`: data contoh berformat `NIM,nilai`.

## Cara menjalankan
Jalankan terminal dari folder utama proyek, lalu:

```bash
python latihan/01_tulis_file.py
python latihan/02_baca_file.py
python latihan/03_append_file.py
python latihan/04_proses_baris.py
python latihan/05_file_not_found.py
python latihan/06_value_error.py
python tugas/rekap_nilai_file.py
```

Gunakan Python 3. Program memakai `with open(..., encoding="utf-8")`,
mode `r`, `w`, `a`, serta penanganan `FileNotFoundError` dan `ValueError`.

## Format data
Satu baris berisi NIM dan nilai yang dipisahkan koma, misalnya `A001,85`.
Data pada folder ini hanya contoh.
