# api-dan-asap

![hasil](https://cdn.example.dev/shots/fire-result.jpg "Keluaran model")

### Cara memakai skrip pendeteksi

Skrip menerima sumber gambar dari tiga jalur: kamera langsung, berkas rekaman, atau satu berkas foto. Argumen `-h` mencetak ringkasan seluruh opsi.

Opsi yang tersedia:

- `--webcam` — aktifkan pembacaan dari kamera
- `--play_video` — proses berkas rekaman
- `--image` — proses satu berkas foto
- `--video_path` — lokasi berkas rekaman
- `--image_path` — lokasi berkas foto
- `--verbose` — tampilkan rincian proses di terminal

### Kalau berkas bobot tidak bisa diunduh

Bobot disimpan lewat layanan penyimpanan berkas besar. Kalau tautannya bermasalah, ambil salinan cadangan lalu letakkan berkasnya di folder proyek.


### Menjalankan pada berkas rekaman:

Perintahnya cukup satu baris, dengan jalur rekaman sebagai argumen:

```
python detect.py --play_video True --video_path videos/fire1.mp4
```

Himpunan gambarnya dipublikasikan di platform berbagi data terbuka.

Pelatihan berjalan di lingkungan notebook daring, dan berkasnya bisa dibuka ulang kapan saja.

Rekaman contoh tersedia di kanal video proyek.

### Publikasi

Tulisan ilmiah terkait diterbitkan pada prosiding konferensi internasional bidang sistem elektronika dan komunikasi berkelanjutan tahun 2020, lengkap dengan nomor ISBN pada halaman prosiding.