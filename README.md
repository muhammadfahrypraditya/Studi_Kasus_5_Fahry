# Studi_Kasus_5_Fahry
<img src="https://github.com/user-attachments/assets/a6e4a227-003c-430f-bb29-d281f570cfb6" alt="Kode hitung_parkir" align="right" width="400">

**Penjelasan Fungsi `hitung_parkir()`**
Fungsi ini digunakan untuk menghitung total biaya parkir berdasarkan jenis kendaraan dan lama waktu parkir (dalam jam).
- `if jenis == "mobil":` — Mengecek apakah kendaraan yang dimasukkan adalah "mobil".
- `tarif = 5000` — Jika benar mobil, tarif per jam Rp5.000.
- `else:` — Jika bukan "mobil" (dianggap motor).
- `tarif = 3000` — Tarif per jam Rp3.000.
- `total_biaya = tarif * lama_parkir` — Tarif dikalikan lama parkir.
- `return total_biaya` — Mengembalikan hasil biaya.

<br clear="right">

<img src="https://github.com/user-attachments/assets/3c44629d-72f2-4395-8139-34d2e565c515" alt="Validasi kendaraan dengan while True" align="right" width="400">

**Validasi Input Kendaraan**

untuk memastikan hanya bisa memasukkan jenis kendaraan yang valid ("mobil" atau "motor"). Jika salah ketik, program akan meminta input ulang tanpa keluar dari program.

- `while True:` — Membuat perulangan 
- `jenis_kendaraan = input(...)` — Meminta user memasukkan jenis kendaraan.
- `if jenis_kendaraan not in ("mobil", "motor"):` — Mengecek apakah input yang dimasukkan bukan "mobil" dan bukan "motor".
- `print("kendaraan tidak valid, coba lagi.")` — Menampilkan pesan error kalau input tidak sesuai.
- `continue` — Menghentikan proses saat ini dan langsung kembali ke awal `while True`, sehingga user diminta input ulang.

<br clear="right">

<img src="https://github.com/user-attachments/assets/af32b8d7-680b-4f63-8651-159c623517bc" alt="Input jam masuk, jam keluar, dan hitung biaya" align="right" width="400">

**Menghitung Lama Parkir dan Biaya**


- `jam_masuk = int(input(...))` —  memasukkan jam masuk kendaraan
- `jam_keluar = int(input(...))` —  memasukkan jam keluar kendaraan
- `lama_parkir = jam_keluar - jam_masuk` — Menghitung selisih jam keluar dan jam masuk untuk mendapatkan lama parkir (dalam jam).


<br clear="right">

<img src="https://github.com/user-attachments/assets/24b1d88f-8ab7-4eee-9c4c-c6227399c995" alt="Menampilkan hasil parkir" align="right" width="400">

**Menampilkan Hasil**

Bagian ini mencetak seluruh informasi parkir

- `print("========PARKIR========")` — Mencetak judul
- `print(f"jenis kendaraan : {jenis_kendaraan}")` — Menampilkan jenis kendaraan yang diinput .
- `print(f"jam masuk : {jam_masuk}")` — Menampilkan jam masuk kendaraan.
- `print(f"jam keluar : {jam_keluar}")` — Menampilkan jam keluar kendaraan.
- `print(f"lama parkir : {lama_parkir} jam")` — Menampilkan lama parkir 
- `print(f"biaya parkir : Rp{biaya_parkir:,}")` — Menampilkan total biaya parkir
- `break` — Menghentikan perulangan `while True`, sehingga program berhenti setelah hasil ditampilkan.

<br clear="right">


<img src="https://github.com/user-attachments/assets/197950cd-87e6-4d21-8c00-0a30bb1c2dca" alt="Menampilkan output" align="right" width="400">
- output kode diatas.
