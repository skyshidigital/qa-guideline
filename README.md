QA Checklist Problem Solving
============================
Berikut checklist problem solving mengenai Quality Assurance yang terjadi per kasus dengan tujuan sebagai referensi Quality Assurance agar meminimalisir pengulangan permasalahan yang terjadi.


| No | Tema  | Masalah  | Penyebab  | Solusi  |
| :--------:  | --------| -------- | --------   | -------- |
| 1 | Pengecekan skenario QA | Terjadi fail dalam melakukan pengujian aliran data antar role yang berbeda | <ul><li>Pengujian dilakukan masih lingkup perfungsi</li><li>Tidak dilakukan pengecekan pada lingkup role yang berbeda</li></ul> |Pengujian dilakukan mengikuti aliran data dan aliran skenario antar role  |
| 2 | Uji coba pada data yang memiliki antar relasi yang sama| Data A memiliki relasi dengan data X, Ketika data A dihapus berpengaruh pada data X gagal diassign ke data B http://prntscr.com/o9ubuv | |Dilakukan pengecekan dan uji coba pada semua form yang memiliki relasi berhasil atau tidak ketika dilakukan assign di data lain |
| 3 | URL tidak SEO friendly | ID URL terlalu panjang pada URL produk dan kategori | Tidak diperhatikan dalam penulisan URL secara detail | <ul><li>Semua halaman list terutama list produk image harus dapat di click dan URL yang digunakan harus dengan ID yang pendek</li><li>URL harus SEO friendly dan human rreadable</li>|
| 4 | Penanganan image pada list produk|Pada halaman list produk image tidak clickable http://prntscr.com/oabnjo| Tidak ditambahkan fungsi clickable pada image | Semua halaman terutama list produk, image dan judul harus clickable |
